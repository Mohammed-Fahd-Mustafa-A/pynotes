---
title: Ev
date: 2025-06-29
author: Your Name
cell_count: 16
score: 15
---

```python
# Block 1: Import necessary libraries
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import plotly.express as px
import numpy as np

```


```python
# Block 2: Load the dataset
# Sample EV adoption dataset (can replace with real one)
data = {
    'Country': ['USA', 'China', 'Norway', 'Germany', 'UK', 'India', 'France', 'Canada', 'Netherlands', 'Japan'],
    'EV_Sales_2020': [330000, 1300000, 105000, 194000, 175000, 22000, 111000, 54000, 90000, 56000],
    'EV_Sales_2021': [607000, 3200000, 153000, 355000, 310000, 48000, 165000, 94000, 115000, 87000],
    'EV_Sales_2022': [918000, 6800000, 174000, 475000, 420000, 90000, 200000, 123000, 130000, 110000],
}
df = pd.DataFrame(data)
df

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
      <th>Country</th>
      <th>EV_Sales_2020</th>
      <th>EV_Sales_2021</th>
      <th>EV_Sales_2022</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>USA</td>
      <td>330000</td>
      <td>607000</td>
      <td>918000</td>
    </tr>
    <tr>
      <th>1</th>
      <td>China</td>
      <td>1300000</td>
      <td>3200000</td>
      <td>6800000</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Norway</td>
      <td>105000</td>
      <td>153000</td>
      <td>174000</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Germany</td>
      <td>194000</td>
      <td>355000</td>
      <td>475000</td>
    </tr>
    <tr>
      <th>4</th>
      <td>UK</td>
      <td>175000</td>
      <td>310000</td>
      <td>420000</td>
    </tr>
    <tr>
      <th>5</th>
      <td>India</td>
      <td>22000</td>
      <td>48000</td>
      <td>90000</td>
    </tr>
    <tr>
      <th>6</th>
      <td>France</td>
      <td>111000</td>
      <td>165000</td>
      <td>200000</td>
    </tr>
    <tr>
      <th>7</th>
      <td>Canada</td>
      <td>54000</td>
      <td>94000</td>
      <td>123000</td>
    </tr>
    <tr>
      <th>8</th>
      <td>Netherlands</td>
      <td>90000</td>
      <td>115000</td>
      <td>130000</td>
    </tr>
    <tr>
      <th>9</th>
      <td>Japan</td>
      <td>56000</td>
      <td>87000</td>
      <td>110000</td>
    </tr>
  </tbody>
</table>
</div>




```python
# Block 3: Calculate Growth Rate
df["Growth_2020_2021"] = ((df["EV_Sales_2021"] - df["EV_Sales_2020"]) / df["EV_Sales_2020"]) * 100
df["Growth_2021_2022"] = ((df["EV_Sales_2022"] - df["EV_Sales_2021"]) / df["EV_Sales_2021"]) * 100
df.round(2)

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
      <th>Country</th>
      <th>EV_Sales_2020</th>
      <th>EV_Sales_2021</th>
      <th>EV_Sales_2022</th>
      <th>Growth_2020_2021</th>
      <th>Growth_2021_2022</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>USA</td>
      <td>330000</td>
      <td>607000</td>
      <td>918000</td>
      <td>83.94</td>
      <td>51.24</td>
    </tr>
    <tr>
      <th>1</th>
      <td>China</td>
      <td>1300000</td>
      <td>3200000</td>
      <td>6800000</td>
      <td>146.15</td>
      <td>112.50</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Norway</td>
      <td>105000</td>
      <td>153000</td>
      <td>174000</td>
      <td>45.71</td>
      <td>13.73</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Germany</td>
      <td>194000</td>
      <td>355000</td>
      <td>475000</td>
      <td>82.99</td>
      <td>33.80</td>
    </tr>
    <tr>
      <th>4</th>
      <td>UK</td>
      <td>175000</td>
      <td>310000</td>
      <td>420000</td>
      <td>77.14</td>
      <td>35.48</td>
    </tr>
    <tr>
      <th>5</th>
      <td>India</td>
      <td>22000</td>
      <td>48000</td>
      <td>90000</td>
      <td>118.18</td>
      <td>87.50</td>
    </tr>
    <tr>
      <th>6</th>
      <td>France</td>
      <td>111000</td>
      <td>165000</td>
      <td>200000</td>
      <td>48.65</td>
      <td>21.21</td>
    </tr>
    <tr>
      <th>7</th>
      <td>Canada</td>
      <td>54000</td>
      <td>94000</td>
      <td>123000</td>
      <td>74.07</td>
      <td>30.85</td>
    </tr>
    <tr>
      <th>8</th>
      <td>Netherlands</td>
      <td>90000</td>
      <td>115000</td>
      <td>130000</td>
      <td>27.78</td>
      <td>13.04</td>
    </tr>
    <tr>
      <th>9</th>
      <td>Japan</td>
      <td>56000</td>
      <td>87000</td>
      <td>110000</td>
      <td>55.36</td>
      <td>26.44</td>
    </tr>
  </tbody>
