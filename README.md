# Pruning-Tensorflow

This repository consists of the an implementation of model weight pruning and fully connected layers pruning of a convolutional neural networks in tensforflow.

The Jupyter Notebook contains two functions:

1. weight_pruning(modelPruning, pruning_rate): this function takes a tensorflow/keras CNN model with a pruning rate between 0 and 1. It performs weights pruning with a rate of pruning_rate over the whole model and returns a pruned, smaller model.

2. FC_pruning(model_FC_pruning, k): this function takes a tensorflow/keras CNN model with a pruning rate between 0 and 1. It performs pruning over the fully connected layers with a rate of k. It returns a pruned, smaller model with pruned FC layers.

### Contact
kassem.kallas@inria.fr

### Requirements
tensorflow

numpy

keras


