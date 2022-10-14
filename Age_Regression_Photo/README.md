# Person Age by Photo

## Description

The project is dedicated to determining the age of a person from a photograph.

The task is regression.

Target metric - MAE.

## Stack

Loading, storing and processing data: pytorch dataset/dataloader (tensors), numpy (matrices), cv2 (images)

Visualization: matplotlib

Automation: albumentations

Models: pytorch, timm - pretrained EfficientNet V2

Alternative solution: ResNet50 in keras

Individual solutions:

- selection of optimal augmentations
- visualization of the learning process after each epoch, plotting the final comparative graphs

## Data

The [ChaLearn Looking at People](https://chalearnlap.cvc.uab.cat/dataset/26/description/) dataset:

- more than 6000 color photographs of people's faces with real age tags

## Conclusions

- selected combination of strong augmentations
- trained model
- the analysis of the model errors is done, it is shown that for the most part the model is mistaken on low-quality photographs