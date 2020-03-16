# Problem to find companys spend's more on which Department

## Importing packages

```python
import pandas as pd
import numpy as np
from sklearn.linear_model import LinearRegression
from sklearn.model_selection import train_test_split
from sklearn.metrics import r2_score
```

## Preprocess Check

This Dataset has no nan Value

In this dataset it contain only one colume with categorical variable 
For that i'm encoding that column(State) using One Hot COde

```bash
data = pd.get_dummies(data, columns= ['State'], prefix = 'state', drop_first= True)
```

```bash
Using OLS i'm exposing which Feature has more spend
```


