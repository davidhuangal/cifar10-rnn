# CIFAR-10 Convolutional Neural Network

## Overview
This code trains a convolutional neural network on the CIFAR-10 image dataset. Uses the [Keras](https://keras.io/) and [NumPy](http://www.numpy.org/) libraries.

## Architecture
 INPUT -> [CONV -> RELU -> CONV -> RELU -> POOL]*3 -> [FC -> RELU]*2 -> FC
 
 As per suggestion by Stanford's [CS231n](http://cs231n.github.io/convolutional-networks/#architectures)

## Accuracy
This model has achieved 70.89% test accuracy on the CIFAR-10 dataset with batch size of 128 and 30 epochs.

Maybe not so impressive, but it was fun to build.

## Dependencies

```sudo pip3 install -r requirements.txt```

## Usage
```python3 c10cnn.py```
