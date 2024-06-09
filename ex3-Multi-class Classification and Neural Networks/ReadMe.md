# Multi-class Classification and Neural Networks Programming Exercise

## Introduction

In this exercise, you will implement one-vs-all logistic regression and neural networks to recognize handwritten digits. Before starting the programming exercise, we strongly recommend watching the video lectures and completing the review questions for the associated topics.

## Getting Started

1. **Prerequisites**:
   - Watch the video lectures related to multi-class classification and neural networks.
   - Complete the review questions for these topics.

2. **Setup**:
   - Download and unzip the starter code into your working directory.
   - Use the `cd` command in Octave/MATLAB to navigate to this directory.

3. **Environment Setup**:
   - Refer to the “Environment Setup Instructions” on the course website for installing Octave/MATLAB.

## Files Included

- **Mandatory Files**:
  - `ex3.m`: Script for the one-vs-all logistic regression.
  - `ex3_nn.m`: Script for the neural network.
  - `ex3data1.mat`: Training set of handwritten digits.
  - `ex3weights.mat`: Initial weights for the neural network exercise.
  - `sigmoid.m`: Sigmoid function.
  - `lrCostFunction.m`: Logistic regression cost function.
  - `oneVsAll.m`: Train a one-vs-all multi-class classifier.
  - `predictOneVsAll.m`: Predict using a one-vs-all multi-class classifier.
  - `predict.m`: Neural network prediction function.

- **Optional Files**:
  - `submit.m`: Script to submit your solutions.
  - `displayData.m`: Function to help visualize the dataset.
  - `fmincg.m`: Function minimization routine (similar to fminunc).

## Exercise Instructions

### 1. Multi-class Classification

#### 1.1 Dataset
- Load the dataset from `ex3data1.mat`:
  ```matlab
  load('ex3data1.mat');
