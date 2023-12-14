# ML Theorie

## Linear Regression and Linear Models

Linear Regression is a statistical approach in machine learning that predicts a continuous outcome based on the linear relationship between the dependent and independent variables.  
Linear Models, including Linear Regression, use a formula involving weighted input features to make predictions, offering simplicity and ease of interpretation.

`continuous outcome`: Numerical values that can take on any value within a range. House Prices, Temperature Forecasting, Stock Prices.  
`dependent variable`: A dependent variable is the outcome that is being measured and analyzed, typically influenced or predicted by one or more independent variables.  
`Independent variable`; 
Independent variables are the factors or inputs that are manipulated or observed to determine their effect on the dependent variable in an experiment or statistical analys.

`residuals`: 
Residuals are the differences between the observed values and the values predicted by machine learning model.

`R-square`: Quantifies the percentage of the variance in the dependent variable that is predictable from the independent variables in a regression model. It provides a measure of how well the model's predictions approximate the real data points, with a value ranging from 0 to 1.
 	
### The Main Ideas of Fitting a Line to Data

Fitting a line to data, commonly done in linear regression, involves finding the best linear relationship between the independent variables (predictors) and the dependent variable (outcome). The main idea is to determine a line that minimizes the difference (usually the sum of squared differences) between the observed values and the values predicted by the line. This process, known as least squares fitting, aims to produce a line that best represents the underlying trend in the data, allowing for prediction and interpretation of relationships between variables.



The lower the sum of residuals the better our prediction line is.

![Description of Image](img/04_07_01_The-Main-Ideas-of-Fitting-a-Line-to-Data.png)

### Linear Regression


Linear regression is distinguished by its assumption of a linear relationship between a dependent variable and one or more independent variables, using a straight line to model this connection. Unlike more complex models, it does not account for non-linear relationships and primarily focuses on predicting continuous outcomes, setting it apart from other models that may handle complex patterns or categorical outputs.

![Description of Image](img/04_07_02_Linear_Regression.png)
