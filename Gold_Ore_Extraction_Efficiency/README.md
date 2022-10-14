# Gold Recovery Efficiency Model

## Description

The project is dedicated to the analysis of gold ore purification technology.

The task is regression.

The target metric is sMAPE.

## Stack

Loading, storing and processing data: pandas, numpy, phik

Visualization: seaborn

Automation: sklearn pipeline, selection of optuna hyperparameters

Models: sklearn, XGBoost

Individual solutions:

- soft cleaning of outliers
- search for sets of correlated features and their combination by PCA
- creating own class for cross-validation with different processing of the training and validation samples

## Data

Real data from the gold mining industry, provided by Yandex Practicum:

- 20,000 entries
- 86 numeric features
- many missing values and outliers
- the distribution of features in the test sample differs from the training one

## Conclusions

- in-depth feature analysis with multiple visualizations
- best regression result obtained using XGBoost after feature space dimensionality reduction
- gained invaluable experience working with "raw" data that require careful pre-processing