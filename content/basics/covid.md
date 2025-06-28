---
title: Covid
date: 2025-06-28
author: Your Name
cell_count: 19
score: 15
---

```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

sns.set(style="darkgrid")

```


```python
data = {
    'Country': ['USA', 'India', 'Brazil', 'Russia', 'UK', 'France', 'Spain', 'Italy'],
    'TotalCases': [34000000, 31000000, 19000000, 7000000, 5000000, 5800000, 3700000, 4200000],
    'TotalDeaths': [610000, 410000, 530000, 190000, 130000, 110000, 81000, 127000],
    'TotalRecovered': [28000000, 30000000, 17000000, 6500000, 4800000, 5000000, 3500000, 3900000],
    'Population': [331000000, 1380000000, 213000000, 146000000, 68000000, 67000000, 47000000, 60000000]
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
      <th>TotalCases</th>
      <th>TotalDeaths</th>
      <th>TotalRecovered</th>
      <th>Population</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>USA</td>
      <td>34000000</td>
      <td>610000</td>
      <td>28000000</td>
      <td>331000000</td>
    </tr>
    <tr>
      <th>1</th>
      <td>India</td>
      <td>31000000</td>
      <td>410000</td>
      <td>30000000</td>
      <td>1380000000</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Brazil</td>
      <td>19000000</td>
      <td>530000</td>
      <td>17000000</td>
      <td>213000000</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Russia</td>
      <td>7000000</td>
      <td>190000</td>
      <td>6500000</td>
      <td>146000000</td>
    </tr>
    <tr>
      <th>4</th>
      <td>UK</td>
      <td>5000000</td>
      <td>130000</td>
      <td>4800000</td>
      <td>68000000</td>
    </tr>
    <tr>
      <th>5</th>
      <td>France</td>
      <td>5800000</td>
      <td>110000</td>
      <td>5000000</td>
      <td>67000000</td>
    </tr>
    <tr>
      <th>6</th>
      <td>Spain</td>
      <td>3700000</td>
      <td>81000</td>
      <td>3500000</td>
      <td>47000000</td>
    </tr>
    <tr>
      <th>7</th>
      <td>Italy</td>
      <td>4200000</td>
      <td>127000</td>
      <td>3900000</td>
      <td>60000000</td>
    </tr>
  </tbody>
</table>
</div>




```python
df.isnull().sum()

```




    Country           0
    TotalCases        0
    TotalDeaths       0
    TotalRecovered    0
    Population        0
    dtype: int64




```python
df['ActiveCases'] = df['TotalCases'] - df['TotalRecovered'] - df['TotalDeaths']
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
      <th>TotalCases</th>
      <th>TotalDeaths</th>
      <th>TotalRecovered</th>
      <th>Population</th>
      <th>ActiveCases</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>USA</td>
      <td>34000000</td>
      <td>610000</td>
      <td>28000000</td>
      <td>331000000</td>
      <td>5390000</td>
    </tr>
    <tr>
      <th>1</th>
      <td>India</td>
      <td>31000000</td>
      <td>410000</td>
      <td>30000000</td>
      <td>1380000000</td>
      <td>590000</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Brazil</td>
      <td>19000000</td>
      <td>530000</td>
      <td>17000000</td>
      <td>213000000</td>
      <td>1470000</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Russia</td>
      <td>7000000</td>
      <td>190000</td>
      <td>6500000</td>
      <td>146000000</td>
      <td>310000</td>
    </tr>
    <tr>
      <th>4</th>
      <td>UK</td>
      <td>5000000</td>
      <td>130000</td>
      <td>4800000</td>
      <td>68000000</td>
      <td>70000</td>
    </tr>
    <tr>
      <th>5</th>
      <td>France</td>
      <td>5800000</td>
      <td>110000</td>
      <td>5000000</td>
      <td>67000000</td>
      <td>690000</td>
    </tr>
    <tr>
      <th>6</th>
      <td>Spain</td>
      <td>3700000</td>
      <td>81000</td>
      <td>3500000</td>
      <td>47000000</td>
      <td>119000</td>
    </tr>
    <tr>
      <th>7</th>
      <td>Italy</td>
      <td>4200000</td>
      <td>127000</td>
      <td>3900000</td>
      <td>60000000</td>
      <td>173000</td>
    </tr>
  </tbody>
