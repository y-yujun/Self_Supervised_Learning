# Self-supervised Learning
A simple self-supervised rotation prediction task to pretrain a feature representation on the CIFAR10 dataset without using class labels, and then fine-tune this representation for CIFAR10 classification.

## Details
The .ipynb file includes tasks like:
* training a ResNet18 on the rotation task, 
* finetuning only the weights of the final block of convolutional layers and linear layer on the supervised CIFAR10 classification task (initialization from the rotation model and from random weights), and
* training the full network on the supervised CIFAR10 classification task (initialization from the rotation model and from random weights).

## References
* Paper: https://arxiv.org/pdf/1803.07728
