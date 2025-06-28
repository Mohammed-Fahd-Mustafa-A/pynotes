---
title: Titanic
date: 2025-06-28
author: Your Name
cell_count: 16
score: 15
---

```python
pip install scikit-learn

```

    Collecting scikit-learn
      Downloading scikit_learn-1.7.0-cp312-cp312-win_amd64.whl.metadata (14 kB)
    Requirement already satisfied: numpy>=1.22.0 in c:\users\hp\miniconda3\envs\py312\lib\site-packages (from scikit-learn) (2.3.1)
    Collecting scipy>=1.8.0 (from scikit-learn)
      Downloading scipy-1.16.0-cp312-cp312-win_amd64.whl.metadata (60 kB)
    Collecting joblib>=1.2.0 (from scikit-learn)
      Downloading joblib-1.5.1-py3-none-any.whl.metadata (5.6 kB)
    Collecting threadpoolctl>=3.1.0 (from scikit-learn)
      Downloading threadpoolctl-3.6.0-py3-none-any.whl.metadata (13 kB)
    Downloading scikit_learn-1.7.0-cp312-cp312-win_amd64.whl (10.7 MB)
       ---------------------------------------- 0.0/10.7 MB ? eta -:--:--
       - -------------------------------------- 0.5/10.7 MB 16.4 MB/s eta 0:00:01
       --- ------------------------------------ 1.0/10.7 MB 2.8 MB/s eta 0:00:04
       ---- ----------------------------------- 1.3/10.7 MB 1.9 MB/s eta 0:00:06
       ---- ----------------------------------- 1.3/10.7 MB 1.9 MB/s eta 0:00:06
       ----- ---------------------------------- 1.6/10.7 MB 1.6 MB/s eta 0:00:06
       ------- -------------------------------- 2.1/10.7 MB 1.6 MB/s eta 0:00:06
       -------- ------------------------------- 2.4/10.7 MB 1.5 MB/s eta 0:00:06
       --------- ------------------------------ 2.6/10.7 MB 1.5 MB/s eta 0:00:06
       --------- ------------------------------ 2.6/10.7 MB 1.5 MB/s eta 0:00:06
       ----------- ---------------------------- 3.1/10.7 MB 1.5 MB/s eta 0:00:05
       ------------ --------------------------- 3.4/10.7 MB 1.5 MB/s eta 0:00:05
       ------------- -------------------------- 3.7/10.7 MB 1.5 MB/s eta 0:00:05
       -------------- ------------------------- 3.9/10.7 MB 1.4 MB/s eta 0:00:05
       --------------- ------------------------ 4.2/10.7 MB 1.4 MB/s eta 0:00:05
       ---------------- ----------------------- 4.5/10.7 MB 1.4 MB/s eta 0:00:05
       ----------------- ---------------------- 4.7/10.7 MB 1.4 MB/s eta 0:00:05
       ------------------ --------------------- 5.0/10.7 MB 1.4 MB/s eta 0:00:05
       ------------------- -------------------- 5.2/10.7 MB 1.4 MB/s eta 0:00:04
       -------------------- ------------------- 5.5/10.7 MB 1.3 MB/s eta 0:00:04
       --------------------- ------------------ 5.8/10.7 MB 1.4 MB/s eta 0:00:04
       ---------------------- ----------------- 6.0/10.7 MB 1.4 MB/s eta 0:00:04
       ----------------------- ---------------- 6.3/10.7 MB 1.3 MB/s eta 0:00:04
       ------------------------ --------------- 6.6/10.7 MB 1.3 MB/s eta 0:00:04
       ------------------------- -------------- 6.8/10.7 MB 1.3 MB/s eta 0:00:03
       -------------------------- ------------- 7.1/10.7 MB 1.3 MB/s eta 0:00:03
       --------------------------- ------------ 7.3/10.7 MB 1.3 MB/s eta 0:00:03
       ---------------------------- ----------- 7.6/10.7 MB 1.3 MB/s eta 0:00:03
       ---------------------------- ----------- 7.6/10.7 MB 1.3 MB/s eta 0:00:03
       ------------------------------ --------- 8.1/10.7 MB 1.3 MB/s eta 0:00:02
       ------------------------------ --------- 8.1/10.7 MB 1.3 MB/s eta 0:00:02
       ------------------------------- -------- 8.4/10.7 MB 1.3 MB/s eta 0:00:02
       --------------------------------- ------ 8.9/10.7 MB 1.3 MB/s eta 0:00:02
       ---------------------------------- ----- 9.2/10.7 MB 1.3 MB/s eta 0:00:02
       ----------------------------------- ---- 9.4/10.7 MB 1.3 MB/s eta 0:00:01
       ----------------------------------- ---- 9.4/10.7 MB 1.3 MB/s eta 0:00:01
       ------------------------------------ --- 9.7/10.7 MB 1.3 MB/s eta 0:00:01
       ------------------------------------- -- 10.0/10.7 MB 1.3 MB/s eta 0:00:01
       ---------------------------------------  10.5/10.7 MB 1.3 MB/s eta 0:00:01
       ---------------------------------------- 10.7/10.7 MB 1.3 MB/s eta 0:00:00
    Downloading joblib-1.5.1-py3-none-any.whl (307 kB)
    Downloading scipy-1.16.0-cp312-cp312-win_amd64.whl (38.4 MB)
       ---------------------------------------- 0.0/38.4 MB ? eta -:--:--
       ---------------------------------------- 0.3/38.4 MB ? eta -:--:--
       ---------------------------------------- 0.3/38.4 MB ? eta -:--:--
        --------------------------------------- 0.5/38.4 MB 1.3 MB/s eta 0:00:30
        --------------------------------------- 0.8/38.4 MB 1.2 MB/s eta 0:00:31
       - -------------------------------------- 1.0/38.4 MB 1.2 MB/s eta 0:00:31
       - -------------------------------------- 1.3/38.4 MB 1.2 MB/s eta 0:00:31
       - -------------------------------------- 1.6/38.4 MB 1.2 MB/s eta 0:00:30
       - -------------------------------------- 1.8/38.4 MB 1.2 MB/s eta 0:00:30
       -- ------------------------------------- 2.1/38.4 MB 1.2 MB/s eta 0:00:30
       -- ------------------------------------- 2.4/38.4 MB 1.2 MB/s eta 0:00:30
       -- ------------------------------------- 2.6/38.4 MB 1.2 MB/s eta 0:00:29
       --- ------------------------------------ 2.9/38.4 MB 1.2 MB/s eta 0:00:29
       --- ------------------------------------ 3.1/38.4 MB 1.2 MB/s eta 0:00:29
       --- ------------------------------------ 3.4/38.4 MB 1.2 MB/s eta 0:00:29
       --- ------------------------------------ 3.7/38.4 MB 1.2 MB/s eta 0:00:29
       ---- ----------------------------------- 3.9/38.4 MB 1.2 MB/s eta 0:00:30
       ---- ----------------------------------- 4.2/38.4 MB 1.2 MB/s eta 0:00:28
       ---- ----------------------------------- 4.5/38.4 MB 1.2 MB/s eta 0:00:28
       ---- ----------------------------------- 4.7/38.4 MB 1.2 MB/s eta 0:00:28
       ----- ---------------------------------- 5.0/38.4 MB 1.2 MB/s eta 0:00:27
       ----- ---------------------------------- 5.2/38.4 MB 1.2 MB/s eta 0:00:28
       ----- ---------------------------------- 5.5/38.4 MB 1.2 MB/s eta 0:00:27
       ------ --------------------------------- 5.8/38.4 MB 1.2 MB/s eta 0:00:28
       ------ --------------------------------- 6.0/38.4 MB 1.2 MB/s eta 0:00:27
       ------ --------------------------------- 6.3/38.4 MB 1.2 MB/s eta 0:00:27
       ------ --------------------------------- 6.6/38.4 MB 1.2 MB/s eta 0:00:26
       ------- -------------------------------- 6.8/38.4 MB 1.2 MB/s eta 0:00:26
       ------- -------------------------------- 7.1/38.4 MB 1.2 MB/s eta 0:00:26
       ------- -------------------------------- 7.3/38.4 MB 1.2 MB/s eta 0:00:26
       ------- -------------------------------- 7.6/38.4 MB 1.2 MB/s eta 0:00:25
       -------- ------------------------------- 7.9/38.4 MB 1.2 MB/s eta 0:00:25
       -------- ------------------------------- 8.1/38.4 MB 1.2 MB/s eta 0:00:25
       -------- ------------------------------- 8.4/38.4 MB 1.2 MB/s eta 0:00:25
       -------- ------------------------------- 8.4/38.4 MB 1.2 MB/s eta 0:00:25
       --------- ------------------------------ 8.9/38.4 MB 1.2 MB/s eta 0:00:24
       --------- ------------------------------ 9.2/38.4 MB 1.2 MB/s eta 0:00:24
       --------- ------------------------------ 9.2/38.4 MB 1.2 MB/s eta 0:00:24
       ---------- ----------------------------- 9.7/38.4 MB 1.2 MB/s eta 0:00:24
       ---------- ----------------------------- 10.0/38.4 MB 1.2 MB/s eta 0:00:23
       ---------- ----------------------------- 10.2/38.4 MB 1.2 MB/s eta 0:00:23
       ---------- ----------------------------- 10.5/38.4 MB 1.2 MB/s eta 0:00:23
       ----------- ---------------------------- 10.7/38.4 MB 1.2 MB/s eta 0:00:23
       ----------- ---------------------------- 11.0/38.4 MB 1.2 MB/s eta 0:00:23
       ----------- ---------------------------- 11.3/38.4 MB 1.2 MB/s eta 0:00:22
       ----------- ---------------------------- 11.3/38.4 MB 1.2 MB/s eta 0:00:22
       ------------ --------------------------- 11.8/38.4 MB 1.2 MB/s eta 0:00:22
       ------------ --------------------------- 12.1/38.4 MB 1.2 MB/s eta 0:00:22
       ------------ --------------------------- 12.3/38.4 MB 1.2 MB/s eta 0:00:22
       ------------- -------------------------- 12.6/38.4 MB 1.2 MB/s eta 0:00:21
       ------------- -------------------------- 12.8/38.4 MB 1.2 MB/s eta 0:00:21
       ------------- -------------------------- 12.8/38.4 MB 1.2 MB/s eta 0:00:21
       ------------- -------------------------- 13.4/38.4 MB 1.2 MB/s eta 0:00:21
       ------------- -------------------------- 13.4/38.4 MB 1.2 MB/s eta 0:00:21
       -------------- ------------------------- 13.6/38.4 MB 1.2 MB/s eta 0:00:21
       -------------- ------------------------- 13.9/38.4 MB 1.2 MB/s eta 0:00:20
       -------------- ------------------------- 14.2/38.4 MB 1.2 MB/s eta 0:00:20
       --------------- ------------------------ 14.4/38.4 MB 1.2 MB/s eta 0:00:20
       --------------- ------------------------ 14.7/38.4 MB 1.2 MB/s eta 0:00:20
       --------------- ------------------------ 14.9/38.4 MB 1.2 MB/s eta 0:00:20
       --------------- ------------------------ 15.2/38.4 MB 1.2 MB/s eta 0:00:19
       ---------------- ----------------------- 15.5/38.4 MB 1.2 MB/s eta 0:00:19
       ---------------- ----------------------- 15.5/38.4 MB 1.2 MB/s eta 0:00:19
       ---------------- ----------------------- 16.0/38.4 MB 1.2 MB/s eta 0:00:19
       ---------------- ----------------------- 16.3/38.4 MB 1.2 MB/s eta 0:00:19
       ----------------- ---------------------- 16.5/38.4 MB 1.2 MB/s eta 0:00:18
       ----------------- ---------------------- 16.8/38.4 MB 1.2 MB/s eta 0:00:18
       ----------------- ---------------------- 17.0/38.4 MB 1.2 MB/s eta 0:00:18
       ------------------ --------------------- 17.3/38.4 MB 1.2 MB/s eta 0:00:18
       ------------------ --------------------- 17.6/38.4 MB 1.2 MB/s eta 0:00:17
       ------------------ --------------------- 17.6/38.4 MB 1.2 MB/s eta 0:00:17
       ------------------ --------------------- 17.8/38.4 MB 1.2 MB/s eta 0:00:17
       ------------------ --------------------- 18.1/38.4 MB 1.2 MB/s eta 0:00:17
       ------------------- -------------------- 18.4/38.4 MB 1.2 MB/s eta 0:00:17
       ------------------- -------------------- 18.6/38.4 MB 1.2 MB/s eta 0:00:17
       ------------------- -------------------- 18.9/38.4 MB 1.2 MB/s eta 0:00:16
       ------------------- -------------------- 19.1/38.4 MB 1.2 MB/s eta 0:00:16
       -------------------- ------------------- 19.4/38.4 MB 1.2 MB/s eta 0:00:16
       -------------------- ------------------- 19.7/38.4 MB 1.2 MB/s eta 0:00:16
       -------------------- ------------------- 19.9/38.4 MB 1.2 MB/s eta 0:00:16
       --------------------- ------------------ 20.2/38.4 MB 1.2 MB/s eta 0:00:15
       --------------------- ------------------ 20.4/38.4 MB 1.2 MB/s eta 0:00:15
       --------------------- ------------------ 20.7/38.4 MB 1.2 MB/s eta 0:00:15
       --------------------- ------------------ 20.7/38.4 MB 1.2 MB/s eta 0:00:15
       ---------------------- ----------------- 21.2/38.4 MB 1.2 MB/s eta 0:00:15
       ---------------------- ----------------- 21.5/38.4 MB 1.2 MB/s eta 0:00:14
       ---------------------- ----------------- 21.5/38.4 MB 1.2 MB/s eta 0:00:14
       ---------------------- ----------------- 22.0/38.4 MB 1.2 MB/s eta 0:00:14
       ----------------------- ---------------- 22.3/38.4 MB 1.2 MB/s eta 0:00:14
       ----------------------- ---------------- 22.5/38.4 MB 1.2 MB/s eta 0:00:13
       ----------------------- ---------------- 22.5/38.4 MB 1.2 MB/s eta 0:00:13
       ----------------------- ---------------- 22.8/38.4 MB 1.2 MB/s eta 0:00:13
       ------------------------ --------------- 23.3/38.4 MB 1.2 MB/s eta 0:00:13
       ------------------------ --------------- 23.6/38.4 MB 1.2 MB/s eta 0:00:13
       ------------------------ --------------- 23.9/38.4 MB 1.2 MB/s eta 0:00:12
       ------------------------ --------------- 23.9/38.4 MB 1.2 MB/s eta 0:00:12
       ------------------------- -------------- 24.4/38.4 MB 1.2 MB/s eta 0:00:12
       ------------------------- -------------- 24.6/38.4 MB 1.2 MB/s eta 0:00:12
       ------------------------- -------------- 24.9/38.4 MB 1.2 MB/s eta 0:00:12
       ------------------------- -------------- 24.9/38.4 MB 1.2 MB/s eta 0:00:12
       -------------------------- ------------- 25.2/38.4 MB 1.2 MB/s eta 0:00:11
       -------------------------- ------------- 25.4/38.4 MB 1.2 MB/s eta 0:00:11
       -------------------------- ------------- 25.7/38.4 MB 1.2 MB/s eta 0:00:11
       -------------------------- ------------- 25.7/38.4 MB 1.2 MB/s eta 0:00:11
       --------------------------- ------------ 26.2/38.4 MB 1.2 MB/s eta 0:00:10
       --------------------------- ------------ 26.5/38.4 MB 1.2 MB/s eta 0:00:10
       --------------------------- ------------ 26.7/38.4 MB 1.2 MB/s eta 0:00:10
       ---------------------------- ----------- 27.0/38.4 MB 1.2 MB/s eta 0:00:10
       ---------------------------- ----------- 27.3/38.4 MB 1.2 MB/s eta 0:00:10
       ---------------------------- ----------- 27.5/38.4 MB 1.2 MB/s eta 0:00:09
       ---------------------------- ----------- 27.8/38.4 MB 1.2 MB/s eta 0:00:09
       ---------------------------- ----------- 27.8/38.4 MB 1.2 MB/s eta 0:00:09
       ----------------------------- ---------- 28.3/38.4 MB 1.2 MB/s eta 0:00:09
       ----------------------------- ---------- 28.6/38.4 MB 1.2 MB/s eta 0:00:09
       ----------------------------- ---------- 28.6/38.4 MB 1.2 MB/s eta 0:00:09
       ------------------------------ --------- 28.8/38.4 MB 1.2 MB/s eta 0:00:08
       ------------------------------ --------- 29.1/38.4 MB 1.2 MB/s eta 0:00:08
       ------------------------------ --------- 29.1/38.4 MB 1.2 MB/s eta 0:00:08
       ------------------------------ --------- 29.4/38.4 MB 1.2 MB/s eta 0:00:08
       ------------------------------ --------- 29.6/38.4 MB 1.2 MB/s eta 0:00:08
       ------------------------------ --------- 29.6/38.4 MB 1.2 MB/s eta 0:00:08
       ------------------------------- -------- 30.1/38.4 MB 1.2 MB/s eta 0:00:07
       ------------------------------- -------- 30.4/38.4 MB 1.2 MB/s eta 0:00:07
       ------------------------------- -------- 30.7/38.4 MB 1.2 MB/s eta 0:00:07
       -------------------------------- ------- 30.9/38.4 MB 1.2 MB/s eta 0:00:07
       -------------------------------- ------- 31.2/38.4 MB 1.2 MB/s eta 0:00:06
       -------------------------------- ------- 31.2/38.4 MB 1.2 MB/s eta 0:00:06
       -------------------------------- ------- 31.5/38.4 MB 1.2 MB/s eta 0:00:06
       --------------------------------- ------ 31.7/38.4 MB 1.2 MB/s eta 0:00:06
       --------------------------------- ------ 32.0/38.4 MB 1.2 MB/s eta 0:00:06
       --------------------------------- ------ 32.2/38.4 MB 1.2 MB/s eta 0:00:06
       --------------------------------- ------ 32.5/38.4 MB 1.2 MB/s eta 0:00:05
       ---------------------------------- ----- 32.8/38.4 MB 1.2 MB/s eta 0:00:05
       ---------------------------------- ----- 33.0/38.4 MB 1.2 MB/s eta 0:00:05
       ---------------------------------- ----- 33.3/38.4 MB 1.2 MB/s eta 0:00:05
       ---------------------------------- ----- 33.6/38.4 MB 1.2 MB/s eta 0:00:05
       ----------------------------------- ---- 33.8/38.4 MB 1.2 MB/s eta 0:00:04
       ----------------------------------- ---- 34.1/38.4 MB 1.2 MB/s eta 0:00:04
       ----------------------------------- ---- 34.3/38.4 MB 1.2 MB/s eta 0:00:04
       ------------------------------------ --- 34.6/38.4 MB 1.2 MB/s eta 0:00:04
       ------------------------------------ --- 34.9/38.4 MB 1.2 MB/s eta 0:00:03
       ------------------------------------ --- 34.9/38.4 MB 1.2 MB/s eta 0:00:03
       ------------------------------------ --- 35.1/38.4 MB 1.2 MB/s eta 0:00:03
       ------------------------------------ --- 35.1/38.4 MB 1.2 MB/s eta 0:00:03
       ------------------------------------- -- 35.7/38.4 MB 1.2 MB/s eta 0:00:03
       ------------------------------------- -- 35.9/38.4 MB 1.2 MB/s eta 0:00:03
       ------------------------------------- -- 35.9/38.4 MB 1.2 MB/s eta 0:00:03
       ------------------------------------- -- 36.4/38.4 MB 1.2 MB/s eta 0:00:02
       ------------------------------------- -- 36.4/38.4 MB 1.2 MB/s eta 0:00:02
       -------------------------------------- - 36.7/38.4 MB 1.2 MB/s eta 0:00:02
       -------------------------------------- - 37.2/38.4 MB 1.2 MB/s eta 0:00:02
       -------------------------------------- - 37.2/38.4 MB 1.2 MB/s eta 0:00:02
       ---------------------------------------  37.7/38.4 MB 1.2 MB/s eta 0:00:01
       ---------------------------------------  38.0/38.4 MB 1.2 MB/s eta 0:00:01
       ---------------------------------------  38.3/38.4 MB 1.2 MB/s eta 0:00:01
       ---------------------------------------- 38.4/38.4 MB 1.2 MB/s eta 0:00:00
    Downloading threadpoolctl-3.6.0-py3-none-any.whl (18 kB)
    Installing collected packages: threadpoolctl, scipy, joblib, scikit-learn
    
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       ---------- ----------------------------- 1/4 [scipy]
       -------------------- ------------------- 2/4 [joblib]
       -------------------- ------------------- 2/4 [joblib]
       ------------------------------ --------- 3/4 [scikit-learn]
       ------------------------------ --------- 3/4 [scikit-learn]
       ------------------------------ --------- 3/4 [scikit-learn]
       ------------------------------ --------- 3/4 [scikit-learn]
       ------------------------------ --------- 3/4 [scikit-learn]
       ------------------------------ --------- 3/4 [scikit-learn]
       ------------------------------ --------- 3/4 [scikit-learn]
       ------------------------------ --------- 3/4 [scikit-learn]
       ------------------------------ --------- 3/4 [scikit-learn]
       ------------------------------ --------- 3/4 [scikit-learn]
       ------------------------------ --------- 3/4 [scikit-learn]
       ------------------------------ --------- 3/4 [scikit-learn]
       ------------------------------ --------- 3/4 [scikit-learn]
       ------------------------------ --------- 3/4 [scikit-learn]
       ------------------------------ --------- 3/4 [scikit-learn]
       ------------------------------ --------- 3/4 [scikit-learn]
       ------------------------------ --------- 3/4 [scikit-learn]
       ------------------------------ --------- 3/4 [scikit-learn]
       ------------------------------ --------- 3/4 [scikit-learn]
       ------------------------------ --------- 3/4 [scikit-learn]
       ------------------------------ --------- 3/4 [scikit-learn]
       ------------------------------ --------- 3/4 [scikit-learn]
       ------------------------------ --------- 3/4 [scikit-learn]
       ------------------------------ --------- 3/4 [scikit-learn]
       ------------------------------ --------- 3/4 [scikit-learn]
       ---------------------------------------- 4/4 [scikit-learn]
    
    Successfully installed joblib-1.5.1 scikit-learn-1.7.0 scipy-1.16.0 threadpoolctl-3.6.0
    Note: you may need to restart the kernel to use updated packages.
    


