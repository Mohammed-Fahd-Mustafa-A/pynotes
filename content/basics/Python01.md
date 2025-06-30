---
title: Python01
date: 2025-06-30
author: Your Name
cell_count: 810
score: 810
---

```
# Topic: Lists & Tuples
nums = [1,2,3]
nums.append(4)
print(nums)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.string)
```


```
# Topic: NumPy
import numpy as np
a = np.array([1,2,3])
print(a * 2)
```


```
# Topic: Loops
i = 0
while i < 5:
    print(i)
    i += 1
```


```
# Topic: Dictionaries & Sets
s = {1,2,3}
s.add(4)
print(s)
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head())
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.bar(['A','B'], [10,20])
plt.show()
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.bar(['A','B'], [10,20])
plt.show()
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.string)
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: Basics
x = 7
print('Odd' if x % 2 else 'Even')
```


```
# Topic: Basics
x = 7
print('Odd' if x % 2 else 'Even')
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head())
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: File I/O
with open('sample.txt') as f:
    print(f.read())
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.bar(['A','B'], [10,20])
plt.show()
```


```
# Topic: Loops
i = 0
while i < 5:
    print(i)
    i += 1
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head())
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: Mini Projects
# Palindrome checker
def is_palindrome(s):
 return s == s[::-1]
print(is_palindrome('madam'))
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: Dictionaries & Sets
s = {1,2,3}
s.add(4)
print(s)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.string)
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: File I/O
with open('sample.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Lists & Tuples
nums = [1,2,3]
nums.append(4)
print(nums)
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: NumPy
import numpy as np
a = np.array([1,2,3])
print(a * 2)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.string)
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Lists & Tuples
t = (1,2,3)
print(t[1])
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Loops
i = 0
while i < 5:
    print(i)
    i += 1
```


```
# Topic: Functions
def factorial(n):
    return 1 if n==0 else n * factorial(n-1)
print(factorial(5))
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Basics
x = 7
print('Odd' if x % 2 else 'Even')
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Lists & Tuples
nums = [1,2,3]
nums.append(4)
print(nums)
```


```
# Topic: File I/O
with open('sample.txt') as f:
    print(f.read())
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Lists & Tuples
nums = [1,2,3]
nums.append(4)
print(nums)
```


```
# Topic: Lists & Tuples
t = (1,2,3)
print(t[1])
```


```
# Topic: Mini Projects
# Simple calculator
def calc(a,b,op):
 if op=='+': return a+b
 elif op=='-': return a-b
print(calc(10,5,'+'))
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Functions
def factorial(n):
    return 1 if n==0 else n * factorial(n-1)
print(factorial(5))
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head())
```


```
# Topic: Lists & Tuples
nums = [1,2,3]
nums.append(4)
print(nums)
```


```
# Topic: Loops
i = 0
while i < 5:
    print(i)
    i += 1
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.bar(['A','B'], [10,20])
plt.show()
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.bar(['A','B'], [10,20])
plt.show()
```


```
# Topic: Basics
name = 'Fahd'
print(f'Welcome, {name}')
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.bar(['A','B'], [10,20])
plt.show()
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Lists & Tuples
t = (1,2,3)
print(t[1])
```


```
# Topic: Dictionaries & Sets
s = {1,2,3}
s.add(4)
print(s)
```


```
# Topic: NumPy
import numpy as np
a = np.array([1,2,3])
print(a * 2)
```


```
# Topic: Functions
def factorial(n):
    return 1 if n==0 else n * factorial(n-1)
print(factorial(5))
```


```
# Topic: NumPy
import numpy as np
print(np.arange(0, 10, 2))
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: Loops
i = 0
while i < 5:
    print(i)
    i += 1
```


```
# Topic: Dictionaries & Sets
d = {'a':1, 'b':2}
print(d['a'])
```


```
# Topic: Mini Projects
# Simple calculator
def calc(a,b,op):
 if op=='+': return a+b
 elif op=='-': return a-b
print(calc(10,5,'+'))
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.bar(['A','B'], [10,20])
plt.show()
```


```
# Topic: Mini Projects
# Simple calculator
def calc(a,b,op):
 if op=='+': return a+b
 elif op=='-': return a-b
print(calc(10,5,'+'))
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Basics
x = 7
print('Odd' if x % 2 else 'Even')
```


```
# Topic: File I/O
with open('sample.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.bar(['A','B'], [10,20])
plt.show()
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: Lists & Tuples
t = (1,2,3)
print(t[1])
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Dictionaries & Sets
s = {1,2,3}
s.add(4)
print(s)
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Dictionaries & Sets
d = {'a':1, 'b':2}
print(d['a'])
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Loops
i = 0
while i < 5:
    print(i)
    i += 1
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Basics
x = 7
print('Odd' if x % 2 else 'Even')
```


```
# Topic: NumPy
import numpy as np
a = np.array([1,2,3])
print(a * 2)
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head())
```


```
# Topic: Lists & Tuples
nums = [1,2,3]
nums.append(4)
print(nums)
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Functions
def factorial(n):
    return 1 if n==0 else n * factorial(n-1)
print(factorial(5))
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: Basics
name = 'Fahd'
print(f'Welcome, {name}')
```


```
# Topic: NumPy
import numpy as np
a = np.array([1,2,3])
print(a * 2)
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.string)
```


