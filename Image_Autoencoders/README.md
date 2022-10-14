# Image Autoencoders

## Description

The project is dedicated to the implementation of the main ideas of image autoencoders.

The task is to modify images, search for similar images, and generate images.

## Stack

Loading, storing and processing data: pytorch dataset/dataloader (tensors), numpy (matrices)

Visualization: matplotlib, TSNE

Automation: torchvision, sklearn

Models: pytorch - manually created ResNet-like architectures

Individual solutions:

- creation of multilayer convolutional models, including encoder and decoder
- manual implementation of loss functions
- visualization of the learning process after each epoch, plotting the final comparative graphs

## Data

- [Labeled Faces in the Wild Home](http://vis-www.cs.umass.edu/lfw/)
- MNIST
- a blank ipynb provided by DL school MIPT was used in the work. The ipynb has been significantly redesigned to suit my needs.

## Conclusions

Implemented:
- regular autoencoder on faces
    - sampling of random vectors from latent space
    - definition of vectors of "features" of faces, for example, smiles
    - modification of features in photos
    - Image Retrieval - search for faces in the dataset that look like a certain face
- variational autoencoder on MNIST
    - denoising
    - loss as the sum of BCELoss and KL divergence
    - sampling of random vectors from latent space
    - modification: conditional VAE