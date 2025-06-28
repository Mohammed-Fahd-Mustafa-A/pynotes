---
title: Employee
date: 2025-06-29
author: Your Name
cell_count: 24
score: 20
---

```python
pip install seaborn

```

    Collecting seaborn
      Downloading seaborn-0.13.2-py3-none-any.whl.metadata (5.4 kB)
    Requirement already satisfied: numpy!=1.24.0,>=1.20 in c:\users\hp\miniconda3\envs\py312\lib\site-packages (from seaborn) (2.3.1)
    Requirement already satisfied: pandas>=1.2 in c:\users\hp\miniconda3\envs\py312\lib\site-packages (from seaborn) (2.3.0)
    Requirement already satisfied: matplotlib!=3.6.1,>=3.4 in c:\users\hp\miniconda3\envs\py312\lib\site-packages (from seaborn) (3.10.3)
    Requirement already satisfied: contourpy>=1.0.1 in c:\users\hp\miniconda3\envs\py312\lib\site-packages (from matplotlib!=3.6.1,>=3.4->seaborn) (1.3.2)
    Requirement already satisfied: cycler>=0.10 in c:\users\hp\miniconda3\envs\py312\lib\site-packages (from matplotlib!=3.6.1,>=3.4->seaborn) (0.12.1)
    Requirement already satisfied: fonttools>=4.22.0 in c:\users\hp\miniconda3\envs\py312\lib\site-packages (from matplotlib!=3.6.1,>=3.4->seaborn) (4.58.4)
    Requirement already satisfied: kiwisolver>=1.3.1 in c:\users\hp\miniconda3\envs\py312\lib\site-packages (from matplotlib!=3.6.1,>=3.4->seaborn) (1.4.8)
    Requirement already satisfied: packaging>=20.0 in c:\users\hp\miniconda3\envs\py312\lib\site-packages (from matplotlib!=3.6.1,>=3.4->seaborn) (24.2)
    Requirement already satisfied: pillow>=8 in c:\users\hp\miniconda3\envs\py312\lib\site-packages (from matplotlib!=3.6.1,>=3.4->seaborn) (11.2.1)
    Requirement already satisfied: pyparsing>=2.3.1 in c:\users\hp\miniconda3\envs\py312\lib\site-packages (from matplotlib!=3.6.1,>=3.4->seaborn) (3.2.3)
    Requirement already satisfied: python-dateutil>=2.7 in c:\users\hp\miniconda3\envs\py312\lib\site-packages (from matplotlib!=3.6.1,>=3.4->seaborn) (2.9.0.post0)
    Requirement already satisfied: pytz>=2020.1 in c:\users\hp\miniconda3\envs\py312\lib\site-packages (from pandas>=1.2->seaborn) (2025.2)
    Requirement already satisfied: tzdata>=2022.7 in c:\users\hp\miniconda3\envs\py312\lib\site-packages (from pandas>=1.2->seaborn) (2025.2)
    Requirement already satisfied: six>=1.5 in c:\users\hp\miniconda3\envs\py312\lib\site-packages (from python-dateutil>=2.7->matplotlib!=3.6.1,>=3.4->seaborn) (1.17.0)
    Downloading seaborn-0.13.2-py3-none-any.whl (294 kB)
    Installing collected packages: seaborn
    Successfully installed seaborn-0.13.2
    Note: you may need to restart the kernel to use updated packages.
    


```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

# Enable inline plotting
%matplotlib inline

```


```python
data = {
    "Name": ["Alice", "Bob", "Charlie", "David", "Eva", "Frank", "Grace", "Henry"],
    "Age": [25, 30, np.nan, 45, 28, 33, 38, np.nan],
    "Salary": [50000, 60000, 55000, 65000, np.nan, 70000, 62000, 58000],
    "Department": ["HR", "Finance", "IT", "Finance", "HR", "IT", "IT", "HR"]
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
      <th>Name</th>
      <th>Age</th>
      <th>Salary</th>
      <th>Department</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Alice</td>
      <td>25.0</td>
      <td>50000.0</td>
      <td>HR</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Bob</td>
      <td>30.0</td>
      <td>60000.0</td>
      <td>Finance</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Charlie</td>
      <td>NaN</td>
      <td>55000.0</td>
      <td>IT</td>
    </tr>
    <tr>
      <th>3</th>
      <td>David</td>
      <td>45.0</td>
      <td>65000.0</td>
      <td>Finance</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Eva</td>
      <td>28.0</td>
      <td>NaN</td>
      <td>HR</td>
    </tr>
    <tr>
      <th>5</th>
      <td>Frank</td>
      <td>33.0</td>
      <td>70000.0</td>
      <td>IT</td>
    </tr>
    <tr>
      <th>6</th>
      <td>Grace</td>
      <td>38.0</td>
      <td>62000.0</td>
      <td>IT</td>
    </tr>
    <tr>
      <th>7</th>
      <td>Henry</td>
      <td>NaN</td>
      <td>58000.0</td>
      <td>HR</td>
    </tr>
  </tbody>
</table>
</div>




```python
df.info()

