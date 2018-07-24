# isdc-traffic-light-classifier
ISDC Project - Traffic Light Classifier using Python

In this project, I've applied knowledge of computer vision techniques to build a classifier for images of traffic lights in which either the red, yellow or green light is illuminated. 

This project includes the following files:
1. helpers.py - Contains helper function for loading the raw input data.
2. Traffic_Light_Classifier.ipynb - Jupyter notebook that contains all the instructions for the project
3. test_functions.py - Contains code for testing get_speeds, get_x_y and get_headings

Classification Steps
---
### 1. Loading and visualizing the data
The first step in any classification task is to be familiar with the data by loading in the images of traffic lights and visualizing them.
### 2. Pre-processing
The input images and output labels are standardized; that is, all the input should be of the same type of data and of the same size, and the output should be a numerical label. This way, all the input images can be analyzed using the same procedures to know what output to expect when a new image is classified.
### 3. Feature extraction
Extract some features from each image to distinguish and classify them. Features should be 1D vectors or even single values that provide some information about an image that can help classify it as a red, yellow, or green traffic light.
### 4. Classification and visualizing error
A function that uses the features to classify any traffic light image is created. This function takes in an image and outputs a label. Code for classifying a test set of data, comparing the predicted label with the true label, and determining the accuracy of the classification model is provided.
### 5. Evaluate your model
To pass this project, the classifier must be > 90% accurate and never classify any red lights as green