```
# Topic: Basics
x = 7
print('Odd' if x % 2 else 'Even')
```


```
# Topic: Loops
i = 0
while i < 5:
    print(i)
    i += 1
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Mini Projects
# Palindrome checker
def is_palindrome(s):
 return s == s[::-1]
print(is_palindrome('madam'))
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Functions
def add(a, b): return a + b
print(add(3, 4))
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: File I/O
with open('sample.txt') as f:
    print(f.read())
```


```
# Topic: Functions
def add(a, b): return a + b
print(add(3, 4))
```


```
# Topic: Lists & Tuples
nums = [1,2,3]
nums.append(4)
print(nums)
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head())
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
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
# Topic: NumPy
import numpy as np
print(np.arange(0, 10, 2))
```


```
# Topic: Basics
a = 5
b = 3
print(a * b)
```


```
# Topic: Loops
i = 0
while i < 5:
    print(i)
    i += 1
```


```
# Topic: Mini Projects
# Simple calculator
def calc(a,b,op):
 if op=='+': return a+b
 elif op=='-': return a-b
print(calc(10,5,'+'))
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Basics
x = 7
print('Odd' if x % 2 else 'Even')
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: File I/O
with open('sample.txt') as f:
    print(f.read())
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: File I/O
with open('sample.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Dictionaries & Sets
d = {'a':1, 'b':2}
print(d['a'])
```


```
# Topic: File I/O
with open('sample.txt') as f:
    print(f.read())
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head())
```


```
# Topic: NumPy
import numpy as np
print(np.arange(0, 10, 2))
```


```
# Topic: Functions
def add(a, b): return a + b
print(add(3, 4))
```


```
# Topic: Lists & Tuples
t = (1,2,3)
print(t[1])
```


```
# Topic: NumPy
import numpy as np
print(np.arange(0, 10, 2))
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Loops
i = 0
while i < 5:
    print(i)
    i += 1
```


```
# Topic: Dictionaries & Sets
d = {'a':1, 'b':2}
print(d['a'])
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Basics
name = 'Fahd'
print(f'Welcome, {name}')
```


```
# Topic: Lists & Tuples
t = (1,2,3)
print(t[1])
```


```
# Topic: Dictionaries & Sets
d = {'a':1, 'b':2}
print(d['a'])
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Basics
x = 7
print('Odd' if x % 2 else 'Even')
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.bar(['A','B'], [10,20])
plt.show()
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.string)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.string)
```


```
# Topic: File I/O
with open('sample.txt') as f:
    print(f.read())
```


```
# Topic: NumPy
import numpy as np
print(np.arange(0, 10, 2))
```


```
# Topic: Mini Projects
# Palindrome checker
def is_palindrome(s):
 return s == s[::-1]
print(is_palindrome('madam'))
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: Functions
def add(a, b): return a + b
print(add(3, 4))
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: Loops
i = 0
while i < 5:
    print(i)
    i += 1
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: File I/O
with open('sample.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Functions
def add(a, b): return a + b
print(add(3, 4))
```


```
# Topic: Functions
def add(a, b): return a + b
print(add(3, 4))
```


```
# Topic: Dictionaries & Sets
d = {'a':1, 'b':2}
print(d['a'])
```


```
# Topic: NumPy
import numpy as np
a = np.array([1,2,3])
print(a * 2)
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: Mini Projects
# Palindrome checker
def is_palindrome(s):
 return s == s[::-1]
print(is_palindrome('madam'))
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Mini Projects
# Simple calculator
def calc(a,b,op):
 if op=='+': return a+b
 elif op=='-': return a-b
print(calc(10,5,'+'))
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: NumPy
import numpy as np
a = np.array([1,2,3])
print(a * 2)
```


```
# Topic: Basics
name = 'Fahd'
print(f'Welcome, {name}')
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.string)
```


```
# Topic: Dictionaries & Sets
d = {'a':1, 'b':2}
print(d['a'])
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.bar(['A','B'], [10,20])
plt.show()
```


```
# Topic: Lists & Tuples
t = (1,2,3)
print(t[1])
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Functions
def add(a, b): return a + b
print(add(3, 4))
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Dictionaries & Sets
d = {'a':1, 'b':2}
print(d['a'])
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Lists & Tuples
t = (1,2,3)
print(t[1])
```


```
# Topic: Mini Projects
# Simple calculator
def calc(a,b,op):
 if op=='+': return a+b
 elif op=='-': return a-b
print(calc(10,5,'+'))
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head())
```


```
# Topic: Loops
i = 0
while i < 5:
    print(i)
    i += 1
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: File I/O
with open('sample.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: Mini Projects
# Simple calculator
def calc(a,b,op):
 if op=='+': return a+b
 elif op=='-': return a-b
print(calc(10,5,'+'))
```


```
# Topic: Functions
def factorial(n):
    return 1 if n==0 else n * factorial(n-1)
print(factorial(5))
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head())
```


```
# Topic: NumPy
import numpy as np
a = np.array([1,2,3])
print(a * 2)
```


```
# Topic: Basics
a = 5
b = 3
print(a * b)
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Mini Projects
# Palindrome checker
def is_palindrome(s):
 return s == s[::-1]
print(is_palindrome('madam'))
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.bar(['A','B'], [10,20])
plt.show()
```


```
# Topic: Basics
a = 5
b = 3
print(a * b)
```


