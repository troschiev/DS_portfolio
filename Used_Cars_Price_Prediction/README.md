# Used Car Price Prediction

## Description

The project is dedicated to predicting the price of a used car according to its characteristics specified by the owner.

The task is regression.

Target metric - RMSE.

## Stack

Loading, storing and processing data: pandas, numpy, phik

Visualization: seaborn, matplotlib

Automation: sklearn, category_encoders, optuna

Models: sklearn linear regression, LightGBM, XGBoost, catboost, pytorch (dense)

Individual solutions:

- data preprocessing and cleaning using domain knowledge
- active use of various ways of encoding categorical variables, in particular, target encoding and its variations. Choice of coding based on the result of cross-validation
- measured the training and inference time of all models, as well as the time of hyperparameters tuning

## Data

The dataset of Yandex Practicum:

- 350,000 entries
- categorical and quantitative features
- there are missing values and outliers (many)

## Conclusions
- it is shown that coding of categorical variables can significantly increase the target metric
- best result obtained using LightGBM with hyperparameter tuning in optuna
- analysis of the residuals showed that most model errors are associated with incorrect information about cars