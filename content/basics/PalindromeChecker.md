---
title: Palindromechecker
date: 2025-06-28
author: Your Name
cell_count: 3
score: 0
---

```python
def is_palindrome(text):
    clean = ''.join(c.lower() for c in text if c.isalnum())
    return clean == clean[::-1]

# Test cases
print(is_palindrome("Madam"))             # True
print(is_palindrome("Race car!"))         # True
print(is_palindrome("Hello"))             # False

```

    True
    True
    False
    


```python

```


```python

```


---
**Score: 0**