```
# Topic: Dictionaries & Sets
d = {'a':1, 'b':2}
print(d['a'])
```


```
# Topic: Dictionaries & Sets
s = {1,2,3}
s.add(4)
print(s)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.string)
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Functions
def factorial(n):
    return 1 if n==0 else n * factorial(n-1)
print(factorial(5))
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.bar(['A','B'], [10,20])
plt.show()
```


```
# Topic: NumPy
import numpy as np
a = np.array([1,2,3])
print(a * 2)
```


```
# Topic: Functions
def add(a, b): return a + b
print(add(3, 4))
```


```
# Topic: Basics
name = 'Fahd'
print(f'Welcome, {name}')
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: Dictionaries & Sets
s = {1,2,3}
s.add(4)
print(s)
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Lists & Tuples
t = (1,2,3)
print(t[1])
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: File I/O
with open('sample.txt') as f:
    print(f.read())
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Loops
i = 0
while i < 5:
    print(i)
    i += 1
```


```
# Topic: Lists & Tuples
t = (1,2,3)
print(t[1])
```


```
# Topic: File I/O
with open('sample.txt') as f:
    print(f.read())
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
print(soup.title.string)
```


```
# Topic: Lists & Tuples
nums = [1,2,3]
nums.append(4)
print(nums)
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: Mini Projects
# Palindrome checker
def is_palindrome(s):
 return s == s[::-1]
print(is_palindrome('madam'))
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: Mini Projects
# Palindrome checker
def is_palindrome(s):
 return s == s[::-1]
print(is_palindrome('madam'))
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Lists & Tuples
t = (1,2,3)
print(t[1])
```


```
# Topic: File I/O
with open('sample.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head())
```


```
# Topic: Mini Projects
# Simple calculator
def calc(a,b,op):
 if op=='+': return a+b
 elif op=='-': return a-b
print(calc(10,5,'+'))
```


```
# Topic: Mini Projects
# Simple calculator
def calc(a,b,op):
 if op=='+': return a+b
 elif op=='-': return a-b
print(calc(10,5,'+'))
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Dictionaries & Sets
s = {1,2,3}
s.add(4)
print(s)
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.bar(['A','B'], [10,20])
plt.show()
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.string)
```


```
# Topic: Dictionaries & Sets
d = {'a':1, 'b':2}
print(d['a'])
```


```
# Topic: Lists & Tuples
t = (1,2,3)
print(t[1])
```


```
# Topic: File I/O
with open('sample.txt') as f:
    print(f.read())
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.bar(['A','B'], [10,20])
plt.show()
```


```
# Topic: Loops
i = 0
while i < 5:
    print(i)
    i += 1
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.bar(['A','B'], [10,20])
plt.show()
```


```
# Topic: NumPy
import numpy as np
print(np.arange(0, 10, 2))
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Basics
x = 7
print('Odd' if x % 2 else 'Even')
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Mini Projects
# Palindrome checker
def is_palindrome(s):
 return s == s[::-1]
print(is_palindrome('madam'))
```


```
# Topic: File I/O
with open('sample.txt') as f:
    print(f.read())
```


```
# Topic: Basics
a = 5
b = 3
print(a * b)
```


```
# Topic: Loops
i = 0
while i < 5:
    print(i)
    i += 1
```


```
# Topic: File I/O
with open('sample.txt') as f:
    print(f.read())
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.string)
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: File I/O
with open('sample.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.string)
```


```
# Topic: File I/O
with open('sample.txt') as f:
    print(f.read())
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Basics
a = 5
b = 3
print(a * b)
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.string)
```


```
# Topic: Lists & Tuples
t = (1,2,3)
print(t[1])
```


```
# Topic: Matplotlib
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
print(soup.title.string)
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.bar(['A','B'], [10,20])
plt.show()
```


```
# Topic: NumPy
import numpy as np
print(np.arange(0, 10, 2))
```


```
# Topic: Functions
def add(a, b): return a + b
print(add(3, 4))
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: Loops
i = 0
while i < 5:
    print(i)
    i += 1
```


```
# Topic: Functions
def add(a, b): return a + b
print(add(3, 4))
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.bar(['A','B'], [10,20])
plt.show()
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.bar(['A','B'], [10,20])
plt.show()
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.string)
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
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: Mini Projects
# Simple calculator
def calc(a,b,op):
 if op=='+': return a+b
 elif op=='-': return a-b
print(calc(10,5,'+'))
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.string)
```


```
# Topic: Functions
def add(a, b): return a + b
print(add(3, 4))
```


```
# Topic: Mini Projects
# Simple calculator
def calc(a,b,op):
 if op=='+': return a+b
 elif op=='-': return a-b
print(calc(10,5,'+'))
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: Basics
a = 5
b = 3
print(a * b)
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.bar(['A','B'], [10,20])
plt.show()
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: NumPy
import numpy as np
a = np.array([1,2,3])
print(a * 2)
```


```
# Topic: Dictionaries & Sets
s = {1,2,3}
s.add(4)
print(s)
```


```
# Topic: Basics
name = 'Fahd'
print(f'Welcome, {name}')
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.string)
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: File I/O
with open('sample.txt') as f:
    print(f.read())
```


```
# Topic: Functions
def factorial(n):
    return 1 if n==0 else n * factorial(n-1)
print(factorial(5))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.string)
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: Basics
x = 7
print('Odd' if x % 2 else 'Even')
```


