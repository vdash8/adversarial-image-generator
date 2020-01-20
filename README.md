# Adversarial Image Generator

A simple project that "attacks" a neural network by generating an input that the network misclassifies. To generate such an input, this notebook uses the fast gradient sign method (FGSM) on the pre-trained ResNet50 neural network provided by keras. An explanation of FGSM can be found [here](https://arxiv.org/pdf/1412.6572.pdf)