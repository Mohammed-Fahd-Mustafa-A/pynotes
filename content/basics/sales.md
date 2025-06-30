---
title: Sales
date: 2025-06-30
author: Your Name
cell_count: 17
score: 15
---

```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

sns.set(style="whitegrid")

```


```python
data = {
    "OrderID": [1001, 1002, 1003, 1004, 1005, 1006],
    "Product": ["Laptop", "Mouse", "Keyboard", "Monitor", "Laptop", "Mouse"],
    "Category": ["Electronics", "Accessories", "Accessories", "Electronics", "Electronics", "Accessories"],
    "Price": [70000, 500, 1500, 12000, 72000, 550],
    "Quantity": [1, 2, 1, 2, 1, 3],
    "Date": pd.to_datetime(["2023-01-10", "2023-01-10", "2023-01-11", "2023-01-12", "2023-01-12", "2023-01-13"])
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
      <th>OrderID</th>
      <th>Product</th>
      <th>Category</th>
      <th>Price</th>
      <th>Quantity</th>
      <th>Date</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1001</td>
      <td>Laptop</td>
      <td>Electronics</td>
      <td>70000</td>
      <td>1</td>
      <td>2023-01-10</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1002</td>
      <td>Mouse</td>
      <td>Accessories</td>
      <td>500</td>
      <td>2</td>
      <td>2023-01-10</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1003</td>
      <td>Keyboard</td>
      <td>Accessories</td>
      <td>1500</td>
      <td>1</td>
      <td>2023-01-11</td>
    </tr>
    <tr>
      <th>3</th>
      <td>1004</td>
      <td>Monitor</td>
      <td>Electronics</td>
      <td>12000</td>
      <td>2</td>
      <td>2023-01-12</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1005</td>
      <td>Laptop</td>
      <td>Electronics</td>
      <td>72000</td>
      <td>1</td>
      <td>2023-01-12</td>
    </tr>
    <tr>
      <th>5</th>
      <td>1006</td>
      <td>Mouse</td>
      <td>Accessories</td>
      <td>550</td>
      <td>3</td>
      <td>2023-01-13</td>
    </tr>
  </tbody>
</table>
</div>




```python
df["Revenue"] = df["Price"] * df["Quantity"]
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
      <th>OrderID</th>
      <th>Product</th>
      <th>Category</th>
      <th>Price</th>
      <th>Quantity</th>
      <th>Date</th>
      <th>Revenue</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1001</td>
      <td>Laptop</td>
      <td>Electronics</td>
      <td>70000</td>
      <td>1</td>
      <td>2023-01-10</td>
      <td>70000</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1002</td>
      <td>Mouse</td>
      <td>Accessories</td>
      <td>500</td>
      <td>2</td>
      <td>2023-01-10</td>
      <td>1000</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1003</td>
      <td>Keyboard</td>
      <td>Accessories</td>
      <td>1500</td>
      <td>1</td>
      <td>2023-01-11</td>
      <td>1500</td>
    </tr>
    <tr>
      <th>3</th>
      <td>1004</td>
      <td>Monitor</td>
      <td>Electronics</td>
      <td>12000</td>
      <td>2</td>
      <td>2023-01-12</td>
      <td>24000</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1005</td>
      <td>Laptop</td>
      <td>Electronics</td>
      <td>72000</td>
      <td>1</td>
      <td>2023-01-12</td>
      <td>72000</td>
    </tr>
    <tr>
      <th>5</th>
      <td>1006</td>
      <td>Mouse</td>
      <td>Accessories</td>
      <td>550</td>
      <td>3</td>
      <td>2023-01-13</td>
      <td>1650</td>
    </tr>
  </tbody>
</table>
</div>




```python
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
      <th>OrderID</th>
      <th>Price</th>
      <th>Quantity</th>
      <th>Date</th>
      <th>Revenue</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>count</th>
      <td>6.000000</td>
      <td>6.000000</td>
      <td>6.000000</td>
      <td>6</td>
      <td>6.000000</td>
    </tr>
    <tr>
      <th>mean</th>
      <td>1003.500000</td>
      <td>26091.666667</td>
      <td>1.666667</td>
      <td>2023-01-11 08:00:00</td>
      <td>28358.333333</td>
    </tr>
    <tr>
      <th>min</th>
      <td>1001.000000</td>
      <td>500.000000</td>
      <td>1.000000</td>
      <td>2023-01-10 00:00:00</td>
      <td>1000.000000</td>
    </tr>
    <tr>
      <th>25%</th>
      <td>1002.250000</td>
      <td>787.500000</td>
      <td>1.000000</td>
      <td>2023-01-10 06:00:00</td>
      <td>1537.500000</td>
    </tr>
    <tr>
      <th>50%</th>
      <td>1003.500000</td>
      <td>6750.000000</td>
      <td>1.500000</td>
      <td>2023-01-11 12:00:00</td>
      <td>12825.000000</td>
    </tr>
    <tr>
      <th>75%</th>
      <td>1004.750000</td>
      <td>55500.000000</td>
      <td>2.000000</td>
      <td>2023-01-12 00:00:00</td>
      <td>58500.000000</td>
    </tr>
    <tr>
      <th>max</th>
      <td>1006.000000</td>
      <td>72000.000000</td>
      <td>3.000000</td>
      <td>2023-01-13 00:00:00</td>
      <td>72000.000000</td>
    </tr>
    <tr>
      <th>std</th>
      <td>1.870829</td>
      <td>35060.382438</td>
      <td>0.816497</td>
      <td>NaN</td>
      <td>34178.361820</td>
    </tr>
  </tbody>
</table>
</div>




```python
revenue_by_product = df.groupby("Product")["Revenue"].sum().sort_values(ascending=False)
revenue_by_product