```
# Topic: Dictionaries & Sets
s = {1,2,3}
s.add(4)
print(s)
```


```
# Topic: Mini Projects
# Palindrome checker
def is_palindrome(s):
 return s == s[::-1]
print(is_palindrome('madam'))
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.string)
```


```
# Topic: Functions
def factorial(n):
    return 1 if n==0 else n * factorial(n-1)
print(factorial(5))
```


```
# Topic: Basics
name = 'Fahd'
print(f'Welcome, {name}')
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Dictionaries & Sets
s = {1,2,3}
s.add(4)
print(s)
```


```
# Topic: File I/O
with open('sample.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: File I/O
with open('sample.txt') as f:
    print(f.read())
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Basics
name = 'Fahd'
print(f'Welcome, {name}')
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: Mini Projects
# Simple calculator
def calc(a,b,op):
 if op=='+': return a+b
 elif op=='-': return a-b
print(calc(10,5,'+'))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.string)
```


```
# Topic: Functions
def factorial(n):
    return 1 if n==0 else n * factorial(n-1)
print(factorial(5))
```


```
# Topic: Loops
i = 0
while i < 5:
    print(i)
    i += 1
```


```
# Topic: Basics
x = 7
print('Odd' if x % 2 else 'Even')
```


```
# Topic: Mini Projects
# Simple calculator
def calc(a,b,op):
 if op=='+': return a+b
 elif op=='-': return a-b
print(calc(10,5,'+'))
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Lists & Tuples
nums = [1,2,3]
nums.append(4)
print(nums)
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: Lists & Tuples
t = (1,2,3)
print(t[1])
```


```
# Topic: Mini Projects
# Palindrome checker
def is_palindrome(s):
 return s == s[::-1]
print(is_palindrome('madam'))
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: File I/O
with open('sample.txt') as f:
    print(f.read())
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: Functions
def add(a, b): return a + b
print(add(3, 4))
```


```
# Topic: Basics
a = 5
b = 3
print(a * b)
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: File I/O
with open('sample.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Lists & Tuples
t = (1,2,3)
print(t[1])
```


```
# Topic: Lists & Tuples
t = (1,2,3)
print(t[1])
```


```
# Topic: File I/O
with open('sample.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Functions
def factorial(n):
    return 1 if n==0 else n * factorial(n-1)
print(factorial(5))
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
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
print(soup.title.string)
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: Functions
def add(a, b): return a + b
print(add(3, 4))
```


```
# Topic: Basics
name = 'Fahd'
print(f'Welcome, {name}')
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head())
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head())
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: NumPy
import numpy as np
a = np.array([1,2,3])
print(a * 2)
```


```
# Topic: Basics
name = 'Fahd'
print(f'Welcome, {name}')
```


```
# Topic: Basics
x = 7
print('Odd' if x % 2 else 'Even')
```


```
# Topic: Functions
def factorial(n):
    return 1 if n==0 else n * factorial(n-1)
print(factorial(5))
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head())
```


```
# Topic: Mini Projects
# Palindrome checker
def is_palindrome(s):
 return s == s[::-1]
print(is_palindrome('madam'))
```


```
# Topic: NumPy
import numpy as np
print(np.arange(0, 10, 2))
```


```
# Topic: Lists & Tuples
t = (1,2,3)
print(t[1])
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.string)
```


```
# Topic: Lists & Tuples
nums = [1,2,3]
nums.append(4)
print(nums)
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.bar(['A','B'], [10,20])
plt.show()
```


```
# Topic: File I/O
with open('sample.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.string)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.string)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.string)
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.string)
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: NumPy
import numpy as np
print(np.arange(0, 10, 2))
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Dictionaries & Sets
d = {'a':1, 'b':2}
print(d['a'])
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.string)
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Basics
name = 'Fahd'
print(f'Welcome, {name}')
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Dictionaries & Sets
s = {1,2,3}
s.add(4)
print(s)
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.bar(['A','B'], [10,20])
plt.show()
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Dictionaries & Sets
d = {'a':1, 'b':2}
print(d['a'])
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.bar(['A','B'], [10,20])
plt.show()
```


```
# Topic: Dictionaries & Sets
d = {'a':1, 'b':2}
print(d['a'])
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head())
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Loops
i = 0
while i < 5:
    print(i)
    i += 1
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head())
```


```
# Topic: Loops
i = 0
while i < 5:
    print(i)
    i += 1
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: File I/O
with open('sample.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.bar(['A','B'], [10,20])
plt.show()
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: Mini Projects
# Palindrome checker
def is_palindrome(s):
 return s == s[::-1]
print(is_palindrome('madam'))
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head())
```


```
# Topic: Mini Projects
# Simple calculator
def calc(a,b,op):
 if op=='+': return a+b
 elif op=='-': return a-b
print(calc(10,5,'+'))
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head())
```


```
# Topic: Functions
def factorial(n):
    return 1 if n==0 else n * factorial(n-1)
print(factorial(5))
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Mini Projects
# Simple calculator
def calc(a,b,op):
 if op=='+': return a+b
 elif op=='-': return a-b
print(calc(10,5,'+'))
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: File I/O
with open('sample.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Mini Projects
# Simple calculator
def calc(a,b,op):
 if op=='+': return a+b
 elif op=='-': return a-b
print(calc(10,5,'+'))
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.bar(['A','B'], [10,20])
plt.show()
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Mini Projects
# Simple calculator
def calc(a,b,op):
 if op=='+': return a+b
 elif op=='-': return a-b
print(calc(10,5,'+'))
```


