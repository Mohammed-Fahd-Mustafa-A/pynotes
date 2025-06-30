---
title: Notesi
date: 2025-06-30
author: Your Name
cell_count: 2505
score: 2505
---

```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: NumPy
import numpy as np
print(np.linspace(0, 1, 5))
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: NumPy
import numpy as np
print(np.linspace(0, 1, 5))
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: NumPy
import numpy as np
print(np.linspace(0, 1, 5))
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: NumPy
import numpy as np
print(np.linspace(0, 1, 5))
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: NumPy
import numpy as np
print(np.linspace(0, 1, 5))
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: NumPy
import numpy as np
print(np.linspace(0, 1, 5))
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: NumPy
import numpy as np
print(np.linspace(0, 1, 5))
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: NumPy
import numpy as np
print(np.linspace(0, 1, 5))
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: NumPy
import numpy as np
print(np.linspace(0, 1, 5))
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: NumPy
import numpy as np
print(np.linspace(0, 1, 5))
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: NumPy
import numpy as np
print(np.linspace(0, 1, 5))
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: NumPy
import numpy as np
print(np.linspace(0, 1, 5))
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: NumPy
import numpy as np
print(np.linspace(0, 1, 5))
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: NumPy
import numpy as np
print(np.linspace(0, 1, 5))
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: NumPy
import numpy as np
print(np.linspace(0, 1, 5))
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: NumPy
import numpy as np
print(np.linspace(0, 1, 5))
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: NumPy
import numpy as np
print(np.linspace(0, 1, 5))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: NumPy
import numpy as np
print(np.linspace(0, 1, 5))
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: NumPy
import numpy as np
print(np.linspace(0, 1, 5))
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: NumPy
import numpy as np
print(np.linspace(0, 1, 5))
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: NumPy
import numpy as np
print(np.linspace(0, 1, 5))
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: NumPy
import numpy as np
print(np.linspace(0, 1, 5))
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: NumPy
import numpy as np
print(np.linspace(0, 1, 5))
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: NumPy
import numpy as np
print(np.linspace(0, 1, 5))
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: NumPy
import numpy as np
print(np.linspace(0, 1, 5))
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: NumPy
import numpy as np
print(np.linspace(0, 1, 5))
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: NumPy
import numpy as np
print(np.linspace(0, 1, 5))
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: NumPy
import numpy as np
print(np.linspace(0, 1, 5))
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: NumPy
import numpy as np
print(np.linspace(0, 1, 5))
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: NumPy
import numpy as np
print(np.linspace(0, 1, 5))
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: NumPy
import numpy as np
print(np.linspace(0, 1, 5))
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: NumPy
import numpy as np
print(np.linspace(0, 1, 5))
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: NumPy
import numpy as np
print(np.linspace(0, 1, 5))
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: NumPy
import numpy as np
print(np.linspace(0, 1, 5))
```


```
# Topic: NumPy
import numpy as np
print(np.linspace(0, 1, 5))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: NumPy
import numpy as np
print(np.linspace(0, 1, 5))
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: NumPy
import numpy as np
print(np.linspace(0, 1, 5))
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: NumPy
import numpy as np
print(np.linspace(0, 1, 5))
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: NumPy
import numpy as np
print(np.linspace(0, 1, 5))
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: NumPy
import numpy as np
print(np.linspace(0, 1, 5))
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: NumPy
import numpy as np
print(np.linspace(0, 1, 5))
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Basics
name = 'Fahd'
print(f'Hello, {name}')
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: NumPy
import numpy as np
print(np.linspace(0, 1, 5))
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Functions
def greet(name='User'):
    print(f'Hi, {name}')
greet()
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: NumPy
import numpy as np
print(np.linspace(0, 1, 5))
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Dictionaries & Sets
s = set([1, 2, 3, 2])
print(s)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: NumPy
import numpy as np
print(np.linspace(0, 1, 5))
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Data Cleaning
import pandas as pd
df = pd.DataFrame({'A':[1,None,3]})
df = df.fillna(0)
print(df)
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: File I/O
with open('test.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Functions
def square(x): return x*x
print(square(5))
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: File I/O
with open('test.txt', 'r') as f:
    print(f.read())
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: Lists & Tuples
lst = [1, 2, 3]
lst.append(4)
print(lst)
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Regex
import re
text = 'email: test@example.com'
print(re.findall(r'\S+@\S+', text))
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Lists & Tuples
t = (1, 2, 3)
print(t[0])
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: OOP
class Student:
    def __init__(self, name): self.name = name
s = Student('Fahd')
print(s.name)
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Mini Projects
# Calculator
def calc(a,b,op): return eval(f'{a}{op}{b}')
print(calc(5,2,'+'))
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: NumPy
import numpy as np
a = np.array([1, 2, 3])
print(a + 5)
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Matplotlib & Seaborn
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Mini Projects
# Palindrome check
def is_pal(s): return s == s[::-1]
print(is_pal('madam'))
```


```
# Topic: JSON & CSV
import json
data = {'a': 1}
print(json.dumps(data))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.text)
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Decorators
def log(func):
 def wrapper():
  print('Call')
  func()
 return wrapper
@log
def say(): print('Hi')
say()
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: CLI Tools
import sys
print(f'Arguments: {sys.argv}')
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Dictionaries & Sets
d = {'name': 'Fahd', 'age': 20}
print(d.get('name'))
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('file.csv')
print(df.head())
```


```
# Topic: Recursion
def fact(n): return 1 if n==0 else n*fact(n-1)
print(fact(5))
```


```
# Topic: Basic ML
from sklearn.linear_model import LinearRegression
model = LinearRegression()
print(model)
```


```
# Topic: Basics
x = 10
y = 20
print(x + y)
```


```
# Topic: Matplotlib & Seaborn
import seaborn as sns
import pandas as pd
sns.set()
sns.histplot(pd.Series([1,2,2,3]));
```


```
# Topic: Algorithms
# Bubble sort
def bubble(arr):
 for i in range(len(arr)):
  for j in range(0, len(arr)-i-1):
   if arr[j]>arr[j+1]: arr[j],arr[j+1]=arr[j+1],arr[j]
a=[5,3,8]
bubble(a)
print(a)
```


```
# Topic: Loops
while True:
    print('Break')
    break
```


```
# Topic: JSON & CSV
import csv
with open('file.csv', 'w', newline='') as f:
 csv.writer(f).writerow(['a','b','c'])
```


---
**Score: 2505**