```python
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LogisticRegression
from sklearn.metrics import accuracy_score, confusion_matrix

```


```python
titanic = sns.load_dataset("titanic")
titanic.head()

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
      <th>survived</th>
      <th>pclass</th>
      <th>sex</th>
      <th>age</th>
      <th>sibsp</th>
      <th>parch</th>
      <th>fare</th>
      <th>embarked</th>
      <th>class</th>
      <th>who</th>
      <th>adult_male</th>
      <th>deck</th>
      <th>embark_town</th>
      <th>alive</th>
      <th>alone</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>0</td>
      <td>3</td>
      <td>male</td>
      <td>22.0</td>
      <td>1</td>
      <td>0</td>
      <td>7.2500</td>
      <td>S</td>
      <td>Third</td>
      <td>man</td>
      <td>True</td>
      <td>NaN</td>
      <td>Southampton</td>
      <td>no</td>
      <td>False</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1</td>
      <td>1</td>
      <td>female</td>
      <td>38.0</td>
      <td>1</td>
      <td>0</td>
      <td>71.2833</td>
      <td>C</td>
      <td>First</td>
      <td>woman</td>
      <td>False</td>
      <td>C</td>
      <td>Cherbourg</td>
      <td>yes</td>
      <td>False</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1</td>
      <td>3</td>
      <td>female</td>
      <td>26.0</td>
      <td>0</td>
      <td>0</td>
      <td>7.9250</td>
      <td>S</td>
      <td>Third</td>
      <td>woman</td>
      <td>False</td>
      <td>NaN</td>
      <td>Southampton</td>
      <td>yes</td>
      <td>True</td>
    </tr>
    <tr>
      <th>3</th>
      <td>1</td>
      <td>1</td>
      <td>female</td>
      <td>35.0</td>
      <td>1</td>
      <td>0</td>
      <td>53.1000</td>
      <td>S</td>
      <td>First</td>
      <td>woman</td>
      <td>False</td>
      <td>C</td>
      <td>Southampton</td>
      <td>yes</td>
      <td>False</td>
    </tr>
    <tr>
      <th>4</th>
      <td>0</td>
      <td>3</td>
      <td>male</td>
      <td>35.0</td>
      <td>0</td>
      <td>0</td>
      <td>8.0500</td>
      <td>S</td>
      <td>Third</td>
      <td>man</td>
      <td>True</td>
      <td>NaN</td>
      <td>Southampton</td>
      <td>no</td>
      <td>True</td>
    </tr>
  </tbody>
</table>
</div>




```python
titanic.info()

