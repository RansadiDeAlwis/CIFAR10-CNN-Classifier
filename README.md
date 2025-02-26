# CIFAR10-CNN-Classifier

This repository contains a project that classifies images from the CIFAR-10 dataset using Convolutional Neural Networks (CNNs). The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class. The goal of this project is to achieve high accuracy in classifying these images.

## Features
- Preprocessing and augmentation of the CIFAR-10 dataset.
- Implementation of a CNN model for image classification.
- Training, validation, and testing of the model.
- Visualization of training metrics and predictions.

## Dataset
The CIFAR-10 dataset contains the following classes:
- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

The dataset can be directly loaded using the `tensorflow.keras.datasets` module.

## Data Preprocessing
The CIFAR-10 dataset consists of 50,000 images used for training and 10,000 images reserved for testing. The training dataset is normalized by dividing the pixel values by 255, as these values typically range from 0 to 255 in most image datasets. This normalization scales the pixel values to a range of 0 to 1, which enhances model convergence and improves overall performance.
