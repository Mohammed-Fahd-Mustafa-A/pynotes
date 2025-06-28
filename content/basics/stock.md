---
title: Stock
date: 2025-06-29
author: Your Name
cell_count: 20
score: 20
---

```python
# Block 1: Install required packages (if not already installed)
!pip install yfinance matplotlib --quiet

```


```python
# Block 2: Import necessary libraries
import yfinance as yf
import matplotlib.pyplot as plt
import pandas as pd

```


```python
# Block 3: Set display options for better visualization
pd.set_option("display.max_rows", 10)
pd.set_option("display.float_format", "{:.2f}".format)

```


```python
# Block 4: Download historical stock data for Apple (AAPL)
stock = yf.Ticker("AAPL")
df = stock.history(period="1y")
df.head()

```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Open</th>
      <th>High</th>
      <th>Low</th>
      <th>Close</th>
      <th>Volume</th>
      <th>Dividends</th>
      <th>Stock Splits</th>
    </tr>
    <tr>
      <th>Date</th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>2024-06-28 00:00:00-04:00</th>
      <td>214.77</td>
      <td>215.06</td>
      <td>209.32</td>
      <td>209.64</td>
      <td>82542700</td>
      <td>0.00</td>
      <td>0.00</td>
    </tr>
    <tr>
      <th>2024-07-01 00:00:00-04:00</th>
      <td>211.10</td>
      <td>216.50</td>
      <td>210.93</td>
      <td>215.74</td>
      <td>60402900</td>
      <td>0.00</td>
      <td>0.00</td>
    </tr>
    <tr>
      <th>2024-07-02 00:00:00-04:00</th>
      <td>215.14</td>
      <td>219.35</td>
      <td>214.10</td>
      <td>219.24</td>
      <td>58046200</td>
      <td>0.00</td>
      <td>0.00</td>
    </tr>
    <tr>
      <th>2024-07-03 00:00:00-04:00</th>
      <td>218.98</td>
      <td>220.52</td>
      <td>218.01</td>
      <td>220.52</td>
      <td>37369800</td>
      <td>0.00</td>
      <td>0.00</td>
    </tr>
    <tr>
      <th>2024-07-05 00:00:00-04:00</th>
      <td>220.62</td>
      <td>225.40</td>
      <td>220.62</td>
      <td>225.29</td>
      <td>60412400</td>
      <td>0.00</td>
      <td>0.00</td>
    </tr>
  </tbody>
</table>
</div>




```python
# Block 5: Basic Information
print("Company Info:")
stock.info['longBusinessSummary'][:300] + "..."

```

    Company Info:
    




    'Apple Inc. designs, manufactures, and markets smartphones, personal computers, tablets, wearables, and accessories worldwide. The company offers iPhone, a line of smartphones; Mac, a line of personal computers; iPad, a line of multi-purpose tablets; and wearables, home, and accessories comprising Ai...'




```python
# Block 6: Describe the dataset
df.describe()

```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Open</th>
      <th>High</th>
      <th>Low</th>
      <th>Close</th>
      <th>Volume</th>
      <th>Dividends</th>
      <th>Stock Splits</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>count</th>
      <td>250.00</td>
      <td>250.00</td>
      <td>250.00</td>
      <td>250.00</td>
      <td>250.00</td>
      <td>250.00</td>
      <td>250.00</td>
    </tr>
    <tr>
      <th>mean</th>
      <td>222.36</td>
      <td>224.92</td>
      <td>220.02</td>
      <td>222.67</td>
      <td>53516737.60</td>
      <td>0.00</td>
      <td>0.00</td>
    </tr>
    <tr>
      <th>std</th>
      <td>15.69</td>
      <td>15.12</td>
      <td>15.96</td>
      <td>15.61</td>
      <td>27343853.63</td>
      <td>0.03</td>
      <td>0.00</td>
    </tr>
    <tr>
      <th>min</th>
      <td>171.72</td>
      <td>190.09</td>
      <td>168.99</td>
      <td>172.19</td>
      <td>23234700.00</td>
      <td>0.00</td>
      <td>0.00</td>
    </tr>
    <tr>
      <th>25%</th>
      <td>211.19</td>
      <td>214.02</td>
      <td>209.38</td>
      <td>212.35</td>
      <td>39510475.00</td>
      <td>0.00</td>
      <td>0.00</td>
    </tr>
    <tr>
      <th>50%</th>
      <td>224.17</td>
      <td>226.07</td>
      <td>222.23</td>
      <td>224.21</td>
      <td>46906700.00</td>
      <td>0.00</td>
      <td>0.00</td>
    </tr>
    <tr>
      <th>75%</th>
      <td>232.45</td>
      <td>234.26</td>
      <td>229.18</td>
      <td>232.52</td>
      <td>58825975.00</td>
      <td>0.00</td>
      <td>0.00</td>
    </tr>
    <tr>
      <th>max</th>
      <td>257.57</td>
      <td>259.47</td>
      <td>257.01</td>
      <td>258.40</td>
      <td>318679900.00</td>
      <td>0.26</td>
      <td>0.00</td>
    </tr>
  </tbody>
