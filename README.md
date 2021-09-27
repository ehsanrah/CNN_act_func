This repository implements a CNN to classify fashion articles fromthe Fashion-MNIST dataset. The neural netwrok architecture is as follows:
Tanh, Sigmoid and relu activation functions are examined as the output and hidden layers activaion functions.
• Input layer: a 28x28x1 image (the 1 specifies a grayscale image)
• First hidden layer: a 2-dimensional convolutional layer with 256 feature maps and a 3x3
filter size with a 30% dropout rate.
• Second hidden layer: a 2x2 max-pooling layer
• Third hidden layer: a 2-dimensional convolutional layerwith 128 featuremaps and a 3x3
filter size with a 30% dropout rate.
• Fourth hidden layer: a 2x2 max-pooling layer
• Fifth hidden layer: a layer to flatten the data
• Sixth hidden layer: A dense (fully-connected) layer consisting of 100 perceptrons
• Seventh hidden layer: A dense (fully-connected) layer consisting of 100 perceptrons
• Output layer (classification probabilites): 10 perceptrons
• Model is trained using 100 epochs.

The accuracy of training and testing with different activation functions on output and hidden layers are compared.