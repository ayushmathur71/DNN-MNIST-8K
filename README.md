# DNN-MNIST-8K
This repository contains DNN models for MNIST dataset classification with less than 8K parameters!

dnn-mnist-8k-v1.ipynb - V1 file contains basic skeleton code with 7.9K params, with batch normalization & basic setup of train/test loaders & train/test functions definitions.

dnn-mnist-8k-v2.ipynb - In the version 2 we add - Global Average Pooling & Regularization (Dropouts) to tackle with overfitting.

dnn-mnist-8k-v3.ipynb - Lastly in version 3 file, we analyse the train dataset again, and add image augmentation/rotation code, correct the maxpool layer location & add a LR schedule to control the decay rate of our learning rate, this helps us achieve 99.4% accuracy in the last few EPOCHS consistently.
