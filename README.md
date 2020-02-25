# Classfier-using-Perceptron-for-MNIST-dataset


The goal is to implement a multi-class Perceeptron and apply it to the MNIST digits dataset. The data and labels are given. Each row in the data file is 784 integers that represent the grayscale values of a 28x28 handwritten digit. Each row in the labels file is a single digit in the range 0-9 and is in a 1-to-1 correspondence with rows in the data file.
The data is randomly split the data into half for training and half for testing. A multi-class Perceptron is implemented as follows:

There is a weight vector per class (so 10 of them)
The predicted class is the one for which wx is largest using the class-specific vectors
When a prediction is wrong, the weights for the correct class are increased by x and the weights for the incorrectly predicted class
are decreased by x
