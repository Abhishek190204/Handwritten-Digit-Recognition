# Handwritten-Digit-Recognition
An artificial neural network to recognize handwritten digits

We have used the MNIST dataset, which consists of 60,000 training images and 10,000 testing images of handwritten digits. The images are grayscale and 28x28 pixels in size.
We first converted the images into a 1D array of 784 pixels and normalized the pixel values between 0 and 1. We also one-hot encoded the target variable (digit label) for training and testing datasets.
We implemented a neural network with two or three hidden layers, each of them having either 100 or 150 neurons depending on the artificial neural network classifier, followed by a SoftMax output layer of 10 neurons (one for each digit class). We have used Tan-Hyperbolic (tanh), Sigmoid, and Rectified Linear Unit (ReLu) activation functions in their respective artificial neural network classifier for the hidden layers and the SoftMax activation function for the output layer. We trained the model using the sparse-categorical cross-entropy loss function and the Adam optimizer.

