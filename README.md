Project Title

Effect of Weight Initialization Scale on Neural Network Convergence

Overview

This project investigates how the variance of initial neural network weights affects convergence speed, training stability, and final accuracy. Four initialization scales (σ = 0.01, 0.1, 0.5, 1.0) were compared using identical architectures and hyperparameters.

Dataset

MNIST handwritten digits (60k train, 10k test), normalized and flattened to 784 features.

Experiments

A fully connected network with two hidden layers was trained separately for each initialization scale. Training loss, accuracy curves, and final test accuracy were collected.

Key Findings

σ = 0.1 converged fastest and achieved highest accuracy.

σ = 0.01 suffered from vanishing gradients.

σ = 1.0 showed unstable gradients early in training.

Moderate variance yields the best generalization.

Repository Structure

Mohan.ipynb

https://github.com/Mohan-Mj2312/Machine-Learning.git

/notebooks: Jupyter notebook with full experiment code

/figures: All training curves and accuracy plots

/report.pdf

README.md: This file

LICENSE: MIT License

License

Released under the MIT License.