```

    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 8 entries, 0 to 7
    Data columns (total 4 columns):
     #   Column      Non-Null Count  Dtype  
    ---  ------      --------------  -----  
     0   Name        8 non-null      object 
     1   Age         6 non-null      float64
     2   Salary      7 non-null      float64
     3   Department  8 non-null      object 
    dtypes: float64(2), object(2)
    memory usage: 388.0+ bytes
    


```python
df.isnull().sum()

```




    Name          0
    Age           2
    Salary        1
    Department    0
    dtype: int64




```python
df['Age'] = df['Age'].fillna(df['Age'].median())
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
      <th>Name</th>
      <th>Age</th>
      <th>Salary</th>
      <th>Department</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Alice</td>
      <td>25.0</td>
      <td>50000.0</td>
      <td>HR</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Bob</td>
      <td>30.0</td>
      <td>60000.0</td>
      <td>Finance</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Charlie</td>
      <td>31.5</td>
      <td>55000.0</td>
      <td>IT</td>
    </tr>
    <tr>
      <th>3</th>
      <td>David</td>
      <td>45.0</td>
      <td>65000.0</td>
      <td>Finance</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Eva</td>
      <td>28.0</td>
      <td>NaN</td>
      <td>HR</td>
    </tr>
    <tr>
      <th>5</th>
      <td>Frank</td>
      <td>33.0</td>
      <td>70000.0</td>
      <td>IT</td>
    </tr>
    <tr>
      <th>6</th>
      <td>Grace</td>
      <td>38.0</td>
      <td>62000.0</td>
      <td>IT</td>
    </tr>
    <tr>
      <th>7</th>
      <td>Henry</td>
      <td>31.5</td>
      <td>58000.0</td>
      <td>HR</td>
    </tr>
  </tbody>
</table>
</div>




```python
df['Salary'] = df['Salary'].fillna(df['Salary'].mean())
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
      <th>Name</th>
      <th>Age</th>
      <th>Salary</th>
      <th>Department</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Alice</td>
      <td>25.0</td>
      <td>50000.0</td>
      <td>HR</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Bob</td>
      <td>30.0</td>
      <td>60000.0</td>
      <td>Finance</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Charlie</td>
      <td>31.5</td>
      <td>55000.0</td>
      <td>IT</td>
    </tr>
    <tr>
      <th>3</th>
      <td>David</td>
      <td>45.0</td>
      <td>65000.0</td>
      <td>Finance</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Eva</td>
      <td>28.0</td>
      <td>60000.0</td>
      <td>HR</td>
    </tr>
    <tr>
      <th>5</th>
      <td>Frank</td>
      <td>33.0</td>
      <td>70000.0</td>
      <td>IT</td>
    </tr>
    <tr>
      <th>6</th>
      <td>Grace</td>
      <td>38.0</td>
      <td>62000.0</td>
      <td>IT</td>
    </tr>
    <tr>
      <th>7</th>
      <td>Henry</td>
      <td>31.5</td>
      <td>58000.0</td>
      <td>HR</td>
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
      <th>Age</th>
      <th>Salary</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>count</th>
      <td>8.00000</td>
      <td>8.000000</td>
    </tr>
    <tr>
      <th>mean</th>
      <td>32.75000</td>
      <td>60000.000000</td>
    </tr>
    <tr>
      <th>std</th>
      <td>6.22208</td>
      <td>6071.008389</td>
    </tr>
    <tr>
      <th>min</th>
      <td>25.00000</td>
      <td>50000.000000</td>
    </tr>
    <tr>
      <th>25%</th>
      <td>29.50000</td>
      <td>57250.000000</td>
    </tr>
    <tr>
      <th>50%</th>
      <td>31.50000</td>
      <td>60000.000000</td>
    </tr>
    <tr>
      <th>75%</th>
      <td>34.25000</td>
      <td>62750.000000</td>
    </tr>
    <tr>
      <th>max</th>
      <td>45.00000</td>
      <td>70000.000000</td>
    </tr>
  </tbody>
</table>
</div>




```python
sns.histplot(df['Age'], kde=True, bins=5, color='skyblue')
plt.title("Age Distribution")
plt.xlabel("Age")
plt.ylabel("Count")
plt.show()