</table>
</div>




```python
# Block 7: Plot closing price
plt.figure(figsize=(12, 5))
plt.plot(df['Close'], label="Close Price", color='blue')
plt.title("Apple (AAPL) - Closing Price")
plt.xlabel("Date")
plt.ylabel("Price (USD)")
plt.legend()
plt.grid(True)
plt.show()

```


    
![png](/pynotes/images/stock_6_0.png)
    



```python
# Block 8: Calculate Moving Averages
df['MA20'] = df['Close'].rolling(window=20).mean()
df['MA50'] = df['Close'].rolling(window=50).mean()
df[['Close', 'MA20', 'MA50']].tail()

```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Close</th>
      <th>MA20</th>
      <th>MA50</th>
    </tr>
    <tr>
      <th>Date</th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>2025-06-23 00:00:00-04:00</th>
      <td>201.50</td>
      <td>200.04</td>
      <td>202.30</td>
    </tr>
    <tr>
      <th>2025-06-24 00:00:00-04:00</th>
      <td>200.30</td>
      <td>200.29</td>
      <td>202.50</td>
    </tr>
    <tr>
      <th>2025-06-25 00:00:00-04:00</th>
      <td>201.56</td>
      <td>200.36</td>
      <td>202.57</td>
    </tr>
    <tr>
      <th>2025-06-26 00:00:00-04:00</th>
      <td>201.00</td>
      <td>200.38</td>
      <td>202.55</td>
    </tr>
    <tr>
      <th>2025-06-27 00:00:00-04:00</th>
      <td>201.08</td>
      <td>200.44</td>
      <td>202.53</td>
    </tr>
  </tbody>
</table>
</div>




```python
# Block 9: Plot Moving Averages
plt.figure(figsize=(12, 6))
plt.plot(df['Close'], label='Close Price', alpha=0.5)
plt.plot(df['MA20'], label='20-day MA', color='orange')
plt.plot(df['MA50'], label='50-day MA', color='green')
plt.title("Moving Averages - AAPL")
plt.xlabel("Date")
plt.ylabel("Price (USD)")
plt.legend()
plt.grid(True)
plt.show()

```


    
![png](/pynotes/images/stock_8_0.png)
    



```python
# Block 10: Volume analysis
df['Volume'].plot(kind='hist', bins=30, color='purple', figsize=(10, 4), title='Trading Volume Distribution')

```




    <Axes: title={'center': 'Trading Volume Distribution'}, ylabel='Frequency'>




    
![png](/pynotes/images/stock_9_1.png)
    



```python
# Block 11: Daily Returns
df['Daily Return'] = df['Close'].pct_change()
df['Daily Return'].dropna().plot(figsize=(10, 5), linestyle='--', marker='o', title="Daily Return (%)")

```




    <Axes: title={'center': 'Daily Return (%)'}, xlabel='Date'>




    
![png](/pynotes/images/stock_10_1.png)
    



```python
# Block 12: Correlation Matrix (simulate multiple stocks)
tickers = ['AAPL', 'MSFT', 'GOOG', 'AMZN']
df_multi = yf.download(tickers, period="6mo")['Close']
df_multi = df_multi.pct_change().dropna()
correlation = df_multi.corr()
correlation

```

    C:\Users\HP\AppData\Local\Temp\ipykernel_6508\2024470801.py:3: FutureWarning: YF.download() has changed argument auto_adjust default to True
      df_multi = yf.download(tickers, period="6mo")['Close']
    [*********************100%***********************]  4 of 4 completed
    




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th>Ticker</th>
      <th>AAPL</th>
      <th>AMZN</th>
      <th>GOOG</th>
      <th>MSFT</th>
    </tr>
    <tr>
      <th>Ticker</th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>AAPL</th>
      <td>1.00</td>
      <td>0.70</td>
      <td>0.56</td>
      <td>0.62</td>
    </tr>
    <tr>
      <th>AMZN</th>
      <td>0.70</td>
      <td>1.00</td>
      <td>0.71</td>
      <td>0.74</td>
    </tr>
    <tr>
      <th>GOOG</th>
      <td>0.56</td>
      <td>0.71</td>
      <td>1.00</td>
      <td>0.60</td>
    </tr>
    <tr>
      <th>MSFT</th>
      <td>0.62</td>
      <td>0.74</td>
      <td>0.60</td>
      <td>1.00</td>
    </tr>
  </tbody>