</table>
</div>




```python
df['MortalityRate'] = (df['TotalDeaths'] / df['TotalCases']) * 100
df['MortalityRate'] = df['MortalityRate'].round(2)
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
      <th>TotalCases</th>
      <th>TotalDeaths</th>
      <th>TotalRecovered</th>
      <th>Population</th>
      <th>ActiveCases</th>
      <th>MortalityRate</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>USA</td>
      <td>34000000</td>
      <td>610000</td>
      <td>28000000</td>
      <td>331000000</td>
      <td>5390000</td>
      <td>1.79</td>
    </tr>
    <tr>
      <th>1</th>
      <td>India</td>
      <td>31000000</td>
      <td>410000</td>
      <td>30000000</td>
      <td>1380000000</td>
      <td>590000</td>
      <td>1.32</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Brazil</td>
      <td>19000000</td>
      <td>530000</td>
      <td>17000000</td>
      <td>213000000</td>
      <td>1470000</td>
      <td>2.79</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Russia</td>
      <td>7000000</td>
      <td>190000</td>
      <td>6500000</td>
      <td>146000000</td>
      <td>310000</td>
      <td>2.71</td>
    </tr>
    <tr>
      <th>4</th>
      <td>UK</td>
      <td>5000000</td>
      <td>130000</td>
      <td>4800000</td>
      <td>68000000</td>
      <td>70000</td>
      <td>2.60</td>
    </tr>
    <tr>
      <th>5</th>
      <td>France</td>
      <td>5800000</td>
      <td>110000</td>
      <td>5000000</td>
      <td>67000000</td>
      <td>690000</td>
      <td>1.90</td>
    </tr>
    <tr>
      <th>6</th>
      <td>Spain</td>
      <td>3700000</td>
      <td>81000</td>
      <td>3500000</td>
      <td>47000000</td>
      <td>119000</td>
      <td>2.19</td>
    </tr>
    <tr>
      <th>7</th>
      <td>Italy</td>
      <td>4200000</td>
      <td>127000</td>
      <td>3900000</td>
      <td>60000000</td>
      <td>173000</td>
      <td>3.02</td>
    </tr>
  </tbody>
</table>
</div>




```python
df['RecoveryRate'] = (df['TotalRecovered'] / df['TotalCases']) * 100
df['RecoveryRate'] = df['RecoveryRate'].round(2)
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
      <th>TotalCases</th>
      <th>TotalDeaths</th>
      <th>TotalRecovered</th>
      <th>Population</th>
      <th>ActiveCases</th>
      <th>MortalityRate</th>
      <th>RecoveryRate</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>USA</td>
      <td>34000000</td>
      <td>610000</td>
      <td>28000000</td>
      <td>331000000</td>
      <td>5390000</td>
      <td>1.79</td>
      <td>82.35</td>
    </tr>
    <tr>
      <th>1</th>
      <td>India</td>
      <td>31000000</td>
      <td>410000</td>
      <td>30000000</td>
      <td>1380000000</td>
      <td>590000</td>
      <td>1.32</td>
      <td>96.77</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Brazil</td>
      <td>19000000</td>
      <td>530000</td>
      <td>17000000</td>
      <td>213000000</td>
      <td>1470000</td>
      <td>2.79</td>
      <td>89.47</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Russia</td>
      <td>7000000</td>
      <td>190000</td>
      <td>6500000</td>
      <td>146000000</td>
      <td>310000</td>
      <td>2.71</td>
      <td>92.86</td>
    </tr>
    <tr>
      <th>4</th>
      <td>UK</td>
      <td>5000000</td>
      <td>130000</td>
      <td>4800000</td>
      <td>68000000</td>
      <td>70000</td>
      <td>2.60</td>
      <td>96.00</td>
    </tr>
    <tr>
      <th>5</th>
      <td>France</td>
      <td>5800000</td>
      <td>110000</td>
      <td>5000000</td>
      <td>67000000</td>
      <td>690000</td>
      <td>1.90</td>
      <td>86.21</td>
    </tr>
    <tr>
      <th>6</th>
      <td>Spain</td>
      <td>3700000</td>
      <td>81000</td>
      <td>3500000</td>
      <td>47000000</td>
      <td>119000</td>
      <td>2.19</td>
      <td>94.59</td>
    </tr>
    <tr>
      <th>7</th>
      <td>Italy</td>
      <td>4200000</td>
      <td>127000</td>
      <td>3900000</td>
      <td>60000000</td>
      <td>173000</td>
      <td>3.02</td>
      <td>92.86</td>
    </tr>
  </tbody>
