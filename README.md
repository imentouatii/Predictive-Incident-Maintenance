# Predictive Maintenance with Deep Learning
This project uses deep learning to predict equipment failures in a manufacturing plant based on sensor data.

## <b>Table of Contents</b>
<h3>&#x2022; Dataset<br>
<h3>&#x2022; Methods<br>
<h3>&#x2022; Usage <br>
<h3>&#x2022; Concluion


## <b>1. Introduction </b>
Equipment failures in a manufacturing plant can lead to costly downtime and lost productivity. Predictive maintenance using machine learning can help to identify potential equipment failures before they occur, allowing for scheduled maintenance to prevent breakdowns.

The data set used for this project contains sensor measurements from a variety of manufacturing equipment, along with information about whether the equipment eventually failed. The goal of this project is to use deep learning to predict equipment failures based on sensor data.

## <b> 2.Dataset </b>
 The data set used for this project is sourced from the UCI Machine Learning Repository, which can be found at the following link:

<h3>&#x2022; https://archive.ics.uci.edu/ml/machine-learning-databases/00601/ai4i2020.csv

The data set contains sensor measurements from 10 different machines in a manufacturing plant, as well as information about whether the machine eventually failed. There are 8 input variables that describe the sensor measurements and 1 output variable that classifies the machines as either "working" or "failed". There are 10,000 samples in the data set.

## <b>3. Methods </b>
For this project, we used a deep neural network to predict equipment failures based on sensor data. The neural network architecture consists of the following layers:

1. Input layer with 6 nodes
2. Two hidden layers with 5 and 4 nodes respectively
1. Output layer with 1 node and sigmoid activation function

We trained the network using binary cross-entropy loss and the Adam optimizer.

## <b> 4. Conclusion </b>
In this project, we used deep learning to predict equipment failures based on sensor data from a manufacturing plant. The model achieved an accuracy of 0.94 on the test set, demonstrating the potential of machine learning in predictive maintenance.