```
# Topic: Basics
a = 5
b = 3
print(a * b)
```


```
# Topic: File I/O
with open('sample.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head())
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Lists & Tuples
t = (1,2,3)
print(t[1])
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: File I/O
with open('sample.txt') as f:
    print(f.read())
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.string)
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: Lists & Tuples
t = (1,2,3)
print(t[1])
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Dictionaries & Sets
s = {1,2,3}
s.add(4)
print(s)
```


```
# Topic: Mini Projects
# Simple calculator
def calc(a,b,op):
 if op=='+': return a+b
 elif op=='-': return a-b
print(calc(10,5,'+'))
```


```
# Topic: NumPy
import numpy as np
a = np.array([1,2,3])
print(a * 2)
```


```
# Topic: Dictionaries & Sets
s = {1,2,3}
s.add(4)
print(s)
```


```
# Topic: Functions
def factorial(n):
    return 1 if n==0 else n * factorial(n-1)
print(factorial(5))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.string)
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Dictionaries & Sets
d = {'a':1, 'b':2}
print(d['a'])
```


```
# Topic: Mini Projects
# Simple calculator
def calc(a,b,op):
 if op=='+': return a+b
 elif op=='-': return a-b
print(calc(10,5,'+'))
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head())
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: File I/O
with open('sample.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: Functions
def factorial(n):
    return 1 if n==0 else n * factorial(n-1)
print(factorial(5))
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head())
```


```
# Topic: File I/O
with open('sample.txt') as f:
    print(f.read())
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.string)
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.bar(['A','B'], [10,20])
plt.show()
```


```
# Topic: Dictionaries & Sets
s = {1,2,3}
s.add(4)
print(s)
```


```
# Topic: Mini Projects
# Simple calculator
def calc(a,b,op):
 if op=='+': return a+b
 elif op=='-': return a-b
print(calc(10,5,'+'))
```


```
# Topic: Dictionaries & Sets
s = {1,2,3}
s.add(4)
print(s)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.string)
```


```
# Topic: Mini Projects
# Simple calculator
def calc(a,b,op):
 if op=='+': return a+b
 elif op=='-': return a-b
print(calc(10,5,'+'))
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.bar(['A','B'], [10,20])
plt.show()
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Loops
i = 0
while i < 5:
    print(i)
    i += 1
```


```
# Topic: Dictionaries & Sets
s = {1,2,3}
s.add(4)
print(s)
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head())
```


```
# Topic: Functions
def add(a, b): return a + b
print(add(3, 4))
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: File I/O
with open('sample.txt', 'w') as f:
    f.write('Hello World')
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
print(soup.title.string)
```


```
# Topic: Functions
def add(a, b): return a + b
print(add(3, 4))
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head())
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.bar(['A','B'], [10,20])
plt.show()
```


```
# Topic: Dictionaries & Sets
d = {'a':1, 'b':2}
print(d['a'])
```


```
# Topic: Mini Projects
# Palindrome checker
def is_palindrome(s):
 return s == s[::-1]
print(is_palindrome('madam'))
```


```
# Topic: Dictionaries & Sets
s = {1,2,3}
s.add(4)
print(s)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.string)
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.string)
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: NumPy
import numpy as np
print(np.arange(0, 10, 2))
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Lists & Tuples
nums = [1,2,3]
nums.append(4)
print(nums)
```


```
# Topic: Lists & Tuples
t = (1,2,3)
print(t[1])
```


```
# Topic: Lists & Tuples
nums = [1,2,3]
nums.append(4)
print(nums)
```


```
# Topic: Basics
name = 'Fahd'
print(f'Welcome, {name}')
```


```
# Topic: Basics
name = 'Fahd'
print(f'Welcome, {name}')
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Functions
def factorial(n):
    return 1 if n==0 else n * factorial(n-1)
print(factorial(5))
```


```
# Topic: Mini Projects
# Palindrome checker
def is_palindrome(s):
 return s == s[::-1]
print(is_palindrome('madam'))
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Lists & Tuples
t = (1,2,3)
print(t[1])
```


```
# Topic: Basics
a = 5
b = 3
print(a * b)
```


```
# Topic: Mini Projects
# Simple calculator
def calc(a,b,op):
 if op=='+': return a+b
 elif op=='-': return a-b
print(calc(10,5,'+'))
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: NumPy
import numpy as np
a = np.array([1,2,3])
print(a * 2)
```


```
# Topic: Mini Projects
# Palindrome checker
def is_palindrome(s):
 return s == s[::-1]
print(is_palindrome('madam'))
```


```
# Topic: NumPy
import numpy as np
a = np.array([1,2,3])
print(a * 2)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.string)
```


```
# Topic: Functions
def add(a, b): return a + b
print(add(3, 4))
```


```
# Topic: Dictionaries & Sets
s = {1,2,3}
s.add(4)
print(s)
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: File I/O
with open('sample.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: NumPy
import numpy as np
print(np.arange(0, 10, 2))
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Basics
name = 'Fahd'
print(f'Welcome, {name}')
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Loops
i = 0
while i < 5:
    print(i)
    i += 1
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.string)
```


