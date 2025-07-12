# 🐼 Pandas Library - Comprehensive Guide
## Pandas Series
### 1-D labeld array , holding any type of data
#### Creating Series
```python
list = [101,102,103]
arr = np.array([101,102,103])
dictionary = {1:'a', 2: 'b' ,3: 'c'}
labels = ['a','b','c']
```
```python
pd.Series(list)
```
```git
0    101
1    102
2    103
dtype: int64
```
```python
pd.Series(arr,index=labels)
```
```git
a    101
b    102
c    103
dtype: int64
```
## Data Frames
