# Handwritten Digit Classifier

## Description
The project aims to develop a handwritten digit classifier using neural networks and deep learning with
1. PyTorch
2. NumPy
## Data
The MNIST database of handwritten digits, available from [this page](http://yann.lecun.com/exdb/mnist/), has a training set of 60,000 examples, and a test set of 10,000 examples. It is a subset of a larger set available from NIST. The digits have been size-normalized and centered in a fixed-size image.

## Results


| Train samples | Test samples | Architecture | Library | Test Accuracy |
| ------------- | ------------ | ------------ | ------- | ------------- |
| 60000         | 10000        | LeNet-5      | PyTorch | 98%           |
| 20000         | 5000         | Vanilla NN   | NumPy   | 82%           |
