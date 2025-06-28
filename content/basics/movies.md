---
title: Movies
date: 2025-06-29
author: Your Name
cell_count: 9
score: 5
---

```python
import matplotlib.pyplot as plt
movies = [
    {"title": "Inception", "rating": 8.8},
    {"title": "Interstellar", "rating": 8.6},
    {"title": "The Dark Knight", "rating": 9.0},
    {"title": "Tenet", "rating": 7.5},
    {"title": "Dunkirk", "rating": 7.9}
]

```


```python
# Create DataFrame
import pandas as pd
df = pd.DataFrame(movies)
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
      <th>rating</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Inception</td>
      <td>8.8</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Interstellar</td>
      <td>8.6</td>
    </tr>
    <tr>
      <th>2</th>
      <td>The Dark Knight</td>
      <td>9.0</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Tenet</td>
      <td>7.5</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Dunkirk</td>
      <td>7.9</td>
    </tr>
  </tbody>
</table>
</div>




```python
# Average rating
df["rating"].mean()

```




    np.float64(8.36)




```python
# Bar plot
df.plot.bar(x="title", y="rating", legend=False, color="purple")
plt.title("Movie Ratings")
plt.ylim(0, 10)
plt.show()

```


    
![png](/pynotes/images/movies_3_0.png)
    



```python
# High rated
df[df["rating"] >= 8.5]

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
      <th>rating</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Inception</td>
      <td>8.8</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Interstellar</td>
      <td>8.6</td>
    </tr>
    <tr>
      <th>2</th>
      <td>The Dark Knight</td>
      <td>9.0</td>
    </tr>
  </tbody>
</table>
</div>




```python
# Sort by rating
df.sort_values(by="rating", ascending=False)

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
      <th>rating</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>2</th>
      <td>The Dark Knight</td>
      <td>9.0</td>
    </tr>
    <tr>
      <th>0</th>
      <td>Inception</td>
      <td>8.8</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Interstellar</td>
      <td>8.6</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Dunkirk</td>
      <td>7.9</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Tenet</td>
      <td>7.5</td>
    </tr>
  </tbody>
</table>
</div>




```python
# Add genre
df["genre"] = ["Sci-Fi", "Sci-Fi", "Action", "Thriller", "War"]
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
      <th>rating</th>
      <th>genre</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Inception</td>
      <td>8.8</td>
      <td>Sci-Fi</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Interstellar</td>
      <td>8.6</td>
      <td>Sci-Fi</td>
    </tr>
    <tr>
      <th>2</th>
      <td>The Dark Knight</td>
      <td>9.0</td>
      <td>Action</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Tenet</td>
      <td>7.5</td>
      <td>Thriller</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Dunkirk</td>
      <td>7.9</td>
      <td>War</td>
    </tr>
  </tbody>
</table>
</div>




```python

```


```python

```


---
**Score: 5**