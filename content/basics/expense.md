---
title: Expense
date: 2025-06-30
author: Your Name
cell_count: 13
score: 10
---

```python
# Import libraries
import pandas as pd
import matplotlib.pyplot as plt

```


```python
# Define expense data
data = [
    {"Date": "2025-06-01", "Category": "Food", "Amount": 250},
    {"Date": "2025-06-03", "Category": "Transport", "Amount": 80},
    {"Date": "2025-06-05", "Category": "Rent", "Amount": 5000},
    {"Date": "2025-06-10", "Category": "Food", "Amount": 300},
    {"Date": "2025-06-15", "Category": "Shopping", "Amount": 1200},
    {"Date": "2025-06-20", "Category": "Entertainment", "Amount": 600},
    {"Date": "2025-06-25", "Category": "Food", "Amount": 280},
]

```


```python
# Create DataFrame
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
      <th>Date</th>
      <th>Category</th>
      <th>Amount</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>2025-06-01</td>
      <td>Food</td>
      <td>250</td>
    </tr>
    <tr>
      <th>1</th>
      <td>2025-06-03</td>
      <td>Transport</td>
      <td>80</td>
    </tr>
    <tr>
      <th>2</th>
      <td>2025-06-05</td>
      <td>Rent</td>
      <td>5000</td>
    </tr>
    <tr>
      <th>3</th>
      <td>2025-06-10</td>
      <td>Food</td>
      <td>300</td>
    </tr>
    <tr>
      <th>4</th>
      <td>2025-06-15</td>
      <td>Shopping</td>
      <td>1200</td>
    </tr>
    <tr>
      <th>5</th>
      <td>2025-06-20</td>
      <td>Entertainment</td>
      <td>600</td>
    </tr>
    <tr>
      <th>6</th>
      <td>2025-06-25</td>
      <td>Food</td>
      <td>280</td>
    </tr>
  </tbody>
</table>
</div>




```python
# Total expenses
df["Amount"].sum()

```




    np.int64(7710)




```python
# Total by category
df.groupby("Category")["Amount"].sum()

```




    Category
    Entertainment     600
    Food              830
    Rent             5000
    Shopping         1200
    Transport          80
    Name: Amount, dtype: int64




```python
# Add weekday
df["Date"] = pd.to_datetime(df["Date"])
df["Weekday"] = df["Date"].dt.day_name()
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
      <th>Date</th>
      <th>Category</th>
      <th>Amount</th>
      <th>Weekday</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>2025-06-01</td>
      <td>Food</td>
      <td>250</td>
      <td>Sunday</td>
    </tr>
    <tr>
      <th>1</th>
      <td>2025-06-03</td>
      <td>Transport</td>
      <td>80</td>
      <td>Tuesday</td>
    </tr>
    <tr>
      <th>2</th>
      <td>2025-06-05</td>
      <td>Rent</td>
      <td>5000</td>
      <td>Thursday</td>
    </tr>
    <tr>
      <th>3</th>
      <td>2025-06-10</td>
      <td>Food</td>
      <td>300</td>
      <td>Tuesday</td>
    </tr>
    <tr>
      <th>4</th>
      <td>2025-06-15</td>
      <td>Shopping</td>
      <td>1200</td>
      <td>Sunday</td>
    </tr>
    <tr>
      <th>5</th>
      <td>2025-06-20</td>
      <td>Entertainment</td>
      <td>600</td>
      <td>Friday</td>
    </tr>
    <tr>
      <th>6</th>
      <td>2025-06-25</td>
      <td>Food</td>
      <td>280</td>
      <td>Wednesday</td>
    </tr>
  </tbody>
</table>
</div>




```python
# Expenses by weekday
df.groupby("Weekday")["Amount"].sum().sort_values()

```




    Weekday
    Wednesday     280
    Tuesday       380
    Friday        600
    Sunday       1450
    Thursday     5000
    Name: Amount, dtype: int64




```python
# Pie chart by category
df.groupby("Category")["Amount"].sum().plot.pie(autopct="%1.1f%%", figsize=(6,6))
plt.title("Expense Distribution")
plt.ylabel("")
plt.show()

```


    
![png](/pynotes/images/expense_7_0.png)
    



```python
# Daily trend line
df.groupby("Date")["Amount"].sum().plot(marker="o")
plt.title("Daily Expense Trend")
plt.xticks(rotation=45)
plt.grid(True)
plt.show()

```


    
![png](/pynotes/images/expense_8_0.png)
    



```python
# Highest spending day
df[df["Amount"] == df["Amount"].max()]

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
      <th>Date</th>
      <th>Category</th>
      <th>Amount</th>
      <th>Weekday</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>2</th>
      <td>2025-06-05</td>
      <td>Rent</td>
      <td>5000</td>
      <td>Thursday</td>
    </tr>
  </tbody>
</table>
</div>




```python
# Add comments
df["Comment"] = df["Amount"].apply(lambda x: "Too much!" if x > 1000 else "Okay")
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
      <th>Date</th>
      <th>Category</th>
      <th>Amount</th>
      <th>Weekday</th>
      <th>Comment</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>2025-06-01</td>
      <td>Food</td>
      <td>250</td>
      <td>Sunday</td>
      <td>Okay</td>
    </tr>
    <tr>
      <th>1</th>
      <td>2025-06-03</td>
      <td>Transport</td>
      <td>80</td>
      <td>Tuesday</td>
      <td>Okay</td>
    </tr>
    <tr>
      <th>2</th>
      <td>2025-06-05</td>
      <td>Rent</td>
      <td>5000</td>
      <td>Thursday</td>
      <td>Too much!</td>
    </tr>
    <tr>
      <th>3</th>
      <td>2025-06-10</td>
      <td>Food</td>
      <td>300</td>
      <td>Tuesday</td>
      <td>Okay</td>
    </tr>
    <tr>
      <th>4</th>
      <td>2025-06-15</td>
      <td>Shopping</td>
      <td>1200</td>
      <td>Sunday</td>
      <td>Too much!</td>
    </tr>
    <tr>
      <th>5</th>
      <td>2025-06-20</td>
      <td>Entertainment</td>
      <td>600</td>
      <td>Friday</td>
      <td>Okay</td>
    </tr>
    <tr>
      <th>6</th>
      <td>2025-06-25</td>
      <td>Food</td>
      <td>280</td>
      <td>Wednesday</td>
      <td>Okay</td>
    </tr>
  </tbody>
</table>
</div>




```python
# Save report
df.to_csv("expenses_report.csv", index=False)

```


```python

```


---
**Score: 10**