
# Standardization in Machine Learning

## What is Standardization?
Standardization is a feature scaling technique that transforms data to have a mean of 0 and a standard deviation of 1.

## Formula
Z = (X - Mean) / Standard Deviation

## Python Example
```python
from sklearn.preprocessing import StandardScaler

scaler = StandardScaler()
X_scaled = scaler.fit_transform(X)
```

## Learning Goals
- Understand feature scaling
- Learn StandardScaler
- Practice standardization using Python