```




    Product
    Laptop      142000
    Monitor      24000
    Mouse         2650
    Keyboard      1500
    Name: Revenue, dtype: int64




```python
revenue_by_product.plot(kind='bar', color='orange', figsize=(8,4))
plt.title("Revenue by Product")
plt.ylabel("Revenue in ₹")
plt.show()

```


    
![png](/pynotes/images/sales_5_0.png)
    



```python
daily_revenue = df.groupby("Date")["Revenue"].sum()
daily_revenue

```




    Date
    2023-01-10    71000
    2023-01-11     1500
    2023-01-12    96000
    2023-01-13     1650
    Name: Revenue, dtype: int64




```python
daily_revenue.plot(marker='o', linestyle='--', color='green')
plt.title("Daily Revenue Trend")
plt.xlabel("Date")
plt.ylabel("Revenue in ₹")
plt.xticks(rotation=45)
plt.tight_layout()
plt.show()

```


    
![png](/pynotes/images/sales_7_0.png)
    



```python
category_revenue = df.groupby("Category")["Revenue"].sum()
category_revenue

```




    Category
    Accessories      4150
    Electronics    166000
    Name: Revenue, dtype: int64




```python
category_revenue.plot.pie(autopct='%1.1f%%', startangle=90, figsize=(5,5))
plt.title("Revenue Share by Category")
plt.ylabel("")
plt.show()

```


    
![png](/pynotes/images/sales_9_0.png)
    



```python
df["Discount"] = [0, 50, 0, 1000, 0, 30]  # Simulate discounts
df["NetRevenue"] = df["Revenue"] - df["Discount"]
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
      <th>OrderID</th>
      <th>Product</th>
      <th>Category</th>
      <th>Price</th>
      <th>Quantity</th>
      <th>Date</th>
      <th>Revenue</th>
      <th>Discount</th>
      <th>NetRevenue</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>1001</td>
      <td>Laptop</td>
      <td>Electronics</td>
      <td>70000</td>
      <td>1</td>
      <td>2023-01-10</td>
      <td>70000</td>
      <td>0</td>
      <td>70000</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1002</td>
      <td>Mouse</td>
      <td>Accessories</td>
      <td>500</td>
      <td>2</td>
      <td>2023-01-10</td>
      <td>1000</td>
      <td>50</td>
      <td>950</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1003</td>
      <td>Keyboard</td>
      <td>Accessories</td>
      <td>1500</td>
      <td>1</td>
      <td>2023-01-11</td>
      <td>1500</td>
      <td>0</td>
      <td>1500</td>
    </tr>
    <tr>
      <th>3</th>
      <td>1004</td>
      <td>Monitor</td>
      <td>Electronics</td>
      <td>12000</td>
      <td>2</td>
      <td>2023-01-12</td>
      <td>24000</td>
      <td>1000</td>
      <td>23000</td>
    </tr>
    <tr>
      <th>4</th>
      <td>1005</td>
      <td>Laptop</td>
      <td>Electronics</td>
      <td>72000</td>
      <td>1</td>
      <td>2023-01-12</td>
      <td>72000</td>
      <td>0</td>
      <td>72000</td>
    </tr>
    <tr>
      <th>5</th>
      <td>1006</td>
      <td>Mouse</td>
      <td>Accessories</td>
      <td>550</td>
      <td>3</td>
      <td>2023-01-13</td>
      <td>1650</td>
      <td>30</td>
      <td>1620</td>
    </tr>
  </tbody>
</table>
</div>




```python
df[["Revenue", "NetRevenue"]].sum()

```




    Revenue       170150
    NetRevenue    169070
    dtype: int64




```python
df.loc[df["Revenue"].idxmax()]

```




    OrderID                      1005
    Product                    Laptop
    Category              Electronics
    Price                       72000
    Quantity                        1
    Date          2023-01-12 00:00:00
    Revenue                     72000
    Discount                        0
    NetRevenue                  72000
    Name: 4, dtype: object




```python
plt.hist(df["Revenue"], bins=5, color="skyblue", edgecolor="black")
plt.title("Revenue Distribution")
plt.xlabel("Revenue")
plt.ylabel("Frequency")
plt.show()

```


    
![png](/pynotes/images/sales_13_0.png)
    



```python
correlation = df[["Price", "Quantity", "Revenue", "Discount", "NetRevenue"]].corr()
sns.heatmap(correlation, annot=True, cmap="YlGnBu")
plt.title("Sales Data Correlation Matrix")
plt.show()

```


    
![png](/pynotes/images/sales_14_0.png)
    



```python
summary = df.groupby("Product")[["Quantity", "Revenue", "Discount", "NetRevenue"]].sum()
summary

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
      <th>Quantity</th>
      <th>Revenue</th>
      <th>Discount</th>
      <th>NetRevenue</th>
    </tr>
    <tr>
      <th>Product</th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Keyboard</th>
      <td>1</td>
      <td>1500</td>
      <td>0</td>
      <td>1500</td>
    </tr>
    <tr>
      <th>Laptop</th>
      <td>2</td>
      <td>142000</td>
      <td>0</td>
      <td>142000</td>
    </tr>
    <tr>
      <th>Monitor</th>
      <td>2</td>
      <td>24000</td>
      <td>1000</td>
      <td>23000</td>
    </tr>
    <tr>
      <th>Mouse</th>
      <td>5</td>
      <td>2650</td>
      <td>80</td>
      <td>2570</td>
    </tr>
  </tbody>
</table>
</div>




```python

```


---
**Score: 15**