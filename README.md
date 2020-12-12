# CNN_EMNIST_Split_mnist_no_fc_model
CNN_EMNIST_Split_mnist_no_fc_model

Convolution Neural Network to detect the EMNIST images.

# Requirements

1. Pytorch Libraries
2. Pytorch Database

# Project Overview

MNIST dataset dataset is available in pytorch torch.utils.data.dataset libraray. CNN model is created to preddict the write image in the dataset.

Features of the model are below:

1. The model has 6 Convolution Layer, 2 maxpooling and 1 Average pooling layer.
2. The model so created does bot have fully connected Neural Network layers.
3. Training works on GPU.
4. Code has calcutaion of Input, Outout and receptive field value for Conv2d layers in the model.
5. Total epochs run for the model are 20.
6. Accuracy of model training is 85%
