This repository provides a PyTorch implementation of the Adam optimizer as described in the paper Adam: A Method for Stochastic Optimization by Kingma and Ba (2014).

# Overview
Adam is a widely adopted optimization algorithm for training deep learning models. The code is designed to be simple, well-documented, and easy to integrate into your projects.

# Features
+ Simple Integration: Easily plug into any PyTorch model.
+ Customizable: Parameters such as learning rate, betas, epsilon, and weight decay can be adjusted.
+ Clean and Documented: Code is structured with clear comments and documentation for ease of understanding and modification.
+ Installation
  + Clone the repository to your local machine:
    ```
       git clone https://github.com/asra020601/ADAM_OPT.git
       cd ADAM_OPT
    
# Parameters
The optimizer supports the following parameters:
+ lr: Learning rate.
+ betas: A tuple of coefficients used for computing running averages of gradient and its square (default: (0.9, 0.999)).
+ eps: A small constant for numerical stability (default: 1e-8).
+ weight_decay: L2 regularization term (default: 0).

# References
[Adam: A Method for Stochastic Optimization](https://arxiv.org/abs/1412.6980) by D. Kingma and J. Ba