</table>
</div>




```python
# Block 13: Heatmap of correlation
import seaborn as sns
plt.figure(figsize=(8, 6))
sns.heatmap(correlation, annot=True, cmap="coolwarm")
plt.title("Correlation Between Stocks")

```




    Text(0.5, 1.0, 'Correlation Between Stocks')




    
![png](/pynotes/images/stock_12_1.png)
    



```python
# Block 14: Candlestick Chart (optional for advanced visuals)
!pip install plotly



```

    Requirement already satisfied: plotly in c:\users\hp\miniconda3\envs\py312\lib\site-packages (6.2.0)
    Requirement already satisfied: narwhals>=1.15.1 in c:\users\hp\miniconda3\envs\py312\lib\site-packages (from plotly) (1.44.0)
    Requirement already satisfied: packaging in c:\users\hp\miniconda3\envs\py312\lib\site-packages (from plotly) (24.2)
    


```python
import plotly.graph_objects as go
fig = go.Figure(data=[go.Candlestick(x=df.index,
                open=df['Open'],
                high=df['High'],
                low=df['Low'],
                close=df['Close'])])
fig.update_layout(title='Candlestick Chart - AAPL', xaxis_rangeslider_visible=False)
fig.show()

```




```python
# Block 15: Highest closing price
highest = df['Close'].max()
print(f"Highest Closing Price in the Last 1 Year: ${highest:.2f}")

```

    Highest Closing Price in the Last 1 Year: $258.40
    


```python
# Block 16: Lowest closing price
lowest = df['Close'].min()
print(f"Lowest Closing Price in the Last 1 Year: ${lowest:.2f}")

```

    Lowest Closing Price in the Last 1 Year: $172.19
    


```python
# Block 17: Save processed data to CSV
df.to_csv("AAPL_Processed.csv")
print("Saved to AAPL_Processed.csv")

```

    Saved to AAPL_Processed.csv
    


```python
# Block 18: Display final data sample
df.tail()

```




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Open</th>
      <th>High</th>
      <th>Low</th>
      <th>Close</th>
      <th>Volume</th>
      <th>Dividends</th>
      <th>Stock Splits</th>
      <th>MA20</th>
      <th>MA50</th>
      <th>Daily Return</th>
    </tr>
    <tr>
      <th>Date</th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>2025-06-23 00:00:00-04:00</th>
      <td>201.63</td>
      <td>202.30</td>
      <td>198.96</td>
      <td>201.50</td>
      <td>55814300</td>
      <td>0.00</td>
      <td>0.00</td>
      <td>200.04</td>
      <td>202.30</td>
      <td>0.00</td>
    </tr>
    <tr>
      <th>2025-06-24 00:00:00-04:00</th>
      <td>202.59</td>
      <td>203.44</td>
      <td>200.20</td>
      <td>200.30</td>
      <td>54064000</td>
      <td>0.00</td>
      <td>0.00</td>
      <td>200.29</td>
      <td>202.50</td>
      <td>-0.01</td>
    </tr>
    <tr>
      <th>2025-06-25 00:00:00-04:00</th>
      <td>201.45</td>
      <td>203.67</td>
      <td>200.62</td>
      <td>201.56</td>
      <td>39525700</td>
      <td>0.00</td>
      <td>0.00</td>
      <td>200.36</td>
      <td>202.57</td>
      <td>0.01</td>
    </tr>
    <tr>
      <th>2025-06-26 00:00:00-04:00</th>
      <td>201.43</td>
      <td>202.64</td>
      <td>199.46</td>
      <td>201.00</td>
      <td>50799100</td>
      <td>0.00</td>
      <td>0.00</td>
      <td>200.38</td>
      <td>202.55</td>
      <td>-0.00</td>
    </tr>
    <tr>
      <th>2025-06-27 00:00:00-04:00</th>
      <td>201.89</td>
      <td>203.22</td>
      <td>200.00</td>
      <td>201.08</td>
      <td>73114100</td>
      <td>0.00</td>
      <td>0.00</td>
      <td>200.44</td>
      <td>202.53</td>
      <td>0.00</td>
    </tr>
  </tbody>
</table>
</div>




```python

```


---
**Score: 20**