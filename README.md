# Simple Convolutional Neural Network 

In this script, a simple convolutional neural network is developed with the following architecture: 32x32x1 input image (greyscale), 28x28x5 convolution layer (5x5 filter), 14x14x5 max pooling layer, followed by two dense layers (120 / 10 output neurons). 
The hidden neurons use a sigmoid activation function, and the final output layer has a soft-max prediction with a cross-entropy loss function. The network is trained using stochastic gradient descent. In this example, the MNIST handwritten data set is used to show the effectiveness of the network.