```

    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 891 entries, 0 to 890
    Data columns (total 15 columns):
     #   Column       Non-Null Count  Dtype   
    ---  ------       --------------  -----   
     0   survived     891 non-null    int64   
     1   pclass       891 non-null    int64   
     2   sex          891 non-null    object  
     3   age          714 non-null    float64 
     4   sibsp        891 non-null    int64   
     5   parch        891 non-null    int64   
     6   fare         891 non-null    float64 
     7   embarked     889 non-null    object  
     8   class        891 non-null    category
     9   who          891 non-null    object  
     10  adult_male   891 non-null    bool    
     11  deck         203 non-null    category
     12  embark_town  889 non-null    object  
     13  alive        891 non-null    object  
     14  alone        891 non-null    bool    
    dtypes: bool(2), category(2), float64(2), int64(4), object(5)
    memory usage: 80.7+ KB
    


```python
titanic.isnull().sum()

```




    survived         0
    pclass           0
    sex              0
    age            177
    sibsp            0
    parch            0
    fare             0
    embarked         2
    class            0
    who              0
    adult_male       0
    deck           688
    embark_town      2
    alive            0
    alone            0
    dtype: int64




```python
# Fill missing age values with the median
titanic["age"] = titanic["age"].fillna(titanic["age"].median())

