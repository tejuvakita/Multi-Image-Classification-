# Multi-Image-Classification-
This project explains How to build a Sequential Model that can perform Multi Class Image Classification in Python using CNN

## Business Objective

Image classification helps to classify a given set of images as their respective category classes. There are many applications of image classification today, one of them being self-driving cars. An image classification model can be built that recognizes various objects, such as vehicles, people, moving objects, etc., on the road to enable autonomous driving.

There are three main classes of input images in this project, and we need to build a model that can correctly identify a given image. To achieve this, we will be using one of the famous machine learning algorithms used for image classification, i.e., Convolutional Neural Network (or CNN).

 

## Data Description

We will be using a dataset of images categorized into three types, namely the driving license, social security, and others.

The training and testing data each contains these three subfolders. There are around 50 images in each subfolder of testing data, while approximately 200 images in each subfolder of training data.

 

## Aim

To build a sequential model that can perform multiclass classification on a given set of data images.

 

## Tech stack

Language - Python
Libraries - numpy, matplotlib, tensorflow, cv2
 

## Approach

* Importing the required libraries.
* Load and read the data images
* Data Visualization
* Count plot
* Data pre-processing
* Create train and validation data
* Normalize the data
* Reshape the data images
* Data augmentation
* Using ImageDataGenerator
* Model Training
* Create a sequential model
* Add convolution, maxpool,dropout layers
* Add the softmax activation function (As this is a multiclass classification problem)
* Pass the optimizer parameter
* Compile the model
* Fit and train the model
* Check for the predictions
* Save the model in h5 format.
* Inferencing the model
* Prediction on the test data
