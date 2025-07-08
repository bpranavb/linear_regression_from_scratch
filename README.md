# Linear Regression with Polynomial Features

This project outlines the foundational principles and a manual implementation of linear regression, diverging from reliance on pre-built libraries like scikit-learn for the core regression logic. It further illustrates the critical role of feature engineering, specifically through the application of polynomial features, in enabling linear models to effectively capture and represent non-linear relationships within datasets.

The included Jupyter Notebook (linear_regression.ipynb) demonstrates this by:

Generating synthetic data based on a quadratic function with added noise.

Implementing a custom LinearRegression class that calculates optimal weights using the Normal Equation.

Applying both a simple linear regression and a polynomial linear regression (where sklearn.preprocessing.PolynomialFeatures is used for feature transformation, but the regression itself remains custom-built).

Visualizing and comparing the true function, the noisy data, the simple linear fit, and the polynomial linear fit to highlight the impact of feature engineering.