```


    
![png](/pynotes/images/employee_8_0.png)
    



```python
sns.countplot(x="Department", data=df, palette="viridis")
plt.title("Department Count")
plt.show()

```

    C:\Users\HP\AppData\Local\Temp\ipykernel_1960\1748937494.py:1: FutureWarning: 
    
    Passing `palette` without assigning `hue` is deprecated and will be removed in v0.14.0. Assign the `x` variable to `hue` and set `legend=False` for the same effect.
    
      sns.countplot(x="Department", data=df, palette="viridis")
    


    
![png](/pynotes/images/employee_9_1.png)
    



```python
sns.boxplot(x="Department", y="Salary", data=df)
plt.title("Salary Distribution by Department")
plt.show()

```


    
![png](/pynotes/images/employee_10_0.png)
    



```python
df['Experience'] = [2, 5, 3, 10, 4, 8, 6, 7]
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
      <th>Name</th>
      <th>Age</th>
      <th>Salary</th>
      <th>Department</th>
      <th>Experience</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Alice</td>
      <td>25.0</td>
      <td>50000.0</td>
      <td>HR</td>
      <td>2</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Bob</td>
      <td>30.0</td>
      <td>60000.0</td>
      <td>Finance</td>
      <td>5</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Charlie</td>
      <td>31.5</td>
      <td>55000.0</td>
      <td>IT</td>
      <td>3</td>
    </tr>
    <tr>
      <th>3</th>
      <td>David</td>
      <td>45.0</td>
      <td>65000.0</td>
      <td>Finance</td>
      <td>10</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Eva</td>
      <td>28.0</td>
      <td>60000.0</td>
      <td>HR</td>
      <td>4</td>
    </tr>
    <tr>
      <th>5</th>
      <td>Frank</td>
      <td>33.0</td>
      <td>70000.0</td>
      <td>IT</td>
      <td>8</td>
    </tr>
    <tr>
      <th>6</th>
      <td>Grace</td>
      <td>38.0</td>
      <td>62000.0</td>
      <td>IT</td>
      <td>6</td>
    </tr>
    <tr>
      <th>7</th>
      <td>Henry</td>
      <td>31.5</td>
      <td>58000.0</td>
      <td>HR</td>
      <td>7</td>
    </tr>
  </tbody>
</table>
</div>




```python
df.corr(numeric_only=True)

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
      <th>Age</th>
      <th>Salary</th>
      <th>Experience</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Age</th>
      <td>1.000000</td>
      <td>0.606989</td>
      <td>0.819292</td>
    </tr>
    <tr>
      <th>Salary</th>
      <td>0.606989</td>
      <td>1.000000</td>
      <td>0.819845</td>
    </tr>
    <tr>
      <th>Experience</th>
      <td>0.819292</td>
      <td>0.819845</td>
      <td>1.000000</td>
    </tr>
  </tbody>
</table>
</div>




```python
df.corr(numeric_only=True)

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
      <th>Age</th>
      <th>Salary</th>
      <th>Experience</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>Age</th>
      <td>1.000000</td>
      <td>0.606989</td>
      <td>0.819292</td>
    </tr>
    <tr>
      <th>Salary</th>
      <td>0.606989</td>
      <td>1.000000</td>
      <td>0.819845</td>
    </tr>
    <tr>
      <th>Experience</th>
      <td>0.819292</td>
      <td>0.819845</td>
      <td>1.000000</td>
    </tr>
  </tbody>
</table>
</div>




```python
sns.heatmap(df.corr(numeric_only=True), annot=True, cmap='coolwarm')
plt.title("Correlation Heatmap")
plt.show()

```


    
![png](/pynotes/images/employee_14_0.png)
    



