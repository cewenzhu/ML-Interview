# ML-Interview
## Models
### 1. Regression
#### 1.1 Linear regression
Find linear relationships between input features and the target variable
##### How it works: 
find optimal w such that y = Xw, where w is the minimizer to the mean squared error.
W can be found using
1. normal equation
> $$w = (X^{T} X) X^{T} y$$
2. Gradient descent:
> $$J(w) =\lVert Xw – y\rVert^{2}$$
> $$w = w – dJ(w)/dw$$

