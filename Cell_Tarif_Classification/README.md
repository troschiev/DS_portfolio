# Tariff Recommendation for a Mobile Operator Client

## Description

The project is dedicated to the classification of mobile operator users based on their activity.

The task is classification.

The target metric is accuracy.

## Tools

Loading, storing and processing data: pandas, numpy

Visualization: seaborn, matplotlib

Automation: sklearn

Models: sklearn (LR, RF, KNN, SVM, NB, Tree), XGBoost

Individual solutions:

- feature engineering, which greatly inreased linear model quality
- study of the influence of model hyperparameters on the quality metric
- determination of features importances L1 regularization
- models blending

## Data

The dataset of Yandex Practicum was used:

- 3000+ entries
- numerical features
- no missing values and outliers

## Conclusions

- 10 models were trained and blended
- model hyperparameters were selected using cross-validation
- the best result was obtained using blending