```
# Topic: File I/O
with open('sample.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: File I/O
with open('sample.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head())
```


```
# Topic: Basics
a = 5
b = 3
print(a * b)
```


```
# Topic: Basics
a = 5
b = 3
print(a * b)
```


```
# Topic: Basics
x = 7
print('Odd' if x % 2 else 'Even')
```


```
# Topic: Dictionaries & Sets
d = {'a':1, 'b':2}
print(d['a'])
```


```
# Topic: Loops
i = 0
while i < 5:
    print(i)
    i += 1
```


```
# Topic: Loops
i = 0
while i < 5:
    print(i)
    i += 1
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head())
```


```
# Topic: Basics
a = 5
b = 3
print(a * b)
```


```
# Topic: Functions
def factorial(n):
    return 1 if n==0 else n * factorial(n-1)
print(factorial(5))
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Mini Projects
# Palindrome checker
def is_palindrome(s):
 return s == s[::-1]
print(is_palindrome('madam'))
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Dictionaries & Sets
d = {'a':1, 'b':2}
print(d['a'])
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.string)
```


```
# Topic: Mini Projects
# Palindrome checker
def is_palindrome(s):
 return s == s[::-1]
print(is_palindrome('madam'))
```


```
# Topic: Dictionaries & Sets
s = {1,2,3}
s.add(4)
print(s)
```


```
# Topic: Dictionaries & Sets
d = {'a':1, 'b':2}
print(d['a'])
```


```
# Topic: Basics
name = 'Fahd'
print(f'Welcome, {name}')
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head())
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head())
```


```
# Topic: Loops
i = 0
while i < 5:
    print(i)
    i += 1
```


```
# Topic: Functions
def factorial(n):
    return 1 if n==0 else n * factorial(n-1)
print(factorial(5))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.string)
```


```
# Topic: NumPy
import numpy as np
print(np.arange(0, 10, 2))
```


```
# Topic: Functions
def factorial(n):
    return 1 if n==0 else n * factorial(n-1)
print(factorial(5))
```


```
# Topic: Lists & Tuples
nums = [1,2,3]
nums.append(4)
print(nums)
```


```
# Topic: Functions
def factorial(n):
    return 1 if n==0 else n * factorial(n-1)
print(factorial(5))
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: Loops
i = 0
while i < 5:
    print(i)
    i += 1
```


```
# Topic: File I/O
with open('sample.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.string)
```


```
# Topic: Mini Projects
# Simple calculator
def calc(a,b,op):
 if op=='+': return a+b
 elif op=='-': return a-b
print(calc(10,5,'+'))
```


```
# Topic: NumPy
import numpy as np
a = np.array([1,2,3])
print(a * 2)
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: Dictionaries & Sets
s = {1,2,3}
s.add(4)
print(s)
```


```
# Topic: Lists & Tuples
t = (1,2,3)
print(t[1])
```


```
# Topic: NumPy
import numpy as np
print(np.arange(0, 10, 2))
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Functions
def factorial(n):
    return 1 if n==0 else n * factorial(n-1)
print(factorial(5))
```


```
# Topic: File I/O
with open('sample.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.bar(['A','B'], [10,20])
plt.show()
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: NumPy
import numpy as np
a = np.array([1,2,3])
print(a * 2)
```


```
# Topic: Functions
def add(a, b): return a + b
print(add(3, 4))
```


```
# Topic: Lists & Tuples
t = (1,2,3)
print(t[1])
```


```
# Topic: Basics
a = 5
b = 3
print(a * b)
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: NumPy
import numpy as np
print(np.arange(0, 10, 2))
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.bar(['A','B'], [10,20])
plt.show()
```


```
# Topic: Functions
def factorial(n):
    return 1 if n==0 else n * factorial(n-1)
print(factorial(5))
```


```
# Topic: Lists & Tuples
t = (1,2,3)
print(t[1])
```


```
# Topic: Dictionaries & Sets
s = {1,2,3}
s.add(4)
print(s)
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Mini Projects
# Simple calculator
def calc(a,b,op):
 if op=='+': return a+b
 elif op=='-': return a-b
print(calc(10,5,'+'))
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head())
```


```
# Topic: Dictionaries & Sets
s = {1,2,3}
s.add(4)
print(s)
```


```
# Topic: Basics
a = 5
b = 3
print(a * b)
```


```
# Topic: File I/O
with open('sample.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.string)
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head())
```


```
# Topic: Mini Projects
# Simple calculator
def calc(a,b,op):
 if op=='+': return a+b
 elif op=='-': return a-b
print(calc(10,5,'+'))
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.string)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.string)
```


```
# Topic: NumPy
import numpy as np
print(np.arange(0, 10, 2))
```


```
# Topic: Dictionaries & Sets
s = {1,2,3}
s.add(4)
print(s)
```


```
# Topic: Dictionaries & Sets
d = {'a':1, 'b':2}
print(d['a'])
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.string)
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head())
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: File I/O
with open('sample.txt') as f:
    print(f.read())
```


```
# Topic: File I/O
with open('sample.txt') as f:
    print(f.read())
```


```
# Topic: Lists & Tuples
nums = [1,2,3]
nums.append(4)
print(nums)
```


```
# Topic: Functions
def add(a, b): return a + b
print(add(3, 4))
```


