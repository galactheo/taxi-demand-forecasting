# Taxi Demand Forecasting

A time series forecasting project completed as part of the TripleTen Data Science bootcamp. The goal is to predict the number of taxi orders for the next hour and help plan driver availability during busy periods.

## Project Overview

The analysis focuses on:

- Preparing historical taxi order data and aggregating it into hourly totals.
- Exploring demand trends and daily seasonality.
- Creating time-based, lag, and rolling-average features.
- Comparing Linear Regression, Decision Tree, and Random Forest models using chronological data splits.
- Evaluating the final model using RMSE.

🛠️ **Tools:** Python, Pandas, NumPy, Matplotlib, Scikit-learn, Statsmodels

## Key Findings

- Taxi demand shows a gradual upward trend and recurring daily patterns.
- Linear Regression achieved the lowest validation RMSE (**27.13**) among the models tested.
- The final model reached a test RMSE of **35.46**, meeting the project's target of less than 48.
