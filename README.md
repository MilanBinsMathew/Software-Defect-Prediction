# Software-Defect-Prediction-JM1

This project uses the dataset JM1 to predict software defects using Artificial Neural Networks

# Link to Dataset:
https://datahub.io/machine-learning/jm1/r/0.html

# Description
The program uses the metrics provided in the JM1 dataset to predict software defects.
The model of this program uses 6 fully connected layers with hidden nodes of 21, 16, 8, 4, and 1 respectively.
All the layers but last uses ReLU activation while the last layer uses a Sigmoid activation function.

The Loss function used here is: Binary Cross Entropy
and an Adam optimizer is used