```
# Topic: Basics
a = 5
b = 3
print(a * b)
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.bar(['A','B'], [10,20])
plt.show()
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
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: NumPy
import numpy as np
print(np.arange(0, 10, 2))
```


```
# Topic: Basics
a = 5
b = 3
print(a * b)
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.string)
```


```
# Topic: Basics
name = 'Fahd'
print(f'Welcome, {name}')
```


```
# Topic: Loops
i = 0
while i < 5:
    print(i)
    i += 1
```


```
# Topic: Lists & Tuples
t = (1,2,3)
print(t[1])
```


```
# Topic: Functions
def factorial(n):
    return 1 if n==0 else n * factorial(n-1)
print(factorial(5))
```


```
# Topic: File I/O
with open('sample.txt') as f:
    print(f.read())
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Basics
name = 'Fahd'
print(f'Welcome, {name}')
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Basics
a = 5
b = 3
print(a * b)
```


```
# Topic: Basics
a = 5
b = 3
print(a * b)
```


```
# Topic: File I/O
with open('sample.txt') as f:
    print(f.read())
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: File I/O
with open('sample.txt') as f:
    print(f.read())
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
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
# Topic: Mini Projects
# Simple calculator
def calc(a,b,op):
 if op=='+': return a+b
 elif op=='-': return a-b
print(calc(10,5,'+'))
```


```
# Topic: Loops
i = 0
while i < 5:
    print(i)
    i += 1
```


```
# Topic: File I/O
with open('sample.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Dictionaries & Sets
s = {1,2,3}
s.add(4)
print(s)
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: Loops
i = 0
while i < 5:
    print(i)
    i += 1
```


```
# Topic: Matplotlib
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
print(soup.title.string)
```


```
# Topic: Functions
def factorial(n):
    return 1 if n==0 else n * factorial(n-1)
print(factorial(5))
```


```
# Topic: Dictionaries & Sets
s = {1,2,3}
s.add(4)
print(s)
```


```
# Topic: Lists & Tuples
t = (1,2,3)
print(t[1])
```


```
# Topic: NumPy
import numpy as np
a = np.array([1,2,3])
print(a * 2)
```


```
# Topic: NumPy
import numpy as np
print(np.arange(0, 10, 2))
```


```
# Topic: Dictionaries & Sets
d = {'a':1, 'b':2}
print(d['a'])
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
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
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: Mini Projects
# Simple calculator
def calc(a,b,op):
 if op=='+': return a+b
 elif op=='-': return a-b
print(calc(10,5,'+'))
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Mini Projects
# Palindrome checker
def is_palindrome(s):
 return s == s[::-1]
print(is_palindrome('madam'))
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Functions
def factorial(n):
    return 1 if n==0 else n * factorial(n-1)
print(factorial(5))
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Mini Projects
# Palindrome checker
def is_palindrome(s):
 return s == s[::-1]
print(is_palindrome('madam'))
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Functions
def factorial(n):
    return 1 if n==0 else n * factorial(n-1)
print(factorial(5))
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.string)
```


```
# Topic: File I/O
with open('sample.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Loops
i = 0
while i < 5:
    print(i)
    i += 1
```


```
# Topic: File I/O
with open('sample.txt') as f:
    print(f.read())
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Functions
def factorial(n):
    return 1 if n==0 else n * factorial(n-1)
print(factorial(5))
```


```
# Topic: Dictionaries & Sets
d = {'a':1, 'b':2}
print(d['a'])
```


```
# Topic: Basics
name = 'Fahd'
print(f'Welcome, {name}')
```


```
# Topic: Mini Projects
# Simple calculator
def calc(a,b,op):
 if op=='+': return a+b
 elif op=='-': return a-b
print(calc(10,5,'+'))
```


```
# Topic: NumPy
import numpy as np
a = np.array([1,2,3])
print(a * 2)
```


```
# Topic: Basics
x = 7
print('Odd' if x % 2 else 'Even')
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: Functions
def add(a, b): return a + b
print(add(3, 4))
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: Mini Projects
# Palindrome checker
def is_palindrome(s):
 return s == s[::-1]
print(is_palindrome('madam'))
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Functions
def factorial(n):
    return 1 if n==0 else n * factorial(n-1)
print(factorial(5))
```


```
# Topic: Mini Projects
# Simple calculator
def calc(a,b,op):
 if op=='+': return a+b
 elif op=='-': return a-b
print(calc(10,5,'+'))
```


```
# Topic: Functions
def add(a, b): return a + b
print(add(3, 4))
```


```
# Topic: Mini Projects
# Simple calculator
def calc(a,b,op):
 if op=='+': return a+b
 elif op=='-': return a-b
print(calc(10,5,'+'))
```


```
# Topic: NumPy
import numpy as np
a = np.array([1,2,3])
print(a * 2)
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Dictionaries & Sets
d = {'a':1, 'b':2}
print(d['a'])
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.string)
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.bar(['A','B'], [10,20])
plt.show()
```


```
# Topic: Mini Projects
# Simple calculator
def calc(a,b,op):
 if op=='+': return a+b
 elif op=='-': return a-b
print(calc(10,5,'+'))
```


```
# Topic: NumPy
import numpy as np
a = np.array([1,2,3])
print(a * 2)
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Functions
def add(a, b): return a + b
print(add(3, 4))
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.bar(['A','B'], [10,20])
plt.show()
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.string)
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: Loops
i = 0
while i < 5:
    print(i)
    i += 1
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
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
df = pd.read_csv('data.csv')
print(df.head())
```