# Check if there are still any missing values
titanic["age"].isnull().sum()


```




    np.int64(0)




```python
# Fill missing embarked values with mode
titanic["embarked"] = titanic["embarked"].fillna(titanic["embarked"].mode()[0])

```


```python
# Convert categorical columns into numerical using one-hot encoding
titanic_encoded = pd.get_dummies(titanic, columns=["sex", "embarked", "pclass"], drop_first=True)
titanic_encoded.head()

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
      <th>survived</th>
      <th>age</th>
      <th>sibsp</th>
      <th>parch</th>
      <th>fare</th>
      <th>class</th>
      <th>who</th>
      <th>adult_male</th>
      <th>deck</th>
      <th>embark_town</th>
      <th>alive</th>
      <th>alone</th>
      <th>sex_male</th>
      <th>embarked_Q</th>
      <th>embarked_S</th>
      <th>pclass_2</th>
      <th>pclass_3</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>0</td>
      <td>22.0</td>
      <td>1</td>
      <td>0</td>
      <td>7.2500</td>
      <td>Third</td>
      <td>man</td>
      <td>True</td>
      <td>NaN</td>
      <td>Southampton</td>
      <td>no</td>
      <td>False</td>
      <td>True</td>
      <td>False</td>
      <td>True</td>
      <td>False</td>
      <td>True</td>
    </tr>
    <tr>
      <th>1</th>
      <td>1</td>
      <td>38.0</td>
      <td>1</td>
      <td>0</td>
      <td>71.2833</td>
      <td>First</td>
      <td>woman</td>
      <td>False</td>
      <td>C</td>
      <td>Cherbourg</td>
      <td>yes</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1</td>
      <td>26.0</td>
      <td>0</td>
      <td>0</td>
      <td>7.9250</td>
      <td>Third</td>
      <td>woman</td>
      <td>False</td>
      <td>NaN</td>
      <td>Southampton</td>
      <td>yes</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>False</td>
      <td>True</td>
    </tr>
    <tr>
      <th>3</th>
      <td>1</td>
      <td>35.0</td>
      <td>1</td>
      <td>0</td>
      <td>53.1000</td>
      <td>First</td>
      <td>woman</td>
      <td>False</td>
      <td>C</td>
      <td>Southampton</td>
      <td>yes</td>
      <td>False</td>
      <td>False</td>
      <td>False</td>
      <td>True</td>
      <td>False</td>
      <td>False</td>
    </tr>
    <tr>
      <th>4</th>
      <td>0</td>
      <td>35.0</td>
      <td>0</td>
      <td>0</td>
      <td>8.0500</td>
      <td>Third</td>
      <td>man</td>
      <td>True</td>
      <td>NaN</td>
      <td>Southampton</td>
      <td>no</td>
      <td>True</td>
      <td>True</td>
      <td>False</td>
      <td>True</td>
      <td>False</td>
      <td>True</td>
    </tr>
  </tbody>
