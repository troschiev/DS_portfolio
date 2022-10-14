# Simpsons Classification

## Description

The project is dedicated to the identification of The Simpsons characters on images.

The task is multiclass classification.

Target metric - F1.

## Stack

Loading, storing and processing data: pytorch dataset/dataloader (tensors), numpy (matrices), PIL (images)

Visualization: matplotlib

Automation: torchvision

Models: pytorch - ResNeXt50

Individual solutions:

- selection of optimal augmentations
- adding weights to the loss function to compensate for strong class imbalance
- unfreezing network layers as you tune

## Data

The dataset of the [Journey to Springfield competition](https://www.kaggle.com/competitions/journey-springfield):

- about 20000 color images with class labels
- strong imbalance of classes (the rarest class is about 1000 times rarer than the most frequent)
- a blank ipynb provided by DL school MIPT was used in the work. The ipynb has been significantly redesigned to suit my needs.

## Conclusions

- based on the pre-trained ResNeXt50 network, a classifier was created and trained
- quality on the test sample was 0.984