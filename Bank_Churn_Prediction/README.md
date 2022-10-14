# Bank Customer Churn

## Description

The project is dedicated to identifying bank customers who are inclined to leave for another organization.

The task is classification.

Target metric - F1.

## Stack

Loading, storing and processing data: pandas, numpy

Visualization: seaborn, t-SNE, matplotlib

Automation: sklearn pipeline, selection of optuna hyperparameters

Models: sklearn, XGBoost, LightGBM

Individual solutions:

- a universal wrapper class for a classifier with a custom threshold
- determination of the optimal classification threshold by cross-validation
- determination of the feature importances by permutations
- blending models

## Data

Used [dataset](https://www.kaggle.com/datasets/barelydedicated/bank-customer-churn-modeling):

- 10,000 entries
- numerical and categorical features
- there are missing values
- no outliers

## Conclusions

- t-SNE visualization was performed, showing that the problem has no trivial solutions and it is necessary to use machine learning models
- 9 models trained, 3 best selected and blended
- best result obtained using XGBoost
- the best method of dealing with class imbalance was the simultaneous balancing of weights and the selection of the classification threshold