```python
df[df['Salary'] > 60000]

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
      <th>Name</th>
      <th>Age</th>
      <th>Salary</th>
      <th>Department</th>
      <th>Experience</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>3</th>
      <td>David</td>
      <td>45.0</td>
      <td>65000.0</td>
      <td>Finance</td>
      <td>10</td>
    </tr>
    <tr>
      <th>5</th>
      <td>Frank</td>
      <td>33.0</td>
      <td>70000.0</td>
      <td>IT</td>
      <td>8</td>
    </tr>
    <tr>
      <th>6</th>
      <td>Grace</td>
      <td>38.0</td>
      <td>62000.0</td>
      <td>IT</td>
      <td>6</td>
    </tr>
  </tbody>
</table>
</div>




```python
df.groupby('Department')['Salary'].mean()

```




    Department
    Finance    62500.000000
    HR         56000.000000
    IT         62333.333333
    Name: Salary, dtype: float64




```python
plt.scatter(df['Age'], df['Salary'], color='green')
plt.xlabel('Age')
plt.ylabel('Salary')
plt.title('Age vs Salary')
plt.grid(True)
plt.show()

```


    
![png](/pynotes/images/employee_17_0.png)
    



```python
df['Department'].value_counts().plot.pie(autopct='%1.1f%%', startangle=90)
plt.title('Department Distribution')
plt.ylabel('')
plt.show()

```


    
![png](/pynotes/images/employee_18_0.png)
    



```python
sns.lineplot(x='Experience', y='Salary', data=df, marker='o')
plt.title("Salary vs Experience")
plt.show()

```


    
![png](/pynotes/images/employee_19_0.png)
    



```python
df['Bonus'] = df['Salary'] * 0.1
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
      <th>Name</th>
      <th>Age</th>
      <th>Salary</th>
      <th>Department</th>
      <th>Experience</th>
      <th>Bonus</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Alice</td>
      <td>25.0</td>
      <td>50000.0</td>
      <td>HR</td>
      <td>2</td>
      <td>5000.0</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Bob</td>
      <td>30.0</td>
      <td>60000.0</td>
      <td>Finance</td>
      <td>5</td>
      <td>6000.0</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Charlie</td>
      <td>31.5</td>
      <td>55000.0</td>
      <td>IT</td>
      <td>3</td>
      <td>5500.0</td>
    </tr>
    <tr>
      <th>3</th>
      <td>David</td>
      <td>45.0</td>
      <td>65000.0</td>
      <td>Finance</td>
      <td>10</td>
      <td>6500.0</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Eva</td>
      <td>28.0</td>
      <td>60000.0</td>
      <td>HR</td>
      <td>4</td>
      <td>6000.0</td>
    </tr>
    <tr>
      <th>5</th>
      <td>Frank</td>
      <td>33.0</td>
      <td>70000.0</td>
      <td>IT</td>
      <td>8</td>
      <td>7000.0</td>
    </tr>
    <tr>
      <th>6</th>
      <td>Grace</td>
      <td>38.0</td>
      <td>62000.0</td>
      <td>IT</td>
      <td>6</td>
      <td>6200.0</td>
    </tr>
    <tr>
      <th>7</th>
      <td>Henry</td>
      <td>31.5</td>
      <td>58000.0</td>
      <td>HR</td>
      <td>7</td>
      <td>5800.0</td>
    </tr>
  </tbody>
</table>
</div>




```python
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
      <th>Name</th>
      <th>Age</th>
      <th>Salary</th>
      <th>Department</th>
      <th>Experience</th>
      <th>Bonus</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Alice</td>
      <td>25.0</td>
      <td>50000.0</td>
      <td>HR</td>
      <td>2</td>
      <td>5000.0</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Bob</td>
      <td>30.0</td>
      <td>60000.0</td>
      <td>Finance</td>
      <td>5</td>
      <td>6000.0</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Charlie</td>
      <td>31.5</td>
      <td>55000.0</td>
      <td>IT</td>
      <td>3</td>
      <td>5500.0</td>
    </tr>
    <tr>
      <th>3</th>
      <td>David</td>
      <td>45.0</td>
      <td>65000.0</td>
      <td>Finance</td>
      <td>10</td>
      <td>6500.0</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Eva</td>
      <td>28.0</td>
      <td>60000.0</td>
      <td>HR</td>
      <td>4</td>
      <td>6000.0</td>
    </tr>
  </tbody>
</table>
</div>




```python
df.to_csv("cleaned_employee_data.csv", index=False)
print("Saved to cleaned_employee_data.csv")

```

    Saved to cleaned_employee_data.csv
    


```python

```


---
**Score: 20**