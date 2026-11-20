# MNIST - Deep Learning Through Computer Vision
This codebase presents tutorial-like workflows for learning deep learning
through the prism of computer vision and the MNIST dataset (and its
derivatives). These codes rely on a basic level of Python understanding, a
general grasp of college-level mathematics, and the desire to learn. The goal
of this pseudo-course is to provide you with an overview of the fundementals
of deep learning to encourage continued pursuit towards interesting topics.

## Topics Covered
- [ ] Introduction to Deep Learning and Machine Learning Concepts
- [ ] Feed-Forward Neural Networks (High-Level Overview)
    - [ ] Artificial Neurons
    - [ ] Weights and Biases
    - [ ] Activation Functions
- [ ] Training a Neural Network (High-Level Overview)
    - [ ] PyTorch Architecture Design
    - [ ] Forward Pass
    - [ ] Loss Function
    - [ ] Backprpagation
    - [ ] Optimization
- [ ] Project 1: MNIST Dataset
- [ ] Training a Neural Network (Mathematical Overview)
    - [ ] Back Propagation
    - [ ] Gradient Descent
    - [ ] Automatic Differentiation
- [ ] Convolutional Neural Networks

## Requirements
* [uv](https://docs.astral.sh/uv/) - For Managing Python Environment

## Usage
MNIST is a small, simple dataset. As such, you will *probably* not require
a CUDA available GPU for this project and can instead run locally. Simple
build files to this end are provided; run the following commands to set
up your environment:
* Sync your environment by `uv sync`
* Run Jupyter Lab by: `uv run --with jupyterlab jupyter lab`
