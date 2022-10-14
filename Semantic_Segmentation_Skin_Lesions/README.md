# Attention!

Notebook has a lot of visualizations so it doesn't always open on GitHub. Please see [link](https://nbviewer.org/github/troschiev/DS_portfolio/blob/main/Semantic_Segmentation_Skin_Lesions/Semantic_Segmentation_Skin_Lesions.ipynb).

# Semantic Segmentation of Skin Lesions

## Description

The project is dedicated to the semantic segmentation of images of skin defects in micro-photographs.

The task is classification (per pixel).

Target metric - IoU (Jaccard index).

## Stack

Loading, storing and processing data: pytorch dataset/dataloader (tensors), numpy (matrices), cv2 (images)

Visualization: matplotlib

Automation: albumentations

Models: pytorch - manually created architectures like SegNet (based on pre-trained VGG16) and Unet

Individual solutions:

- selection of optimal augmentations
- manual implementation of loss functions, specific to image segmentation tasks
- visualization of the learning process after each epoch, plotting the final comparative graphs

## Data

The [ADDI project](https://www.fc.up.pt/addi/ph2%20database.html) dataset:

- 200 color semantically marked images
- a blank ipynb provided by DL school MIPT was used in the work. The ipynb has been significantly redesigned to suit my needs.

## Conclusions

- 15 models were trained (3 architectures, 5 loss functions), the results are presented in the form of visual graphs. All models were trained to convergence
- a detailed report on the results of the training was written 