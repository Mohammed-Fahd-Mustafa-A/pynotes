---
title: Panda
date: 2025-06-29
author: Your Name
cell_count: 16
score: 15
---

```python
import pandas as pd
df = pd.DataFrame({'Name': ['Alice', 'Bob', 'Charlie'], 'Age': [25, 30, 35]})
print(df)
```

          Name  Age
    0    Alice   25
    1      Bob   30
    2  Charlie   35
    


```python
df['Name_Upper'] = df['Name'].str.upper()  # Now works because 'Name' exists
print(df)
```

          Name  Age Name_Upper
    0    Alice   25      ALICE
    1      Bob   30        BOB
    2  Charlie   35    CHARLIE
    


```python
df['Age_Next_Year'] = df['Age'] + 1
print(df)
```

          Name  Age Name_Upper  Age_Next_Year
    0    Alice   25      ALICE             26
    1      Bob   30        BOB             31
    2  Charlie   35    CHARLIE             36
    


```python
young_people = df[df['Age'] < 30]
print(young_people)
```

        Name  Age Name_Upper  Age_Next_Year
    0  Alice   25      ALICE             26
    


```python
print(df.sort_values('Age', ascending=False))
```

          Name  Age Name_Upper  Age_Next_Year
    2  Charlie   35    CHARLIE             36
    1      Bob   30        BOB             31
    0    Alice   25      ALICE             26
    


```python
# Adding a department column for grouping
df['Dept'] = ['HR', 'IT', 'HR']
print(df.groupby('Dept')['Age'].mean())
```

    Dept
    HR    30.0
    IT    30.0
    Name: Age, dtype: float64
    


```python
df['Age_Squared'] = df['Age'].apply(lambda x: x**2)
print(df)
```

          Name  Age Name_Upper  Age_Next_Year Dept  Age_Squared
    0    Alice   25      ALICE             26   HR          625
    1      Bob   30        BOB             31   IT          900
    2  Charlie   35    CHARLIE             36   HR         1225
    


```python
df = df.rename(columns={'Name': 'Full_Name'})
print(df)
```

      Full_Name  Age Name_Upper  Age_Next_Year Dept  Age_Squared
    0     Alice   25      ALICE             26   HR          625
    1       Bob   30        BOB             31   IT          900
    2   Charlie   35    CHARLIE             36   HR         1225
    


```python
df = df.drop(columns=['Age_Squared'])
print(df)
```

      Full_Name  Age Name_Upper  Age_Next_Year Dept
    0     Alice   25      ALICE             26   HR
    1       Bob   30        BOB             31   IT
    2   Charlie   35    CHARLIE             36   HR
    


```python
filtered = df[df['Age'] > 28].reset_index(drop=True)
print(filtered)
```

      Full_Name  Age Name_Upper  Age_Next_Year Dept
    0       Bob   30        BOB             31   IT
    1   Charlie   35    CHARLIE             36   HR
    


```python
print(df.sample(2))  # Random 2 rows
```

      Full_Name  Age Name_Upper  Age_Next_Year Dept
    2   Charlie   35    CHARLIE             36   HR
    1       Bob   30        BOB             31   IT
    


```python
print(df['Dept'].value_counts())
```

    Dept
    HR    2
    IT    1
    Name: count, dtype: int64
    


```python
mask = (df['Age'] > 25) & (df['Dept'] == 'HR')
print(df[mask])
```

      Full_Name  Age Name_Upper  Age_Next_Year Dept
    2   Charlie   35    CHARLIE             36   HR
    


```python
df['Join_Date'] = pd.to_datetime(['2022-01-01', '2021-05-15', '2023-03-10'])
df['Join_Year'] = df['Join_Date'].dt.year
print(df)
```

      Full_Name  Age Name_Upper  Age_Next_Year Dept  Join_Date  Join_Year
    0     Alice   25      ALICE             26   HR 2022-01-01       2022
    1       Bob   30        BOB             31   IT 2021-05-15       2021
    2   Charlie   35    CHARLIE             36   HR 2023-03-10       2023
    


```python
print(df.memory_usage())
```

    Index            132
    Full_Name         24
    Age               24
    Name_Upper        24
    Age_Next_Year     24
    Dept              24
    Join_Date         24
    Join_Year         12
    dtype: int64
    


```python

```


---
**Score: 15**