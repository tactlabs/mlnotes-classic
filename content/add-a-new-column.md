---
title: "add-a-new-column"
author: "TactLabs"
type: article
draft: false
--- 

```python
import pandas as pd
```


```python
data = {
    'city' : ['Toronto', 'Montreal', 'Waterloo'],
    'points' : [80, 70, 90]
}
```


```python
data
```




    {'city': ['Toronto', 'Montreal', 'Waterloo'], 'points': [80, 70, 90]}




```python
type(data)
```




    dict




```python
df = pd.DataFrame(data)
```


```python
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
      <th>city</th>
      <th>points</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Toronto</td>
      <td>80</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Montreal</td>
      <td>70</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Waterloo</td>
      <td>90</td>
    </tr>
  </tbody>
</table>
</div>




```python
df = df.assign(code = [1, 2, 3])
```


```python

```
