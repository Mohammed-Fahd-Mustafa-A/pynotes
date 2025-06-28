---
title: Books
date: 2025-06-29
author: Your Name
cell_count: 23
score: 20
---

```python
!pip install requests beautifulsoup4 pandas matplotlib seaborn wordcloud

```

    Requirement already satisfied: requests in c:\users\hp\miniconda3\envs\py312\lib\site-packages (2.32.4)
    Requirement already satisfied: beautifulsoup4 in c:\users\hp\miniconda3\envs\py312\lib\site-packages (4.12.3)
    Requirement already satisfied: pandas in c:\users\hp\miniconda3\envs\py312\lib\site-packages (2.3.0)
    Requirement already satisfied: matplotlib in c:\users\hp\miniconda3\envs\py312\lib\site-packages (3.10.3)
    Requirement already satisfied: seaborn in c:\users\hp\miniconda3\envs\py312\lib\site-packages (0.13.2)
    Collecting wordcloud
      Downloading wordcloud-1.9.4-cp312-cp312-win_amd64.whl.metadata (3.5 kB)
    Requirement already satisfied: charset_normalizer<4,>=2 in c:\users\hp\miniconda3\envs\py312\lib\site-packages (from requests) (3.3.2)
    Requirement already satisfied: idna<4,>=2.5 in c:\users\hp\miniconda3\envs\py312\lib\site-packages (from requests) (3.10)
    Requirement already satisfied: urllib3<3,>=1.21.1 in c:\users\hp\miniconda3\envs\py312\lib\site-packages (from requests) (2.5.0)
    Requirement already satisfied: certifi>=2017.4.17 in c:\users\hp\miniconda3\envs\py312\lib\site-packages (from requests) (2025.6.15)
    Requirement already satisfied: soupsieve>1.2 in c:\users\hp\miniconda3\envs\py312\lib\site-packages (from beautifulsoup4) (2.5)
    Requirement already satisfied: numpy>=1.26.0 in c:\users\hp\miniconda3\envs\py312\lib\site-packages (from pandas) (2.3.1)
    Requirement already satisfied: python-dateutil>=2.8.2 in c:\users\hp\miniconda3\envs\py312\lib\site-packages (from pandas) (2.9.0.post0)
    Requirement already satisfied: pytz>=2020.1 in c:\users\hp\miniconda3\envs\py312\lib\site-packages (from pandas) (2025.2)
    Requirement already satisfied: tzdata>=2022.7 in c:\users\hp\miniconda3\envs\py312\lib\site-packages (from pandas) (2025.2)
    Requirement already satisfied: contourpy>=1.0.1 in c:\users\hp\miniconda3\envs\py312\lib\site-packages (from matplotlib) (1.3.2)
    Requirement already satisfied: cycler>=0.10 in c:\users\hp\miniconda3\envs\py312\lib\site-packages (from matplotlib) (0.12.1)
    Requirement already satisfied: fonttools>=4.22.0 in c:\users\hp\miniconda3\envs\py312\lib\site-packages (from matplotlib) (4.58.4)
    Requirement already satisfied: kiwisolver>=1.3.1 in c:\users\hp\miniconda3\envs\py312\lib\site-packages (from matplotlib) (1.4.8)
    Requirement already satisfied: packaging>=20.0 in c:\users\hp\miniconda3\envs\py312\lib\site-packages (from matplotlib) (24.2)
    Requirement already satisfied: pillow>=8 in c:\users\hp\miniconda3\envs\py312\lib\site-packages (from matplotlib) (11.2.1)
    Requirement already satisfied: pyparsing>=2.3.1 in c:\users\hp\miniconda3\envs\py312\lib\site-packages (from matplotlib) (3.2.3)
    Requirement already satisfied: six>=1.5 in c:\users\hp\miniconda3\envs\py312\lib\site-packages (from python-dateutil>=2.8.2->pandas) (1.17.0)
    Downloading wordcloud-1.9.4-cp312-cp312-win_amd64.whl (301 kB)
    Installing collected packages: wordcloud
    Successfully installed wordcloud-1.9.4
    


