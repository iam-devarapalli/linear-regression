# Linear-Regression

Linear regression is a simple and widely used machine learning algorithm that provides a foundation for understanding more advanced techniques. It models the linear relationship between one or more independent variables (X) and a continuous dependent variable (Y) to make predictions.

# Key Concepts: 
Dependent Variable (Y): The variable we want to predict, also known as the target variable.

Independent Variables (X): Features used to predict the dependent variable.

Supervised Learning: Since both X and Y are known, linear regression falls under supervised learning.

<img width="681" height="181" alt="Screenshot 2026-10-18 at 12 34 00 PM" src="https://github.com/user-attachments/assets/469cfeec-1c5a-452a-bfc6-61bd3166afda" />

# Learning Objectives:

Understand the basic concept of linear regression.

Implement linear regression using a dataset.

Learn about the importance of model evaluation through metrics like R-squared.

# Linear Regression Types:
## Simple Linear Regression: 
There is only one independent variable affecting a dependent variable. The relationship can be expressed as: 
Y = mX + c
Where: 
m is the slope of the line (coefficient)
c is the y-intercept.

The algorithm tries to find the best-fit line that best predicts Y from X.

Uses one input feature, Example: Predict house price from area.


## Multiple Linear Regression: 

If there are two or more independent variables, it's referred to as multiple linear regression. 

The equation becomes:  Y = W0 + W1X1 + W2X2 +...+WnXn
W is a coefficient for the respective feature X.

Uses multiple input features, Example: Predict house price from area, bedrooms, and age.

## Main project steps: 
1. Load and explore the dataset.
2. Split data into training and test sets.
3. Handle missing values and encode categorical features using training data.
4. Train the regression model.
5. Evaluate predictions using MAE, MSE, RMSE, and R².
6. Inspect residuals and check model assumptions.
   
## Important assumptions
- The conditional mean of the target is linear in the model parameters.
- Errors are independent and have zero conditional mean.
- Errors have constant variance for standard inference.
- Features have no perfect multicollinearity.
- Normally distributed errors support exact small-sample confidence intervals and hypothesis tests; normality is not required simply to fit the model.

## Advantages and limitations
Advantages: Simple, interpretable, fast, and useful as a baseline model.

Limitations: Sensitive to outliers, affected by correlated features, and may underfit nonlinear relationships. Predictions outside the training data’s range can be unreliable.