</table>
</div>




```python
# Optional: Drop columns that are not useful for prediction
titanic = titanic.drop(columns=["who", "adult_male", "deck", "embark_town", "alive", "class", "alone"], errors='ignore')

# Fill missing values
titanic["age"] = titanic["age"].fillna(titanic["age"].median())
titanic["fare"] = titanic["fare"].fillna(titanic["fare"].median())
titanic["embarked"] = titanic["embarked"].fillna(titanic["embarked"].mode()[0])

# Convert categorical columns to numeric
titanic_encoded = pd.get_dummies(titanic, columns=["sex", "embarked", "pclass"], drop_first=True)

# Define features and label
X = titanic_encoded.drop("survived", axis=1)
y = titanic_encoded["survived"]

```


```python
from sklearn.model_selection import train_test_split

X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2, random_state=42)

from sklearn.linear_model import LogisticRegression

model = LogisticRegression(max_iter=200)
model.fit(X_train, y_train)

```




<style>#sk-container-id-1 {
  /* Definition of color scheme common for light and dark mode */
  --sklearn-color-text: #000;
  --sklearn-color-text-muted: #666;
  --sklearn-color-line: gray;
  /* Definition of color scheme for unfitted estimators */
  --sklearn-color-unfitted-level-0: #fff5e6;
  --sklearn-color-unfitted-level-1: #f6e4d2;
  --sklearn-color-unfitted-level-2: #ffe0b3;
  --sklearn-color-unfitted-level-3: chocolate;
  /* Definition of color scheme for fitted estimators */
  --sklearn-color-fitted-level-0: #f0f8ff;
  --sklearn-color-fitted-level-1: #d4ebff;
  --sklearn-color-fitted-level-2: #b3dbfd;
  --sklearn-color-fitted-level-3: cornflowerblue;

  /* Specific color for light theme */
  --sklearn-color-text-on-default-background: var(--sg-text-color, var(--theme-code-foreground, var(--jp-content-font-color1, black)));
  --sklearn-color-background: var(--sg-background-color, var(--theme-background, var(--jp-layout-color0, white)));
  --sklearn-color-border-box: var(--sg-text-color, var(--theme-code-foreground, var(--jp-content-font-color1, black)));
  --sklearn-color-icon: #696969;

  @media (prefers-color-scheme: dark) {
    /* Redefinition of color scheme for dark theme */
    --sklearn-color-text-on-default-background: var(--sg-text-color, var(--theme-code-foreground, var(--jp-content-font-color1, white)));
    --sklearn-color-background: var(--sg-background-color, var(--theme-background, var(--jp-layout-color0, #111)));
    --sklearn-color-border-box: var(--sg-text-color, var(--theme-code-foreground, var(--jp-content-font-color1, white)));
    --sklearn-color-icon: #878787;
  }
}

#sk-container-id-1 {
  color: var(--sklearn-color-text);
}

#sk-container-id-1 pre {
  padding: 0;
}

#sk-container-id-1 input.sk-hidden--visually {
  border: 0;
  clip: rect(1px 1px 1px 1px);
  clip: rect(1px, 1px, 1px, 1px);
  height: 1px;
  margin: -1px;
  overflow: hidden;
  padding: 0;
  position: absolute;
  width: 1px;
}

#sk-container-id-1 div.sk-dashed-wrapped {
  border: 1px dashed var(--sklearn-color-line);
  margin: 0 0.4em 0.5em 0.4em;
  box-sizing: border-box;
  padding-bottom: 0.4em;
  background-color: var(--sklearn-color-background);
}

#sk-container-id-1 div.sk-container {
  /* jupyter's `normalize.less` sets `[hidden] { display: none; }`
     but bootstrap.min.css set `[hidden] { display: none !important; }`
     so we also need the `!important` here to be able to override the
     default hidden behavior on the sphinx rendered scikit-learn.org.
     See: https://github.com/scikit-learn/scikit-learn/issues/21755 */
  display: inline-block !important;
  position: relative;
}

#sk-container-id-1 div.sk-text-repr-fallback {
  display: none;
}

div.sk-parallel-item,
div.sk-serial,
div.sk-item {
  /* draw centered vertical line to link estimators */
  background-image: linear-gradient(var(--sklearn-color-text-on-default-background), var(--sklearn-color-text-on-default-background));
  background-size: 2px 100%;
  background-repeat: no-repeat;
  background-position: center center;
}

/* Parallel-specific style estimator block */

#sk-container-id-1 div.sk-parallel-item::after {
  content: "";
  width: 100%;
  border-bottom: 2px solid var(--sklearn-color-text-on-default-background);
  flex-grow: 1;
}

#sk-container-id-1 div.sk-parallel {
  display: flex;
  align-items: stretch;
  justify-content: center;
  background-color: var(--sklearn-color-background);
  position: relative;
}

#sk-container-id-1 div.sk-parallel-item {
  display: flex;
  flex-direction: column;
}

#sk-container-id-1 div.sk-parallel-item:first-child::after {
  align-self: flex-end;
  width: 50%;
}