</table>
</div>




```python
# Block 4: Bar chart - 2022 EV Sales by Country
plt.figure(figsize=(10,6))
sns.barplot(x="EV_Sales_2022", y="Country", data=df, palette="viridis")
plt.title("EV Sales in 2022 by Country")
plt.xlabel("EV Units Sold")
plt.ylabel("Country")
plt.tight_layout()
plt.show()

```

    C:\Users\HP\AppData\Local\Temp\ipykernel_11660\3378219073.py:3: FutureWarning: 
    
    Passing `palette` without assigning `hue` is deprecated and will be removed in v0.14.0. Assign the `y` variable to `hue` and set `legend=False` for the same effect.
    
      sns.barplot(x="EV_Sales_2022", y="Country", data=df, palette="viridis")
    


    
![png](/pynotes/images/EV_3_1.png)
    



```python
# Block 5: Line plot - Year-wise EV sales
df_long = pd.melt(df, id_vars=['Country'], value_vars=['EV_Sales_2020', 'EV_Sales_2021', 'EV_Sales_2022'],
                  var_name='Year', value_name='EV_Sales')
df_long['Year'] = df_long['Year'].str.extract(r'(\d+)')  # <-- fixed here
df_long['Year'] = df_long['Year'].astype(int)

plt.figure(figsize=(12,6))
sns.lineplot(data=df_long, x='Year', y='EV_Sales', hue='Country', marker='o')
plt.title("EV Sales Over Years")
plt.ylabel("EV Units Sold")
plt.show()

```


    
![png](/pynotes/images/EV_4_0.png)
    



```python
# Block 6: Heatmap for growth percentages
growth_data = df[["Country", "Growth_2020_2021", "Growth_2021_2022"]].set_index("Country")
plt.figure(figsize=(10,5))
sns.heatmap(growth_data, annot=True, cmap="YlGnBu", fmt=".1f")
plt.title("EV Sales Growth Percentage (2020–2022)")
plt.show()

```


    
![png](/pynotes/images/EV_5_0.png)
    



```python
# Block 7: Top 5 countries by 2022 EV sales
top5 = df.sort_values(by="EV_Sales_2022", ascending=False).head(5)
top5[['Country', 'EV_Sales_2022']]

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
      <th>Country</th>
      <th>EV_Sales_2022</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>1</th>
      <td>China</td>
      <td>6800000</td>
    </tr>
    <tr>
      <th>0</th>
      <td>USA</td>
      <td>918000</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Germany</td>
      <td>475000</td>
    </tr>
    <tr>
      <th>4</th>
      <td>UK</td>
      <td>420000</td>
    </tr>
    <tr>
      <th>6</th>
      <td>France</td>
      <td>200000</td>
    </tr>
  </tbody>
</table>
</div>




```python
# Block 8: Pie chart of market share (2022)
plt.figure(figsize=(8,8))
plt.pie(df["EV_Sales_2022"], labels=df["Country"], autopct='%1.1f%%', startangle=140)
plt.title("Global Market Share of EV Sales (2022)")
plt.axis('equal')
plt.show()

