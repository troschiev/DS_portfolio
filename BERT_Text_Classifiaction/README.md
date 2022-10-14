# Toxic Comment Classification

## Description

The project is dedicated to creating a model that defines toxic comments on Wikipedia edits.

The task is classification.

Target metric - F1.

## Stack

Loading, storing and processing data: pandas, pytorch dataset/dataloader, numpy

Visualization: seaborn, matplotlib, wordcloud

Automation: sklearn pipeline, optuna

Models: sklearn logistic regression & naive Bayes, catboost, BERT (Hugging Face)

Text processing: nltk, enchant, spacy, gensim

Individual solutions:

- "soft" text cleaning for BERT operation
- class imbalance: class weights in the loss function, adjustment of the classification threshold on the validation set

## Data

The dataset of Yandex Practicum:

- 160,000 tagged entries in English
- class imbalance 9 to 1

## Conclusions

- best result by fine-tuned BERT classifier trained for only 2 epochs with low LR
- second result - for logistic regression on TF-IDF features after text lemmatization