</table>
</div>




```python
df['CasesPer100k'] = (df['TotalCases'] / df['Population']) * 100000
df['CasesPer100k'] = df['CasesPer100k'].round(2)
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
      <th>TotalCases</th>
      <th>TotalDeaths</th>
      <th>TotalRecovered</th>
      <th>Population</th>
      <th>ActiveCases</th>
      <th>MortalityRate</th>
      <th>RecoveryRate</th>
      <th>CasesPer100k</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>USA</td>
      <td>34000000</td>
      <td>610000</td>
      <td>28000000</td>
      <td>331000000</td>
      <td>5390000</td>
      <td>1.79</td>
      <td>82.35</td>
      <td>10271.90</td>
    </tr>
    <tr>
      <th>1</th>
      <td>India</td>
      <td>31000000</td>
      <td>410000</td>
      <td>30000000</td>
      <td>1380000000</td>
      <td>590000</td>
      <td>1.32</td>
      <td>96.77</td>
      <td>2246.38</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Brazil</td>
      <td>19000000</td>
      <td>530000</td>
      <td>17000000</td>
      <td>213000000</td>
      <td>1470000</td>
      <td>2.79</td>
      <td>89.47</td>
      <td>8920.19</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Russia</td>
      <td>7000000</td>
      <td>190000</td>
      <td>6500000</td>
      <td>146000000</td>
      <td>310000</td>
      <td>2.71</td>
      <td>92.86</td>
      <td>4794.52</td>
    </tr>
    <tr>
      <th>4</th>
      <td>UK</td>
      <td>5000000</td>
      <td>130000</td>
      <td>4800000</td>
      <td>68000000</td>
      <td>70000</td>
      <td>2.60</td>
      <td>96.00</td>
      <td>7352.94</td>
    </tr>
    <tr>
      <th>5</th>
      <td>France</td>
      <td>5800000</td>
      <td>110000</td>
      <td>5000000</td>
      <td>67000000</td>
      <td>690000</td>
      <td>1.90</td>
      <td>86.21</td>
      <td>8656.72</td>
    </tr>
    <tr>
      <th>6</th>
      <td>Spain</td>
      <td>3700000</td>
      <td>81000</td>
      <td>3500000</td>
      <td>47000000</td>
      <td>119000</td>
      <td>2.19</td>
      <td>94.59</td>
      <td>7872.34</td>
    </tr>
    <tr>
      <th>7</th>
      <td>Italy</td>
      <td>4200000</td>
      <td>127000</td>
      <td>3900000</td>
      <td>60000000</td>
      <td>173000</td>
      <td>3.02</td>
      <td>92.86</td>
      <td>7000.00</td>
    </tr>
  </tbody>
</table>
</div>




```python
df.sort_values('TotalCases', ascending=False)

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
      <th>TotalCases</th>
      <th>TotalDeaths</th>
      <th>TotalRecovered</th>
      <th>Population</th>
      <th>ActiveCases</th>
      <th>MortalityRate</th>
      <th>RecoveryRate</th>
      <th>CasesPer100k</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>USA</td>
      <td>34000000</td>
      <td>610000</td>
      <td>28000000</td>
      <td>331000000</td>
      <td>5390000</td>
      <td>1.79</td>
      <td>82.35</td>
      <td>10271.90</td>
    </tr>
    <tr>
      <th>1</th>
      <td>India</td>
      <td>31000000</td>
      <td>410000</td>
      <td>30000000</td>
      <td>1380000000</td>
      <td>590000</td>
      <td>1.32</td>
      <td>96.77</td>
      <td>2246.38</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Brazil</td>
      <td>19000000</td>
      <td>530000</td>
      <td>17000000</td>
      <td>213000000</td>
      <td>1470000</td>
      <td>2.79</td>
      <td>89.47</td>
      <td>8920.19</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Russia</td>
      <td>7000000</td>
      <td>190000</td>
      <td>6500000</td>
      <td>146000000</td>
      <td>310000</td>
      <td>2.71</td>
      <td>92.86</td>
      <td>4794.52</td>
    </tr>
    <tr>
      <th>5</th>
      <td>France</td>
      <td>5800000</td>
      <td>110000</td>
      <td>5000000</td>
      <td>67000000</td>
      <td>690000</td>
      <td>1.90</td>
      <td>86.21</td>
      <td>8656.72</td>
    </tr>
    <tr>
      <th>4</th>
      <td>UK</td>
      <td>5000000</td>
      <td>130000</td>
      <td>4800000</td>
      <td>68000000</td>
      <td>70000</td>
      <td>2.60</td>
      <td>96.00</td>
      <td>7352.94</td>
    </tr>
    <tr>
      <th>7</th>
      <td>Italy</td>
      <td>4200000</td>
      <td>127000</td>
      <td>3900000</td>
      <td>60000000</td>
      <td>173000</td>
      <td>3.02</td>
      <td>92.86</td>
      <td>7000.00</td>
    </tr>
    <tr>
      <th>6</th>
      <td>Spain</td>
      <td>3700000</td>
      <td>81000</td>
      <td>3500000</td>
      <td>47000000</td>
      <td>119000</td>
      <td>2.19</td>
      <td>94.59</td>
      <td>7872.34</td>
    </tr>
  </tbody>