#sk-container-id-1 div.sk-parallel-item:last-child::after {
  align-self: flex-start;
  width: 50%;
}

#sk-container-id-1 div.sk-parallel-item:only-child::after {
  width: 0;
}

/* Serial-specific style estimator block */

#sk-container-id-1 div.sk-serial {
  display: flex;
  flex-direction: column;
  align-items: center;
  background-color: var(--sklearn-color-background);
  padding-right: 1em;
  padding-left: 1em;
}


/* Toggleable style: style used for estimator/Pipeline/ColumnTransformer box that is
clickable and can be expanded/collapsed.
- Pipeline and ColumnTransformer use this feature and define the default style
- Estimators will overwrite some part of the style using the `sk-estimator` class
*/

/* Pipeline and ColumnTransformer style (default) */

#sk-container-id-1 div.sk-toggleable {
  /* Default theme specific background. It is overwritten whether we have a
  specific estimator or a Pipeline/ColumnTransformer */
  background-color: var(--sklearn-color-background);
}

/* Toggleable label */
#sk-container-id-1 label.sk-toggleable__label {
  cursor: pointer;
  display: flex;
  width: 100%;
  margin-bottom: 0;
  padding: 0.5em;
  box-sizing: border-box;
  text-align: center;
  align-items: start;
  justify-content: space-between;
  gap: 0.5em;
}

#sk-container-id-1 label.sk-toggleable__label .caption {
  font-size: 0.6rem;
  font-weight: lighter;
  color: var(--sklearn-color-text-muted);
}

#sk-container-id-1 label.sk-toggleable__label-arrow:before {
  /* Arrow on the left of the label */
  content: "▸";
  float: left;
  margin-right: 0.25em;
  color: var(--sklearn-color-icon);
}

#sk-container-id-1 label.sk-toggleable__label-arrow:hover:before {
  color: var(--sklearn-color-text);
}

/* Toggleable content - dropdown */

#sk-container-id-1 div.sk-toggleable__content {
  display: none;
  text-align: left;
  /* unfitted */
  background-color: var(--sklearn-color-unfitted-level-0);
}

#sk-container-id-1 div.sk-toggleable__content.fitted {
  /* fitted */
  background-color: var(--sklearn-color-fitted-level-0);
}

#sk-container-id-1 div.sk-toggleable__content pre {
  margin: 0.2em;
  border-radius: 0.25em;
  color: var(--sklearn-color-text);
  /* unfitted */
  background-color: var(--sklearn-color-unfitted-level-0);
}

#sk-container-id-1 div.sk-toggleable__content.fitted pre {
  /* unfitted */
  background-color: var(--sklearn-color-fitted-level-0);
}

#sk-container-id-1 input.sk-toggleable__control:checked~div.sk-toggleable__content {
  /* Expand drop-down */
  display: block;
  width: 100%;
  overflow: visible;
}

#sk-container-id-1 input.sk-toggleable__control:checked~label.sk-toggleable__label-arrow:before {
  content: "▾";
}

/* Pipeline/ColumnTransformer-specific style */

#sk-container-id-1 div.sk-label input.sk-toggleable__control:checked~label.sk-toggleable__label {
  color: var(--sklearn-color-text);
  background-color: var(--sklearn-color-unfitted-level-2);
}

#sk-container-id-1 div.sk-label.fitted input.sk-toggleable__control:checked~label.sk-toggleable__label {
  background-color: var(--sklearn-color-fitted-level-2);
}

/* Estimator-specific style */

/* Colorize estimator box */
#sk-container-id-1 div.sk-estimator input.sk-toggleable__control:checked~label.sk-toggleable__label {
  /* unfitted */
  background-color: var(--sklearn-color-unfitted-level-2);
}

#sk-container-id-1 div.sk-estimator.fitted input.sk-toggleable__control:checked~label.sk-toggleable__label {
  /* fitted */
  background-color: var(--sklearn-color-fitted-level-2);
}

#sk-container-id-1 div.sk-label label.sk-toggleable__label,
#sk-container-id-1 div.sk-label label {
  /* The background is the default theme color */
  color: var(--sklearn-color-text-on-default-background);
}

/* On hover, darken the color of the background */
#sk-container-id-1 div.sk-label:hover label.sk-toggleable__label {
  color: var(--sklearn-color-text);
  background-color: var(--sklearn-color-unfitted-level-2);
}

/* Label box, darken color on hover, fitted */
#sk-container-id-1 div.sk-label.fitted:hover label.sk-toggleable__label.fitted {
  color: var(--sklearn-color-text);
  background-color: var(--sklearn-color-fitted-level-2);
}

/* Estimator label */

#sk-container-id-1 div.sk-label label {
  font-family: monospace;
  font-weight: bold;
  display: inline-block;
  line-height: 1.2em;
}

#sk-container-id-1 div.sk-label-container {
  text-align: center;
}

/* Estimator-specific */
#sk-container-id-1 div.sk-estimator {
  font-family: monospace;
  border: 1px dotted var(--sklearn-color-border-box);
  border-radius: 0.25em;
  box-sizing: border-box;
  margin-bottom: 0.5em;
  /* unfitted */
  background-color: var(--sklearn-color-unfitted-level-0);
}

#sk-container-id-1 div.sk-estimator.fitted {
  /* fitted */
  background-color: var(--sklearn-color-fitted-level-0);
}

/* on hover */
#sk-container-id-1 div.sk-estimator:hover {
  /* unfitted */
  background-color: var(--sklearn-color-unfitted-level-2);
}

#sk-container-id-1 div.sk-estimator.fitted:hover {
  /* fitted */
  background-color: var(--sklearn-color-fitted-level-2);
}

/* Specification for estimator info (e.g. "i" and "?") */

/* Common style for "i" and "?" */

.sk-estimator-doc-link,
a:link.sk-estimator-doc-link,
a:visited.sk-estimator-doc-link {
  float: right;
  font-size: smaller;
  line-height: 1em;
  font-family: monospace;
  background-color: var(--sklearn-color-background);
  border-radius: 1em;
  height: 1em;
  width: 1em;
  text-decoration: none !important;
  margin-left: 0.5em;
  text-align: center;
  /* unfitted */
  border: var(--sklearn-color-unfitted-level-1) 1pt solid;
  color: var(--sklearn-color-unfitted-level-1);
}

.sk-estimator-doc-link.fitted,
a:link.sk-estimator-doc-link.fitted,
a:visited.sk-estimator-doc-link.fitted {
  /* fitted */
  border: var(--sklearn-color-fitted-level-1) 1pt solid;
  color: var(--sklearn-color-fitted-level-1);
}

/* On hover */
div.sk-estimator:hover .sk-estimator-doc-link:hover,
.sk-estimator-doc-link:hover,
div.sk-label-container:hover .sk-estimator-doc-link:hover,
.sk-estimator-doc-link:hover {
  /* unfitted */
  background-color: var(--sklearn-color-unfitted-level-3);
  color: var(--sklearn-color-background);
  text-decoration: none;
}

