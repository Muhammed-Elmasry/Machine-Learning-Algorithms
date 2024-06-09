# Neural Networks Learning Programming Exercise

## Introduction

In this exercise, you will implement the backpropagation algorithm for neural networks and apply it to the task of hand-written digit recognition. Before starting the programming exercise, we strongly recommend watching the video lectures and completing the review questions for the associated topics.

## Getting Started

1. **Prerequisites**:
   - Watch the video lectures related to neural networks and backpropagation.
   - Complete the review questions for these topics.

2. **Setup**:
   - Download and unzip the starter code into your working directory.
   - Use the `cd` command in Octave/MATLAB to navigate to this directory.

3. **Environment Setup**:
   - Refer to the “Environment Setup Instructions” on the course website for installing Octave/MATLAB.

## Files Included

- **Mandatory Files**:
  - `ex4.m`: Main script for the exercise.
  - `ex4data1.mat`: Training set of hand-written digits.
  - `ex4weights.mat`: Neural network parameters for exercise 4.
  - `sigmoid.m`: Sigmoid function.
  - `computeNumericalGradient.m`: Numerically compute gradients.
  - `checkNNGradients.m`: Function to help check your gradients.
  - `debugInitializeWeights.m`: Function for initializing weights.
  - `predict.m`: Neural network prediction function.
  - `sigmoidGradient.m`: Compute the gradient of the sigmoid function.
  - `randInitializeWeights.m`: Randomly initialize weights.
  - `nnCostFunction.m`: Neural network cost function.

- **Optional Files**:
  - `submit.m`: Script to submit your solutions.
  - `displayData.m`: Function to help visualize the dataset.
  - `fmincg.m`: Function minimization routine (similar to fminunc).

## Exercise Instructions

### 1. Neural Networks

#### 1.1 Visualizing the Data
- Visualize a subset of the training set using `displayData.m`.

#### 1.2 Model Representation
- Load the dataset and pre-trained neural network weights from `ex4data1.mat` and `ex4weights.mat`:
  ```matlab
  load('ex4data1.mat');
  load('ex4weights.mat');