</table>
</div>




```python
plt.figure(figsize=(10,5))
sns.barplot(x="Country", y="TotalCases", data=df)
plt.title("Total COVID-19 Cases by Country")
plt.xticks(rotation=45)
plt.show()

```


    
![png](/pynotes/images/covid_8_0.png)
    



```python
plt.figure(figsize=(6,6))
plt.pie(df['TotalDeaths'], labels=df['Country'], autopct='%1.1f%%', startangle=140)
plt.title("Share of Total Deaths")
plt.show()

```


    
![png](/pynotes/images/covid_9_0.png)
    



```python
plt.figure(figsize=(8,6))
sns.scatterplot(x="RecoveryRate", y="MortalityRate", data=df, hue="Country", s=100)
plt.title("Recovery vs Mortality Rate")
plt.show()

```


    
![png](/pynotes/images/covid_10_0.png)
    



```python
correlation = df.corr(numeric_only=True)
correlation

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
      <th>TotalCases</th>
      <th>TotalDeaths</th>
      <th>TotalRecovered</th>
      <th>Population</th>
      <th>ActiveCases</th>
      <th>MortalityRate</th>
      <th>RecoveryRate</th>
      <th>CasesPer100k</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>TotalCases</th>
      <td>1.000000</td>
      <td>0.912920</td>
      <td>0.993700</td>
      <td>0.716484</td>
      <td>0.735629</td>
      <td>-0.630630</td>
      <td>-0.350647</td>
      <td>-0.070176</td>
    </tr>
    <tr>
      <th>TotalDeaths</th>
      <td>0.912920</td>
      <td>1.000000</td>
      <td>0.885787</td>
      <td>0.456123</td>
      <td>0.785250</td>
      <td>-0.319051</td>
      <td>-0.481419</td>
      <td>0.170433</td>
    </tr>
    <tr>
      <th>TotalRecovered</th>
      <td>0.993700</td>
      <td>0.885787</td>
      <td>1.000000</td>
      <td>0.786761</td>
      <td>0.655228</td>
      <td>-0.650646</td>
      <td>-0.258257</td>
      <td>-0.167963</td>
    </tr>
    <tr>
      <th>Population</th>
      <td>0.716484</td>
      <td>0.456123</td>
      <td>0.786761</td>
      <td>1.000000</td>
      <td>0.084207</td>
      <td>-0.702345</td>
      <td>0.279695</td>
      <td>-0.688266</td>
    </tr>
    <tr>
      <th>ActiveCases</th>
      <td>0.735629</td>
      <td>0.785250</td>
      <td>0.655228</td>
      <td>0.084207</td>
      <td>1.000000</td>
      <td>-0.344567</td>
      <td>-0.801032</td>
      <td>0.533024</td>
    </tr>
    <tr>
      <th>MortalityRate</th>
      <td>-0.630630</td>
      <td>-0.319051</td>
      <td>-0.650646</td>
      <td>-0.702345</td>
      <td>-0.344567</td>
      <td>1.000000</td>
      <td>0.153110</td>
      <td>0.228256</td>
    </tr>
    <tr>
      <th>RecoveryRate</th>
      <td>-0.350647</td>
      <td>-0.481419</td>
      <td>-0.258257</td>
      <td>0.279695</td>
      <td>-0.801032</td>
      <td>0.153110</td>
      <td>1.000000</td>
      <td>-0.739556</td>
    </tr>
    <tr>
      <th>CasesPer100k</th>
      <td>-0.070176</td>
      <td>0.170433</td>
      <td>-0.167963</td>
      <td>-0.688266</td>
      <td>0.533024</td>
      <td>0.228256</td>
      <td>-0.739556</td>
      <td>1.000000</td>
    </tr>
  </tbody>
</table>
</div>




```python
plt.figure(figsize=(10,6))
sns.heatmap(correlation, annot=True, cmap="Blues")
plt.title("Feature Correlation Matrix")
plt.show()