div.sk-estimator.fitted:hover .sk-estimator-doc-link.fitted:hover,
.sk-estimator-doc-link.fitted:hover,
div.sk-label-container:hover .sk-estimator-doc-link.fitted:hover,
.sk-estimator-doc-link.fitted:hover {
  /* fitted */
  background-color: var(--sklearn-color-fitted-level-3);
  color: var(--sklearn-color-background);
  text-decoration: none;
}

/* Span, style for the box shown on hovering the info icon */
.sk-estimator-doc-link span {
  display: none;
  z-index: 9999;
  position: relative;
  font-weight: normal;
  right: .2ex;
  padding: .5ex;
  margin: .5ex;
  width: min-content;
  min-width: 20ex;
  max-width: 50ex;
  color: var(--sklearn-color-text);
  box-shadow: 2pt 2pt 4pt #999;
  /* unfitted */
  background: var(--sklearn-color-unfitted-level-0);
  border: .5pt solid var(--sklearn-color-unfitted-level-3);
}

.sk-estimator-doc-link.fitted span {
  /* fitted */
  background: var(--sklearn-color-fitted-level-0);
  border: var(--sklearn-color-fitted-level-3);
}

.sk-estimator-doc-link:hover span {
  display: block;
}

/* "?"-specific style due to the `<a>` HTML tag */

#sk-container-id-1 a.estimator_doc_link {
  float: right;
  font-size: 1rem;
  line-height: 1em;
  font-family: monospace;
  background-color: var(--sklearn-color-background);
  border-radius: 1rem;
  height: 1rem;
  width: 1rem;
  text-decoration: none;
  /* unfitted */
  color: var(--sklearn-color-unfitted-level-1);
  border: var(--sklearn-color-unfitted-level-1) 1pt solid;
}

#sk-container-id-1 a.estimator_doc_link.fitted {
  /* fitted */
  border: var(--sklearn-color-fitted-level-1) 1pt solid;
  color: var(--sklearn-color-fitted-level-1);
}

/* On hover */
#sk-container-id-1 a.estimator_doc_link:hover {
  /* unfitted */
  background-color: var(--sklearn-color-unfitted-level-3);
  color: var(--sklearn-color-background);
  text-decoration: none;
}

#sk-container-id-1 a.estimator_doc_link.fitted:hover {
  /* fitted */
  background-color: var(--sklearn-color-fitted-level-3);
}

.estimator-table summary {
    padding: .5rem;
    font-family: monospace;
    cursor: pointer;
}

.estimator-table details[open] {
    padding-left: 0.1rem;
    padding-right: 0.1rem;
    padding-bottom: 0.3rem;
}

.estimator-table .parameters-table {
    margin-left: auto !important;
    margin-right: auto !important;
}

.estimator-table .parameters-table tr:nth-child(odd) {
    background-color: #fff;
}

.estimator-table .parameters-table tr:nth-child(even) {
    background-color: #f6f6f6;
}

.estimator-table .parameters-table tr:hover {
    background-color: #e0e0e0;
}

.estimator-table table td {
    border: 1px solid rgba(106, 105, 104, 0.232);
}

.user-set td {
    color:rgb(255, 94, 0);
    text-align: left;
}

.user-set td.value pre {
    color:rgb(255, 94, 0) !important;
    background-color: transparent !important;
}

.default td {
    color: black;
    text-align: left;
}

.user-set td i,
.default td i {
    color: black;
}

