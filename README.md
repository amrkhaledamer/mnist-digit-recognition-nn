# MNIST-digit-recognition-nn
A PyTorch-based neural network model for handwritten digit recognition using the MNIST dataset. Implements custom training loops, stratified data splitting, performance evaluation, and analysis of hyperparameters including learning rate, batch size, and network architecture.

## Features
- MNIST dataset loading and preprocessing
- Dynamic fully-connected neural network (`DynamicNN`)
- Training and validation routines
- Metric plotting (loss and accuracy)
- Hyperparameter tuning:
  - Learning rates
  - Batch sizes
  - Neural network layer configurations
- Evaluation with confusion matrix

- ## Requirements

To run this project, you need the following Python packages:

- Python 3.7+
- torch
- torchvision
- numpy
- scikit-learn
- matplotlib

- To install the dependencies, run:

```bash
pip install torch torchvision numpy scikit-learn matplotlib
