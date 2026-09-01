# Elevate Labs AI & ML Internship - Task 3

## Objective
This repository contains the code for Task 3: Linear Regression. The objective was to implement and understand both simple and multiple linear regression using Scikit-learn, Pandas, and Matplotlib.

## Process
1. Imported and preprocessed the housing dataset.
2. Split the data into an 80/20 train-test split.
3. Fit a Multiple Linear Regression model using `sklearn.linear_model`.
4. Evaluated the model's performance using MAE, MSE, and the R-squared score.
5. Plotted the actual vs. predicted prices and interpreted the feature coefficients.

## Interview Questions & Answers
1. **What assumptions does linear regression make?** It assumes a linear relationship between features and the target, independence of errors, constant variance of residuals (homoscedasticity), and normally distributed errors.
2. **How do you interpret the coefficients?** A coefficient represents the expected change in the target variable for a one-unit change in that specific independent variable, assuming all other variables are held constant.
3. **What is the R-squared score and its significance?** It is a statistical measure that represents the proportion of the variance in the dependent variable that is explained by the independent variables. A score closer to 1.0 indicates a better fit.
4. **When would you prefer MSE over MAE?** You prefer Mean Squared Error (MSE) when you want to heavily penalize large errors or outliers, because squaring the errors gives exponentially higher weight to larger differences.
5. **How do you detect multicollinearity?** By generating a correlation matrix to spot highly correlated independent variables, or by calculating the Variance Inflation Factor (VIF).
6. **What is the difference between simple and multiple regression?** Simple regression uses only one independent variable to predict the target, whereas multiple regression uses two or more independent variables.
7. **Can linear regression be used for classification?** No, linear regression is designed to predict continuous numerical values. Logistic regression is the appropriate algorithm for classification tasks.
8. **What happens if you violate regression assumptions?** The model's predictions become unreliable, the standard errors of the coefficients may be biased, and any confidence intervals or hypothesis tests will be invalid.