.copy-paste-icon {
    background-image: url(data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCA0NDggNTEyIj48IS0tIUZvbnQgQXdlc29tZSBGcmVlIDYuNy4yIGJ5IEBmb250YXdlc29tZSAtIGh0dHBzOi8vZm9udGF3ZXNvbWUuY29tIExpY2Vuc2UgLSBodHRwczovL2ZvbnRhd2Vzb21lLmNvbS9saWNlbnNlL2ZyZWUgQ29weXJpZ2h0IDIwMjUgRm9udGljb25zLCBJbmMuLS0+PHBhdGggZD0iTTIwOCAwTDMzMi4xIDBjMTIuNyAwIDI0LjkgNS4xIDMzLjkgMTQuMWw2Ny45IDY3LjljOSA5IDE0LjEgMjEuMiAxNC4xIDMzLjlMNDQ4IDMzNmMwIDI2LjUtMjEuNSA0OC00OCA0OGwtMTkyIDBjLTI2LjUgMC00OC0yMS41LTQ4LTQ4bDAtMjg4YzAtMjYuNSAyMS41LTQ4IDQ4LTQ4ek00OCAxMjhsODAgMCAwIDY0LTY0IDAgMCAyNTYgMTkyIDAgMC0zMiA2NCAwIDAgNDhjMCAyNi41LTIxLjUgNDgtNDggNDhMNDggNTEyYy0yNi41IDAtNDgtMjEuNS00OC00OEwwIDE3NmMwLTI2LjUgMjEuNS00OCA0OC00OHoiLz48L3N2Zz4=);
    background-repeat: no-repeat;
    background-size: 14px 14px;
    background-position: 0;
    display: inline-block;
    width: 14px;
    height: 14px;
    cursor: pointer;
}
</style><body><div id="sk-container-id-1" class="sk-top-container"><div class="sk-text-repr-fallback"><pre>LogisticRegression(max_iter=200)</pre><b>In a Jupyter environment, please rerun this cell to show the HTML representation or trust the notebook. <br />On GitHub, the HTML representation is unable to render, please try loading this page with nbviewer.org.</b></div><div class="sk-container" hidden><div class="sk-item"><div class="sk-estimator fitted sk-toggleable"><input class="sk-toggleable__control sk-hidden--visually" id="sk-estimator-id-1" type="checkbox" checked><label for="sk-estimator-id-1" class="sk-toggleable__label fitted sk-toggleable__label-arrow"><div><div>LogisticRegression</div></div><div><a class="sk-estimator-doc-link fitted" rel="noreferrer" target="_blank" href="https://scikit-learn.org/1.7/modules/generated/sklearn.linear_model.LogisticRegression.html">?<span>Documentation for LogisticRegression</span></a><span class="sk-estimator-doc-link fitted">i<span>Fitted</span></span></div></label><div class="sk-toggleable__content fitted" data-param-prefix="">
        <div class="estimator-table">
            <details>
                <summary>Parameters</summary>
                <table class="parameters-table">
                  <tbody>

        <tr class="default">
            <td><i class="copy-paste-icon"
                 onclick="copyToClipboard('penalty',
                          this.parentElement.nextElementSibling)"
            ></i></td>
            <td class="param">penalty&nbsp;</td>
            <td class="value">&#x27;l2&#x27;</td>
        </tr>


        <tr class="default">
            <td><i class="copy-paste-icon"
                 onclick="copyToClipboard('dual',
                          this.parentElement.nextElementSibling)"
            ></i></td>
            <td class="param">dual&nbsp;</td>
            <td class="value">False</td>
        </tr>


        <tr class="default">
            <td><i class="copy-paste-icon"
                 onclick="copyToClipboard('tol',
                          this.parentElement.nextElementSibling)"
            ></i></td>
            <td class="param">tol&nbsp;</td>
            <td class="value">0.0001</td>
        </tr>


        <tr class="default">
            <td><i class="copy-paste-icon"
                 onclick="copyToClipboard('C',
                          this.parentElement.nextElementSibling)"
            ></i></td>
            <td class="param">C&nbsp;</td>
            <td class="value">1.0</td>
        </tr>


        <tr class="default">
            <td><i class="copy-paste-icon"
                 onclick="copyToClipboard('fit_intercept',
                          this.parentElement.nextElementSibling)"
            ></i></td>
            <td class="param">fit_intercept&nbsp;</td>
            <td class="value">True</td>
        </tr>


        <tr class="default">
            <td><i class="copy-paste-icon"
                 onclick="copyToClipboard('intercept_scaling',
                          this.parentElement.nextElementSibling)"
            ></i></td>
            <td class="param">intercept_scaling&nbsp;</td>
            <td class="value">1</td>
        </tr>


        <tr class="default">
            <td><i class="copy-paste-icon"
                 onclick="copyToClipboard('class_weight',
                          this.parentElement.nextElementSibling)"
            ></i></td>
            <td class="param">class_weight&nbsp;</td>
            <td class="value">None</td>
        </tr>


        <tr class="default">
            <td><i class="copy-paste-icon"
                 onclick="copyToClipboard('random_state',
                          this.parentElement.nextElementSibling)"
            ></i></td>
            <td class="param">random_state&nbsp;</td>
            <td class="value">None</td>
        </tr>


        <tr class="default">
            <td><i class="copy-paste-icon"
                 onclick="copyToClipboard('solver',
                          this.parentElement.nextElementSibling)"
            ></i></td>
            <td class="param">solver&nbsp;</td>
            <td class="value">&#x27;lbfgs&#x27;</td>
        </tr>


        <tr class="user-set">
            <td><i class="copy-paste-icon"
                 onclick="copyToClipboard('max_iter',
                          this.parentElement.nextElementSibling)"
            ></i></td>
            <td class="param">max_iter&nbsp;</td>
            <td class="value">200</td>
        </tr>


        <tr class="default">
            <td><i class="copy-paste-icon"
                 onclick="copyToClipboard('multi_class',
                          this.parentElement.nextElementSibling)"
            ></i></td>
            <td class="param">multi_class&nbsp;</td>
            <td class="value">&#x27;deprecated&#x27;</td>
        </tr>


        <tr class="default">
            <td><i class="copy-paste-icon"
                 onclick="copyToClipboard('verbose',
                          this.parentElement.nextElementSibling)"
            ></i></td>
            <td class="param">verbose&nbsp;</td>
            <td class="value">0</td>
        </tr>


        <tr class="default">
            <td><i class="copy-paste-icon"
                 onclick="copyToClipboard('warm_start',
                          this.parentElement.nextElementSibling)"
            ></i></td>
            <td class="param">warm_start&nbsp;</td>
            <td class="value">False</td>
        </tr>


        <tr class="default">
            <td><i class="copy-paste-icon"
                 onclick="copyToClipboard('n_jobs',
                          this.parentElement.nextElementSibling)"
            ></i></td>
            <td class="param">n_jobs&nbsp;</td>
            <td class="value">None</td>
        </tr>


        <tr class="default">
            <td><i class="copy-paste-icon"
                 onclick="copyToClipboard('l1_ratio',
                          this.parentElement.nextElementSibling)"
            ></i></td>
            <td class="param">l1_ratio&nbsp;</td>
            <td class="value">None</td>
        </tr>

                  </tbody>
                </table>
            </details>
        </div>
    </div></div></div></div></div><script>function copyToClipboard(text, element) {
    // Get the parameter prefix from the closest toggleable content
    const toggleableContent = element.closest('.sk-toggleable__content');
    const paramPrefix = toggleableContent ? toggleableContent.dataset.paramPrefix : '';
    const fullParamName = paramPrefix ? `${paramPrefix}${text}` : text;

    const originalStyle = element.style;
    const computedStyle = window.getComputedStyle(element);
    const originalWidth = computedStyle.width;
    const originalHTML = element.innerHTML.replace('Copied!', '');

    navigator.clipboard.writeText(fullParamName)
        .then(() => {
            element.style.width = originalWidth;
            element.style.color = 'green';
            element.innerHTML = "Copied!";

            setTimeout(() => {
                element.innerHTML = originalHTML;
                element.style = originalStyle;
            }, 2000);
        })
        .catch(err => {
            console.error('Failed to copy:', err);
            element.style.color = 'red';
            element.innerHTML = "Failed!";
            setTimeout(() => {
                element.innerHTML = originalHTML;
                element.style = originalStyle;
            }, 2000);
        });
    return false;
}

document.querySelectorAll('.fa-regular.fa-copy').forEach(function(element) {
    const toggleableContent = element.closest('.sk-toggleable__content');
    const paramPrefix = toggleableContent ? toggleableContent.dataset.paramPrefix : '';
    const paramName = element.parentElement.nextElementSibling.textContent.trim();
    const fullParamName = paramPrefix ? `${paramPrefix}${paramName}` : paramName;

    element.setAttribute('title', fullParamName);
});
</script></body>




```python
# Predict on the test set
y_pred = model.predict(X_test)

```


```python
from sklearn.metrics import accuracy_score

# Evaluate the model
accuracy = accuracy_score(y_test, y_pred)
print(f"Accuracy: {accuracy:.2f}")

```

    Accuracy: 0.80
    


```python
from sklearn.metrics import classification_report

# Detailed performance report
print(classification_report(y_test, y_pred))

```

                  precision    recall  f1-score   support
    
               0       0.81      0.86      0.83       105
               1       0.78      0.72      0.75        74
    
        accuracy                           0.80       179
       macro avg       0.80      0.79      0.79       179
    weighted avg       0.80      0.80      0.80       179
    
    


```python
from sklearn.metrics import confusion_matrix
import seaborn as sns
import matplotlib.pyplot as plt

# Plot confusion matrix
cm = confusion_matrix(y_test, y_pred)
sns.heatmap(cm, annot=True, fmt="d", cmap="Blues")
plt.xlabel("Predicted")
plt.ylabel("Actual")
plt.title("Confusion Matrix")
plt.show()

```


    
![png](/pynotes/images/titanic_13_0.png)
    



```python
# Show feature importance
coefficients = pd.Series(model.coef_[0], index=X.columns)
coefficients.sort_values().plot(kind='barh', figsize=(10,6), title="Feature Impact on Survival")
plt.tight_layout()
plt.show()

```


    
![png](/pynotes/images/titanic_14_0.png)
    



```python

```


---
**Score: 15**