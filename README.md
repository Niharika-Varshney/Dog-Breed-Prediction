# Dog Breed Prediction

This repository contains a project for predicting dog breeds from images using a Convolutional Neural Network (CNN) implemented with TensorFlow. The dataset used in this project is sourced from the Kaggle Dog Breed Identification competition.


## Overview
The goal of this project is to accurately classify images of dogs into one of 120 different breeds using deep learning techniques. The solution involves preprocessing the image data, building and training a CNN, and evaluating the model's performance.

## Libraries Used
- **Tensorflow**
- **NumPy**
- **Pandas**
- **Matplotlib**

## Installation
To get started, clone the repository and install the necessary dependencies:
<br>
```git clone https://github.com/Niharika-Varshney/Dog-Breed-Prediction```
<br>
```cd Dog-Breed-Prediction```


## Data Preparation
Download the dataset from here [https://www.kaggle.com/c/dog-breed-identification/data].
<br>
**File descriptions**
- ```train.zip``` - the training set, you are provided the breed for these dogs
- ```test.zip``` - the test set, you must predict the probability of each breed for each image
- ```sample_submission.csv``` - a sample submission file in the correct format
- ```labels.csv``` - the breeds for the images in the train set


## Results
The model achieves a validation accuracy of approximately 90%. Performance can be further enhanced by experimenting with different architectures, optimizers, and data augmentation techniques.
