# DNN-MNIST-8K
This repository contains DNN models for MNIST dataset classification with less than 8K parameters!

The first V1 file contains basic skeleton code with 7.9K params, with batch normalization & basic setup of train/test loaders & train/test functions definitions.

V2 file - In the version 2 we add - Global Average Pooling & Regularization (Dropouts) to tackle with overfitting.

V3 file - Lastly we analyse the train dataset again, and add image augmentation/rotation code, correct the maxpool layer location & add a LR schedule to control the decay rate of our learning rate, this helps us achieve 99.4% accuracy in the last few EPOCHS consistently.
