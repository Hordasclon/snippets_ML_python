# Starting point
```python
# Input
X = df[['TotalSF']] # pandas DataFrame
# Label
y = df["SalePrice"] # pandas Series
```


# Models
## Linear Regression
```python
# Load the library
from sklearn.linear_model import LinearRegression
# Create an instance of the model
reg = LinearRegression()
# Fit the regressor
reg.fit(X,y)
# Do predictions
reg.predict([[2540],[3500],[4000]])
```


## k-neighbors
## Decision Tree

# Metrics
## MAE
## MAPE
## RMSE
## Correlation
## Bias

# Evaluation
## Train Test Split
## Cross Validation
## Grid Search
## Randomized Search
