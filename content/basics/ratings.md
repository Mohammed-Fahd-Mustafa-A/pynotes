---
title: Ratings
date: 2025-06-28
author: Your Name
cell_count: 17
score: 15
---

```python
# 1. Import required libraries
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt

```


```python
# 2. Create a sample movie dataset
data = {
    "title": ["Inception", "Titanic", "Avengers", "Shrek", "Up", "Coco", "Joker", "Frozen", "Toy Story", "Tenet"],
    "genre": ["Sci-Fi", "Romance", "Action", "Animation", "Animation", "Animation", "Drama", "Animation", "Animation", "Sci-Fi"],
    "year": [2010, 1997, 2012, 2001, 2009, 2017, 2019, 2013, 1995, 2020],
    "rating": [8.8, 7.8, 8.1, 7.9, 8.3, 8.4, 8.5, 7.5, 8.3, 7.4],
    "votes": [2000000, 1100000, 1800000, 600000, 800000, 500000, 1000000, 700000, 900000, 400000]
}

```


```python
# 3. Convert to DataFrame
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
      <th>title</th>
      <th>genre</th>
      <th>year</th>
      <th>rating</th>
      <th>votes</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Inception</td>
      <td>Sci-Fi</td>
      <td>2010</td>
      <td>8.8</td>
      <td>2000000</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Titanic</td>
      <td>Romance</td>
      <td>1997</td>
      <td>7.8</td>
      <td>1100000</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Avengers</td>
      <td>Action</td>
      <td>2012</td>
      <td>8.1</td>
      <td>1800000</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Shrek</td>
      <td>Animation</td>
      <td>2001</td>
      <td>7.9</td>
      <td>600000</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Up</td>
      <td>Animation</td>
      <td>2009</td>
      <td>8.3</td>
      <td>800000</td>
    </tr>
    <tr>
      <th>5</th>
      <td>Coco</td>
      <td>Animation</td>
      <td>2017</td>
      <td>8.4</td>
      <td>500000</td>
    </tr>
    <tr>
      <th>6</th>
      <td>Joker</td>
      <td>Drama</td>
      <td>2019</td>
      <td>8.5</td>
      <td>1000000</td>
    </tr>
    <tr>
      <th>7</th>
      <td>Frozen</td>
      <td>Animation</td>
      <td>2013</td>
      <td>7.5</td>
      <td>700000</td>
    </tr>
    <tr>
      <th>8</th>
      <td>Toy Story</td>
      <td>Animation</td>
      <td>1995</td>
      <td>8.3</td>
      <td>900000</td>
    </tr>
    <tr>
      <th>9</th>
      <td>Tenet</td>
      <td>Sci-Fi</td>
      <td>2020</td>
      <td>7.4</td>
      <td>400000</td>
    </tr>
  </tbody>
</table>
</div>




```python
# 4. Check data types and info
df.info()

```

    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 10 entries, 0 to 9
    Data columns (total 5 columns):
     #   Column  Non-Null Count  Dtype  
    ---  ------  --------------  -----  
     0   title   10 non-null     object 
     1   genre   10 non-null     object 
     2   year    10 non-null     int64  
     3   rating  10 non-null     float64
     4   votes   10 non-null     int64  
    dtypes: float64(1), int64(2), object(2)
    memory usage: 532.0+ bytes
    


```python
# 5. Basic statistics
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
      <th>year</th>
      <th>rating</th>
      <th>votes</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>count</th>
      <td>10.00000</td>
      <td>10.000000</td>
      <td>1.000000e+01</td>
    </tr>
    <tr>
      <th>mean</th>
      <td>2009.30000</td>
      <td>8.100000</td>
      <td>9.800000e+05</td>
    </tr>
    <tr>
      <th>std</th>
      <td>8.90755</td>
      <td>0.447214</td>
      <td>5.329165e+05</td>
    </tr>
    <tr>
      <th>min</th>
      <td>1995.00000</td>
      <td>7.400000</td>
      <td>4.000000e+05</td>
    </tr>
    <tr>
      <th>25%</th>
      <td>2003.00000</td>
      <td>7.825000</td>
      <td>6.250000e+05</td>
    </tr>
    <tr>
      <th>50%</th>
      <td>2011.00000</td>
      <td>8.200000</td>
      <td>8.500000e+05</td>
    </tr>
    <tr>
      <th>75%</th>
      <td>2016.00000</td>
      <td>8.375000</td>
      <td>1.075000e+06</td>
    </tr>
    <tr>
      <th>max</th>
      <td>2020.00000</td>
      <td>8.800000</td>
      <td>2.000000e+06</td>
    </tr>
  </tbody>
</table>
</div>




```python
# 6. Add a column for rating category
def rate_group(r):
    if r >= 8.5:
        return "Excellent"
    elif r >= 8.0:
        return "Good"
    elif r >= 7.5:
        return "Average"
    else:
        return "Below Average"

df["rating_group"] = df["rating"].apply(rate_group)

```


```python
# 7. Count of each rating group
df["rating_group"].value_counts()

```




    rating_group
    Good             4
    Average          3
    Excellent        2
    Below Average    1
    Name: count, dtype: int64