```


    
![png](/pynotes/images/EV_7_0.png)
    



```python
# Block 9: Scatter plot - 2022 vs Growth
plt.figure(figsize=(10,6))
sns.scatterplot(x="EV_Sales_2022", y="Growth_2021_2022", data=df, hue="Country", s=100)
plt.title("2022 Sales vs Growth (2021–2022)")
plt.xlabel("EV Sales 2022")
plt.ylabel("Growth %")
plt.grid(True)
plt.show()

```


    
![png](/pynotes/images/EV_8_0.png)
    



```python
# Block 10: Interactive Plotly bar chart
fig = px.bar(df, x='Country', y=['EV_Sales_2020', 'EV_Sales_2021', 'EV_Sales_2022'],
             title='EV Sales by Country (2020–2022)', barmode='group')
fig.show()

```




```python
# Block 11: Add average sales column
df["Average_Sales"] = df[["EV_Sales_2020", "EV_Sales_2021", "EV_Sales_2022"]].mean(axis=1).astype(int)
df[["Country", "Average_Sales"]]

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
      <th>Country</th>
      <th>Average_Sales</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>USA</td>
      <td>618333</td>
    </tr>
    <tr>
      <th>1</th>
      <td>China</td>
      <td>3766666</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Norway</td>
      <td>144000</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Germany</td>
      <td>341333</td>
    </tr>
    <tr>
      <th>4</th>
      <td>UK</td>
      <td>301666</td>
    </tr>
    <tr>
      <th>5</th>
      <td>India</td>
      <td>53333</td>
    </tr>
    <tr>
      <th>6</th>
      <td>France</td>
      <td>158666</td>
    </tr>
    <tr>
      <th>7</th>
      <td>Canada</td>
      <td>90333</td>
    </tr>
    <tr>
      <th>8</th>
      <td>Netherlands</td>
      <td>111666</td>
    </tr>
    <tr>
      <th>9</th>
      <td>Japan</td>
      <td>84333</td>
    </tr>
  </tbody>
</table>
</div>




```python
# Block 12: Highlight countries with below-average growth
threshold = df["Growth_2021_2022"].mean()
below_avg = df[df["Growth_2021_2022"] < threshold]
below_avg[["Country", "Growth_2021_2022"]]

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
      <th>Country</th>
      <th>Growth_2021_2022</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>2</th>
      <td>Norway</td>
      <td>13.725490</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Germany</td>
      <td>33.802817</td>
    </tr>
    <tr>
      <th>4</th>
      <td>UK</td>
      <td>35.483871</td>
    </tr>
    <tr>
      <th>6</th>
      <td>France</td>
      <td>21.212121</td>
    </tr>
    <tr>
      <th>7</th>
      <td>Canada</td>
      <td>30.851064</td>
    </tr>
    <tr>
      <th>8</th>
      <td>Netherlands</td>
      <td>13.043478</td>
    </tr>
    <tr>
      <th>9</th>
      <td>Japan</td>
      <td>26.436782</td>
    </tr>
  </tbody>
</table>
</div>




```python
# Block 13: Correlation heatmap
plt.figure(figsize=(8,6))
sns.heatmap(df.corr(numeric_only=True), annot=True, cmap="coolwarm")
plt.title("Correlation Between Numeric Features")
plt.show()

```


    
![png](/pynotes/images/EV_12_0.png)
    



```python
# Block 14: Boxplot of sales over years
plt.figure(figsize=(10,5))
sns.boxplot(data=df_long, x="Year", y="EV_Sales")
plt.title("Distribution of EV Sales Over the Years")
plt.show()

```


    
![png](/pynotes/images/EV_13_0.png)
    



```python
# Block 15: Save results to CSV
df.to_csv("ev_sales_analysis.csv", index=False)
print("Data saved to ev_sales_analysis.csv")

```

    Data saved to ev_sales_analysis.csv
    


```python

```


---
**Score: 15**