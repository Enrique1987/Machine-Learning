# ML Theorie

## Linear Regression and Linear Models

`Linear Regression`: is a statistical approach in machine learning that predicts a continuous outcome based on the linear relationship between the dependent and independent variables.  
Linear Models, including Linear Regression, use a formula involving weighted input features to make predictions, offering simplicity and ease of interpretation.

`continuous outcome`: Numerical values that can take on any value within a range. House Prices, Temperature Forecasting, Stock Prices.  

`dependent variable`: A dependent variable is the outcome that is being measured and analyzed, typically influenced or predicted by one or more independent variables. 

`Independent variable`: Independent variables are the factors or inputs that are manipulated or observed to determine their effect on the dependent variable in an experiment or statistical analys.

`residuals`: Residuals are the differences between the observed values and the values predicted by machine learning model.

`t-tests`: A t-test is a statistical test used to compare the means of two groups to determine if there is a significant difference between them. It's commonly used in hypothesis testing to assess whether any observed differences in sample means are due to chance or reflect true differences in the populations.

`ANOVA`: Analysis of Variance, is a statistical method used to compare the means of three or more groups to determine if there are any statistically significant differences among them. It generalizes the t-test to more than two groups, analyzing the variance within and between groups to assess whether any observed differences are due to chance or reflect true differences in the populations.

`Fitting a line`:commonly done in linear regression, involves finding the best linear relationship between the independent variables (predictors) and the dependent variable (outcome). The main idea is to determine a line that minimizes the difference (usually the sum of squared differences) between the observed values and the values predicted by the line. This process, known as least squares fitting, aims to produce a line that best represents the underlying trend in the data, allowing for prediction and interpretation of relationships between variables. The lower the sum of residuals the better our prediction line is.

`Multiple Regression`: Is a statistical technique that models the relationship between a single dependent variable and two or more independent variables. It extends the concept of linear regression by incorporating multiple predictors, allowing for more complex analysis of how various factors simultaneously affect the outcome.

`R-squared`: Measures how well one variable predicts another. The statistically significan R-squared was 0.9 -> Very good the relathionship between the two variables explains the 90% of the variation in the data!

#### Why R-squared and not just plain R ?
 Its not obvious that (regular) R = 0.7 is twice as good as R = 0.5