```python
# 8. Count of each genre
df["genre"].value_counts()

```




    genre
    Animation    5
    Sci-Fi       2
    Romance      1
    Action       1
    Drama        1
    Name: count, dtype: int64




```python
# 9. Top rated movie
df[df["rating"] == df["rating"].max()]

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
      <th>title</th>
      <th>genre</th>
      <th>year</th>
      <th>rating</th>
      <th>votes</th>
      <th>rating_group</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Inception</td>
      <td>Sci-Fi</td>
      <td>2010</td>
      <td>8.8</td>
      <td>2000000</td>
      <td>Excellent</td>
    </tr>
  </tbody>
</table>
</div>




```python
# 10. Lowest rated movie
df[df["rating"] == df["rating"].min()]

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
      <th>title</th>
      <th>genre</th>
      <th>year</th>
      <th>rating</th>
      <th>votes</th>
      <th>rating_group</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>9</th>
      <td>Tenet</td>
      <td>Sci-Fi</td>
      <td>2020</td>
      <td>7.4</td>
      <td>400000</td>
      <td>Below Average</td>
    </tr>
  </tbody>
</table>
</div>




```python
# 11. Filter animation movies
df[df["genre"] == "Animation"]

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
      <th>title</th>
      <th>genre</th>
      <th>year</th>
      <th>rating</th>
      <th>votes</th>
      <th>rating_group</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>3</th>
      <td>Shrek</td>
      <td>Animation</td>
      <td>2001</td>
      <td>7.9</td>
      <td>600000</td>
      <td>Average</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Up</td>
      <td>Animation</td>
      <td>2009</td>
      <td>8.3</td>
      <td>800000</td>
      <td>Good</td>
    </tr>
    <tr>
      <th>5</th>
      <td>Coco</td>
      <td>Animation</td>
      <td>2017</td>
      <td>8.4</td>
      <td>500000</td>
      <td>Good</td>
    </tr>
    <tr>
      <th>7</th>
      <td>Frozen</td>
      <td>Animation</td>
      <td>2013</td>
      <td>7.5</td>
      <td>700000</td>
      <td>Average</td>
    </tr>
    <tr>
      <th>8</th>
      <td>Toy Story</td>
      <td>Animation</td>
      <td>1995</td>
      <td>8.3</td>
      <td>900000</td>
      <td>Good</td>
    </tr>
  </tbody>
</table>
</div>




```python
# 12. Movies released after 2010
df[df["year"] > 2010]

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
      <th>title</th>
      <th>genre</th>
      <th>year</th>
      <th>rating</th>
      <th>votes</th>
      <th>rating_group</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>2</th>
      <td>Avengers</td>
      <td>Action</td>
      <td>2012</td>
      <td>8.1</td>
      <td>1800000</td>
      <td>Good</td>
    </tr>
    <tr>
      <th>5</th>
      <td>Coco</td>
      <td>Animation</td>
      <td>2017</td>
      <td>8.4</td>
      <td>500000</td>
      <td>Good</td>
    </tr>
    <tr>
      <th>6</th>
      <td>Joker</td>
      <td>Drama</td>
      <td>2019</td>
      <td>8.5</td>
      <td>1000000</td>
      <td>Excellent</td>
    </tr>
    <tr>
      <th>7</th>
      <td>Frozen</td>
      <td>Animation</td>
      <td>2013</td>
      <td>7.5</td>
      <td>700000</td>
      <td>Average</td>
    </tr>
    <tr>
      <th>9</th>
      <td>Tenet</td>
      <td>Sci-Fi</td>
      <td>2020</td>
      <td>7.4</td>
      <td>400000</td>
      <td>Below Average</td>
    </tr>
  </tbody>
</table>
</div>




```python
# 13. Group by genre and average rating
df.groupby("genre")["rating"].mean()

```




    genre
    Action       8.10
    Animation    8.08
    Drama        8.50
    Romance      7.80
    Sci-Fi       8.10
    Name: rating, dtype: float64




```python
# 14. Visualization: Rating Distribution
plt.figure(figsize=(8, 4))
plt.hist(df["rating"], bins=5, color="skyblue", edgecolor="black")
plt.title("Rating Distribution")
plt.xlabel("Rating")
plt.ylabel("Number of Movies")
plt.grid(True)
plt.show()

```


    
![png](/pynotes/images/ratings_13_0.png)
    



```python
# 15. Bar chart: Votes per movie
plt.figure(figsize=(10, 5))
plt.bar(df["title"], df["votes"], color="orange")
plt.xticks(rotation=45)
plt.title("Votes per Movie")
plt.ylabel("Number of Votes")
plt.tight_layout()
plt.show()

```


    
![png](/pynotes/images/ratings_14_0.png)
    



```python
# 16. Scatter plot: Ratings vs Votes
plt.figure(figsize=(8, 5))
plt.scatter(df["rating"], df["votes"], color="green")
plt.title("Ratings vs Votes")
plt.xlabel("Rating")
plt.ylabel("Votes")
plt.grid(True)
plt.show()

```


    
![png](/pynotes/images/ratings_15_0.png)
    



```python

```


---
**Score: 15**