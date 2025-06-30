---
title: File
date: 2025-06-30
author: Your Name
cell_count: 10
score: 10
---

```python
# Create sample text
sample_text = """
Python is an amazing programming language.
It is popular for data science, AI, and more.
Python emphasizes code readability.
"""

```


```python
# Write to file
with open("sample.txt", "w") as f:
    f.write(sample_text)

```


```python
# Read the file
with open("sample.txt", "r") as f:
    content = f.read()

print(content)

```

    
    Python is an amazing programming language.
    It is popular for data science, AI, and more.
    Python emphasizes code readability.
    
    


```python
# Line count
lines = content.strip().split("\n")
len(lines)

```




    3




```python
# Word count
words = content.split()
len(words)

```




    19




```python
# Char count (excluding whitespace)
len(content.replace(" ", "").replace("\n", ""))

```




    106




```python
# Word frequency
from collections import Counter
freq = Counter(words)
freq

```




    Counter({'Python': 2,
             'is': 2,
             'an': 1,
             'amazing': 1,
             'programming': 1,
             'language.': 1,
             'It': 1,
             'popular': 1,
             'for': 1,
             'data': 1,
             'science,': 1,
             'AI,': 1,
             'and': 1,
             'more.': 1,
             'emphasizes': 1,
             'code': 1,
             'readability.': 1})




```python
# Most common word
freq.most_common(1)

```




    [('Python', 2)]




```python
# Longest word
max(words, key=len)

```




    'readability.'




```python

```


---
**Score: 10**