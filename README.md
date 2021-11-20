# Software-Defect-Prediction

This project uses a combination of Deep Learning and Machine Learning to predict software defects.

# Description

A Neural Network is deployed as a feature extractor and an SVM based classifier is used to predict whther the given software has a defect or not.

The model is composed of 6 layers of Dense Network to perform the feature extraction.
All the layers but last uses ReLU activation while the last layer uses a Sigmoid activation function.

The Loss function used here is: Hinge Loss
and an Adam optimizer is used

# Dataset

For this study we have performed analysis on the JM1, AR1, KC2 and MC1 datasets.