```


    
![png](/pynotes/images/covid_12_0.png)
    



```python
df.sort_values('MortalityRate', ascending=False).head(5)

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
      <th>TotalCases</th>
      <th>TotalDeaths</th>
      <th>TotalRecovered</th>
      <th>Population</th>
      <th>ActiveCases</th>
      <th>MortalityRate</th>
      <th>RecoveryRate</th>
      <th>CasesPer100k</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>7</th>
      <td>Italy</td>
      <td>4200000</td>
      <td>127000</td>
      <td>3900000</td>
      <td>60000000</td>
      <td>173000</td>
      <td>3.02</td>
      <td>92.86</td>
      <td>7000.00</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Brazil</td>
      <td>19000000</td>
      <td>530000</td>
      <td>17000000</td>
      <td>213000000</td>
      <td>1470000</td>
      <td>2.79</td>
      <td>89.47</td>
      <td>8920.19</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Russia</td>
      <td>7000000</td>
      <td>190000</td>
      <td>6500000</td>
      <td>146000000</td>
      <td>310000</td>
      <td>2.71</td>
      <td>92.86</td>
      <td>4794.52</td>
    </tr>
    <tr>
      <th>4</th>
      <td>UK</td>
      <td>5000000</td>
      <td>130000</td>
      <td>4800000</td>
      <td>68000000</td>
      <td>70000</td>
      <td>2.60</td>
      <td>96.00</td>
      <td>7352.94</td>
    </tr>
    <tr>
      <th>6</th>
      <td>Spain</td>
      <td>3700000</td>
      <td>81000</td>
      <td>3500000</td>
      <td>47000000</td>
      <td>119000</td>
      <td>2.19</td>
      <td>94.59</td>
      <td>7872.34</td>
    </tr>
  </tbody>