```python
import requests
from bs4 import BeautifulSoup
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
from wordcloud import WordCloud

```

    C:\Users\HP\miniconda3\envs\py312\Lib\site-packages\requests\__init__.py:86: RequestsDependencyWarning: Unable to find acceptable character detection dependency (chardet or charset_normalizer).
      warnings.warn(
    


```python
pip install chardet

```

    Collecting chardet
      Downloading chardet-5.2.0-py3-none-any.whl.metadata (3.4 kB)
    Downloading chardet-5.2.0-py3-none-any.whl (199 kB)
    Installing collected packages: chardet
    Successfully installed chardet-5.2.0
    Note: you may need to restart the kernel to use updated packages.
    


```python
import requests
from bs4 import BeautifulSoup
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
from wordcloud import WordCloud

```


```python
base_url = "http://books.toscrape.com/catalogue/page-{}.html"

```


```python
titles = []
prices = []
ratings = []

```


```python
for page_num in range(1, 6):  # scraping 5 pages
    url = base_url.format(page_num)
    response = requests.get(url)
    soup = BeautifulSoup(response.content, 'html.parser')
    
    books = soup.find_all('article', class_='product_pod')
    
    for book in books:
        title = book.h3.a['title']
        price = float(book.find('p', class_='price_color').text[1:])
        rating = book.p['class'][1]
        
        titles.append(title)
        prices.append(price)
        ratings.append(rating)

```


```python
df = pd.DataFrame({
    "title": titles,
    "price": prices,
    "rating": ratings
})
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
      <th>title</th>
      <th>price</th>
      <th>rating</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>A Light in the Attic</td>
      <td>51.77</td>
      <td>Three</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Tipping the Velvet</td>
      <td>53.74</td>
      <td>One</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Soumission</td>
      <td>50.10</td>
      <td>One</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Sharp Objects</td>
      <td>47.82</td>
      <td>Four</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Sapiens: A Brief History of Humankind</td>
      <td>54.23</td>
      <td>Five</td>
    </tr>
  </tbody>
</table>
</div>




```python
rating_map = {
    "One": 1,
    "Two": 2,
    "Three": 3,
    "Four": 4,
    "Five": 5
}
df["rating_num"] = df["rating"].map(rating_map)

```


```python
df.sort_values(by="price", ascending=False).head(10)

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
      <th>price</th>
      <th>rating</th>
      <th>rating_num</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>68</th>
      <td>The Death of Humanity: and the Case for Life</td>
      <td>58.11</td>
      <td>Four</td>
      <td>4</td>
    </tr>
    <tr>
      <th>40</th>
      <td>Slow States of Collapse: Poems</td>
      <td>57.31</td>
      <td>Three</td>
      <td>3</td>
    </tr>
    <tr>
      <th>15</th>
      <td>Our Band Could Be Your Life: Scenes from the A...</td>
      <td>57.25</td>
      <td>Three</td>
      <td>3</td>
    </tr>
    <tr>
      <th>58</th>
      <td>The Past Never Ends</td>
      <td>56.50</td>
      <td>Four</td>
      <td>4</td>
    </tr>
    <tr>
      <th>57</th>
      <td>The Pioneer Woman Cooks: Dinnertime: Comfort C...</td>
      <td>56.41</td>
      <td>One</td>
      <td>1</td>
    </tr>
    <tr>
      <th>91</th>
      <td>Masks and Shadows</td>
      <td>56.40</td>
      <td>Two</td>
      <td>2</td>
    </tr>
    <tr>
      <th>56</th>
      <td>The Secret of Dreadwillow Carse</td>
      <td>56.13</td>
      <td>One</td>
      <td>1</td>
    </tr>
    <tr>
      <th>67</th>
      <td>The Electric Pencil: Drawings from Inside Stat...</td>
      <td>56.06</td>
      <td>One</td>
      <td>1</td>
    </tr>
    <tr>
      <th>25</th>
      <td>Birdsong: A Story in Pictures</td>
      <td>54.64</td>
      <td>Three</td>
      <td>3</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Sapiens: A Brief History of Humankind</td>
      <td>54.23</td>
      <td>Five</td>
      <td>5</td>
    </tr>
  </tbody>
</table>
</div>




```python
plt.figure(figsize=(10, 5))
sns.histplot(df["price"], bins=15, kde=True, color="teal")
plt.title("Distribution of Book Prices")
plt.xlabel("Price (£)")
plt.ylabel("Number of Books")
plt.show()

```


    
![png](/pynotes/images/books_10_0.png)
    



```python
plt.figure(figsize=(8, 5))
sns.boxplot(x="rating_num", y="price", data=df)
plt.title("Book Prices vs Ratings")
plt.xlabel("Rating (1 to 5)")
plt.ylabel("Price (£)")
plt.show()

```


    
![png](/pynotes/images/books_11_0.png)
    



```python
high_rated = df[df["rating_num"] >= 4]
high_rated.head()

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
      <th>price</th>
      <th>rating</th>
      <th>rating_num</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>3</th>
      <td>Sharp Objects</td>
      <td>47.82</td>
      <td>Four</td>
      <td>4</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Sapiens: A Brief History of Humankind</td>
      <td>54.23</td>
      <td>Five</td>
      <td>5</td>
    </tr>
    <tr>
      <th>6</th>
      <td>The Dirty Little Secrets of Getting Your Dream...</td>
      <td>33.34</td>
      <td>Four</td>
      <td>4</td>
    </tr>
    <tr>
      <th>8</th>
      <td>The Boys in the Boat: Nine Americans and Their...</td>
      <td>22.60</td>
      <td>Four</td>
      <td>4</td>
    </tr>
    <tr>
      <th>11</th>
      <td>Shakespeare's Sonnets</td>
      <td>20.66</td>
      <td>Four</td>
      <td>4</td>
    </tr>
  </tbody>
</table>
</div>




```python
all_titles = " ".join(df["title"])
wordcloud = WordCloud(width=800, height=400, background_color="white").generate(all_titles)

plt.figure(figsize=(10, 5))
plt.imshow(wordcloud, interpolation='bilinear')
plt.axis('off')
plt.title("Word Cloud of Book Titles")
plt.show()

```


    
![png](/pynotes/images/books_13_0.png)
    



```python
df.groupby("rating_num")["price"].mean().plot(kind='bar', color="orange")
plt.title("Average Price by Rating")
plt.ylabel("Average Price (£)")
plt.xlabel("Rating")
plt.show()

```


    
![png](/pynotes/images/books_14_0.png)
    



```python
df["rating_num"].value_counts().sort_index().plot(kind='bar', color="purple")
plt.title("Book Count by Rating")
plt.ylabel("Number of Books")
plt.xlabel("Rating")
plt.show()

```


    
![png](/pynotes/images/books_15_0.png)
    



```python
df.isnull().sum()

```




    title         0
    price         0
    rating        0
    rating_num    0
    dtype: int64




```python
df.to_csv("books.csv", index=False)

```


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
      <th>price</th>
      <th>rating_num</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>count</th>
      <td>100.000000</td>
      <td>100.000000</td>
    </tr>
    <tr>
      <th>mean</th>
      <td>34.560700</td>
      <td>2.930000</td>
    </tr>
    <tr>
      <th>std</th>
      <td>14.638531</td>
      <td>1.423149</td>
    </tr>
    <tr>
      <th>min</th>
      <td>10.160000</td>
      <td>1.000000</td>
    </tr>
    <tr>
      <th>25%</th>
      <td>19.897500</td>
      <td>2.000000</td>
    </tr>
    <tr>
      <th>50%</th>
      <td>34.775000</td>
      <td>3.000000</td>
    </tr>
    <tr>
      <th>75%</th>
      <td>47.967500</td>
      <td>4.000000</td>
    </tr>
    <tr>
      <th>max</th>
      <td>58.110000</td>
      <td>5.000000</td>
    </tr>
  </tbody>
</table>
</div>




```python
df[df["rating_num"] == 5][["title", "price"]].head()

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
      <th>price</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>4</th>
      <td>Sapiens: A Brief History of Humankind</td>
      <td>54.23</td>
    </tr>
    <tr>
      <th>12</th>
      <td>Set Me Free</td>
      <td>17.46</td>
    </tr>
    <tr>
      <th>13</th>
      <td>Scott Pilgrim's Precious Little Life (Scott Pi...</td>
      <td>52.29</td>
    </tr>
    <tr>
      <th>14</th>
      <td>Rip it Up and Start Again</td>
      <td>35.02</td>
    </tr>
    <tr>
      <th>23</th>
      <td>Chase Me (Paris Nights #2)</td>
      <td>25.27</td>
    </tr>
  </tbody>
</table>
</div>




```python
df["price_category"] = pd.cut(df["price"], bins=[0, 20, 40, 60], labels=["Low", "Medium", "High"])
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
      <th>title</th>
      <th>price</th>
      <th>rating</th>
      <th>rating_num</th>
      <th>price_category</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>A Light in the Attic</td>
      <td>51.77</td>
      <td>Three</td>
      <td>3</td>
      <td>High</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Tipping the Velvet</td>
      <td>53.74</td>
      <td>One</td>
      <td>1</td>
      <td>High</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Soumission</td>
      <td>50.10</td>
      <td>One</td>
      <td>1</td>
      <td>High</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Sharp Objects</td>
      <td>47.82</td>
      <td>Four</td>
      <td>4</td>
      <td>High</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Sapiens: A Brief History of Humankind</td>
      <td>54.23</td>
      <td>Five</td>
      <td>5</td>
      <td>High</td>
    </tr>
  </tbody>
</table>
</div>




```python
df["price_category"].value_counts().plot(kind="pie", autopct="%1.1f%%", colors=["lightgreen", "gold", "salmon"])
plt.title("Price Category Distribution")
plt.ylabel("")
plt.show()

```


    
![png](/pynotes/images/books_21_0.png)
    



```python

```


---
**Score: 20**