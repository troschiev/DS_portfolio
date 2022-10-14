# Taxi Demand Time Series

## Description

The project is dedicated to predicting the taxi orders number time series.

The task is to regress the time series 1 step forward.

Target metric - RMSE.

## Stack

Loading, storing and processing data: pandas, numpy, phik

Working with time series: statsmodels, pmdarima, prophet

Visualization: seaborn, matplotlib, built-in library methods for time series processing

Automation: sklearn, category_encoders

Generic models: sklearn linear regression, LightGBM, pytorch (architectures: dense, LSTM), lineartree

Individual solutions:

- automated feature engineering and selection for classical ML models
- a forecast was obtained for the entire test sample with models capable of predicting many steps ahead 
- a hybrid boosting model was used, which combines the advantages of linear models (stability) and gradient boosting

## Data

The dataset of Yandex Practicum:

- 26,000 time series records with dates
- no missing values and outliers

## Conclusions

- trained all the main models used for forecasting time series, including:
  - exponential smoothing
  - linear regression on lagged features
  - gradient boosting on selected features
  - SARIMA
  - Prophet (ready-made library for working with time series)
  - fully connected neural network
  - LSTM
- it is shown that models specifically designed for time series, such as exponential smoothing and SARIMA, provide the best result
- at the same time, linear regression with a large number of lag variables also provides a great result when predicting 1 step ahead