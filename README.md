# Linear-Regression-

Linear regression performs a regression task on a target variable based on independent variables in a given data. It is a machine learning algorithm and is often used to find the relationship between the target and independent variables.

The __Simple Linear Regression model__ is to predict the target variable using one independent variable.

When one variable/column in a dataset is not sufficient to create a good model and make more accurate predictions, we’ll use a multiple linear regression model instead of a simple linear regression model

The line equation for the multiple linear regression model is:
```y = β0 + β1X1 + β2X2 + β3X3 + ....+ βpXp + e```

Before proceeding further on
building the model using python,
we need to consider some things:
1. Adding more variables isn’t
always helpful because the
model may ‘over-fit,’ and it’ll be
too complicated. The trained
model doesn’t generalize with
the new data. It only works on
the trained data.
2. All the variables/columns in the
dataset may not be independent.
This condition is called
multicollinearity , where there
is an association between
predictor variables.
3. We have to select the
appropriate variables to build
the best model. This process of
selecting variables is called
Feature selection 