```
# Topic: Lists & Tuples
t = (1,2,3)
print(t[1])
```


```
# Topic: Mini Projects
# Palindrome checker
def is_palindrome(s):
 return s == s[::-1]
print(is_palindrome('madam'))
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Basics
x = 7
print('Odd' if x % 2 else 'Even')
```


```
# Topic: File I/O
with open('sample.txt') as f:
    print(f.read())
```


```
# Topic: Dictionaries & Sets
s = {1,2,3}
s.add(4)
print(s)
```


```
# Topic: Loops
i = 0
while i < 5:
    print(i)
    i += 1
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: Basics
a = 5
b = 3
print(a * b)
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Basics
a = 5
b = 3
print(a * b)
```


```
# Topic: NumPy
import numpy as np
print(np.arange(0, 10, 2))
```


```
# Topic: Dictionaries & Sets
s = {1,2,3}
s.add(4)
print(s)
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.bar(['A','B'], [10,20])
plt.show()
```


```
# Topic: Functions
def factorial(n):
    return 1 if n==0 else n * factorial(n-1)
print(factorial(5))
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: Mini Projects
# Palindrome checker
def is_palindrome(s):
 return s == s[::-1]
print(is_palindrome('madam'))
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Functions
def factorial(n):
    return 1 if n==0 else n * factorial(n-1)
print(factorial(5))
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.plot([1,2],[3,4])
plt.show()
```


```
# Topic: Dictionaries & Sets
s = {1,2,3}
s.add(4)
print(s)
```


```
# Topic: Functions
def add(a, b): return a + b
print(add(3, 4))
```


```
# Topic: Functions
def factorial(n):
    return 1 if n==0 else n * factorial(n-1)
print(factorial(5))
```


```
# Topic: Basics
x = 7
print('Odd' if x % 2 else 'Even')
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Basics
a = 5
b = 3
print(a * b)
```


```
# Topic: Lists & Tuples
t = (1,2,3)
print(t[1])
```


```
# Topic: NumPy
import numpy as np
print(np.arange(0, 10, 2))
```


```
# Topic: Dictionaries & Sets
d = {'a':1, 'b':2}
print(d['a'])
```


```
# Topic: Functions
def add(a, b): return a + b
print(add(3, 4))
```


```
# Topic: Recursion
def fib(n):
    if n <= 1: return n
    return fib(n-1) + fib(n-2)
print(fib(5))
```


```
# Topic: NumPy
import numpy as np
a = np.array([1,2,3])
print(a * 2)
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Mini Projects
# Simple calculator
def calc(a,b,op):
 if op=='+': return a+b
 elif op=='-': return a-b
print(calc(10,5,'+'))
```


```
# Topic: Mini Projects
# Simple calculator
def calc(a,b,op):
 if op=='+': return a+b
 elif op=='-': return a-b
print(calc(10,5,'+'))
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head())
```


```
# Topic: Basics
x = 7
print('Odd' if x % 2 else 'Even')
```


```
# Topic: Basics
a = 5
b = 3
print(a * b)
```


```
# Topic: Functions
def factorial(n):
    return 1 if n==0 else n * factorial(n-1)
print(factorial(5))
```


```
# Topic: Classes & Objects
class Dog:
    def bark(self):
        print('Woof!')
d = Dog()
d.bark()
```


```
# Topic: Pandas
import pandas as pd
df = pd.DataFrame({'A':[1,2],'B':[3,4]})
print(df)
```


```
# Topic: File I/O
with open('sample.txt', 'w') as f:
    f.write('Hello World')
```


```
# Topic: Mini Projects
# Palindrome checker
def is_palindrome(s):
 return s == s[::-1]
print(is_palindrome('madam'))
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Loops
i = 0
while i < 5:
    print(i)
    i += 1
```


```
# Topic: Pandas
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head())
```


```
# Topic: Lists & Tuples
t = (1,2,3)
print(t[1])
```


```
# Topic: Matplotlib
import matplotlib.pyplot as plt
plt.bar(['A','B'], [10,20])
plt.show()
```


```
# Topic: Web Scraping
import requests
from bs4 import BeautifulSoup
r = requests.get('https://example.com')
soup = BeautifulSoup(r.text, 'html.parser')
print(soup.title.string)
```


```
# Topic: Dictionaries & Sets
s = {1,2,3}
s.add(4)
print(s)
```


```
# Topic: Decorators
def decorator(fn):
    def wrapper():
        print('Before')
        fn()
        print('After')
    return wrapper
@decorator
def say(): print('Hi')
say()
```


```
# Topic: Mini Projects
# Palindrome checker
def is_palindrome(s):
 return s == s[::-1]
print(is_palindrome('madam'))
```


```
# Topic: Lists & Tuples
t = (1,2,3)
print(t[1])
```


```
# Topic: Loops
for i in range(10): print(i*i)
```


```
# Topic: Exceptions
try:
    print(10/0)
except ZeroDivisionError:
    print('Cannot divide by zero')
```


```
# Topic: Basics
a = 5
b = 3
print(a * b)
```


```
# Topic: Mini Projects
# Palindrome checker
def is_palindrome(s):
 return s == s[::-1]
print(is_palindrome('madam'))
```


---
**Score: 810**