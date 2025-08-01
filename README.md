MNIST Digit Recognition using a Neural Network:
This repository contains code for a simple neural network to recognize handwritten digits from the MNIST dataset. The model is built using TensorFlow and Keras.

Model Architecture:
The model consists of the following layers:

A Flatten layer to convert the 28x28 pixel images into a 1D array.
A Dense layer with 128 neurons and a ReLU activation function.
A Dense layer with 32 neurons and a ReLU activation function.
A Dense output layer with 10 neurons (one for each digit) and a softmax activation function.