</table>
</div>




```python
totals = df[['TotalCases', 'TotalDeaths', 'TotalRecovered']].sum()
totals

```




    TotalCases        109700000
    TotalDeaths         2188000
    TotalRecovered     98700000
    dtype: int64




```python
global_mortality = (totals['TotalDeaths'] / totals['TotalCases']) * 100
round(global_mortality, 2)

```




    np.float64(1.99)




```python
df['RiskLevel'] = df['MortalityRate'].apply(lambda x: 'High' if x > 2 else 'Moderate')
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
      <th>TotalCases</th>
      <th>TotalDeaths</th>
      <th>TotalRecovered</th>
      <th>Population</th>
      <th>ActiveCases</th>
      <th>MortalityRate</th>
      <th>RecoveryRate</th>
      <th>CasesPer100k</th>
      <th>RiskLevel</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>USA</td>
      <td>34000000</td>
      <td>610000</td>
      <td>28000000</td>
      <td>331000000</td>
      <td>5390000</td>
      <td>1.79</td>
      <td>82.35</td>
      <td>10271.90</td>
      <td>Moderate</td>
    </tr>
    <tr>
      <th>1</th>
      <td>India</td>
      <td>31000000</td>
      <td>410000</td>
      <td>30000000</td>
      <td>1380000000</td>
      <td>590000</td>
      <td>1.32</td>
      <td>96.77</td>
      <td>2246.38</td>
      <td>Moderate</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Brazil</td>
      <td>19000000</td>
      <td>530000</td>
      <td>17000000</td>
      <td>213000000</td>
      <td>1470000</td>
      <td>2.79</td>
      <td>89.47</td>
      <td>8920.19</td>
      <td>High</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Russia</td>
      <td>7000000</td>
      <td>190000</td>
      <td>6500000</td>
      <td>146000000</td>
      <td>310000</td>
      <td>2.71</td>
      <td>92.86</td>
      <td>4794.52</td>
      <td>High</td>
    </tr>
    <tr>
      <th>4</th>
      <td>UK</td>
      <td>5000000</td>
      <td>130000</td>
      <td>4800000</td>
      <td>68000000</td>
      <td>70000</td>
      <td>2.60</td>
      <td>96.00</td>
      <td>7352.94</td>
      <td>High</td>
    </tr>
    <tr>
      <th>5</th>
      <td>France</td>
      <td>5800000</td>
      <td>110000</td>
      <td>5000000</td>
      <td>67000000</td>
      <td>690000</td>
      <td>1.90</td>
      <td>86.21</td>
      <td>8656.72</td>
      <td>Moderate</td>
    </tr>
    <tr>
      <th>6</th>
      <td>Spain</td>
      <td>3700000</td>
      <td>81000</td>
      <td>3500000</td>
      <td>47000000</td>
      <td>119000</td>
      <td>2.19</td>
      <td>94.59</td>
      <td>7872.34</td>
      <td>High</td>
    </tr>
    <tr>
      <th>7</th>
      <td>Italy</td>
      <td>4200000</td>
      <td>127000</td>
      <td>3900000</td>
      <td>60000000</td>
      <td>173000</td>
      <td>3.02</td>
      <td>92.86</td>
      <td>7000.00</td>
      <td>High</td>
    </tr>
  </tbody>
</table>
</div>




```python
sns.countplot(x="RiskLevel", data=df)
plt.title("Country Risk Level Count")
plt.show()

```


    
![png](/pynotes/images/covid_17_0.png)
    



```python

```


---
**Score: 15**