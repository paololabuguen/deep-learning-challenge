# deep-learning-challenge

## Overview

Given the dataset, we want to create a neural network model to predict successful charities funded by Alphabet Soup.

## Results

### Data Preprocessing

The target of the data is the IS_SUCCESSFUL column and everything else but the identifying columns would be the features.
Some columns are also binned in order to reduce the amount of inputs.

### Compiling, Training and Evaluating the Model

Before trying to optimize, there were 2 hidden layers, the first had 80 neurons with the activation function RELU.
The second layer had 30 neurons with the activation function tanh and an output layer with the activation function sigmoid.
When we trained our model with the dataset, the accuracy was about 73%.

The optimization process had me changing a lot of things such as adding more layers, changing number of neurons and also
removing some rows. However, the accuracy stayed about the same at around 73%.

## Summary

Although I was not able to achieve more than 75% accuracy with the model, we could explore using different models such
as logistic regression since there are only 2 possible choices for outputs which are either success or fail.
