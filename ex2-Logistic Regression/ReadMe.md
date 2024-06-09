# Logistic Regression Programming Exercise

## Introduction

In this exercise, you will implement logistic regression and apply it to two different datasets. Before starting on the programming exercise, we strongly recommend watching the video lectures and completing the review questions for the associated topics.

## Getting Started

1. **Prerequisites**:
   - Watch the video lectures related to logistic regression.
   - Complete the review questions for these topics.

2. **Setup**:
   - Download and unzip the starter code into your working directory.
   - Use the `cd` command in Octave/MATLAB to navigate to this directory.

3. **Environment Setup**:
   - Refer to the “Environment Setup Instructions” on the course website for installing Octave/MATLAB.

## Files Included

- **Mandatory Files**:
  - `ex2.m`: Main script for the exercise.
  - `ex2data1.txt`: Training set for the first half of the exercise.
  - `ex2data2.txt`: Training set for the second half of the exercise.
  - `sigmoid.m`: Sigmoid function.
  - `costFunction.m`: Logistic regression cost function.
  - `predict.m`: Logistic regression prediction function.
  - `costFunctionReg.m`: Regularized logistic regression cost function.

- **Optional Files**:
  - `ex2_reg.m`: Script for the exercise with regularization.
  - `submit.m`: Script to submit your solutions.
  - `mapFeature.m`: Function to generate polynomial features.
  - `plotDecisionBoundary.m`: Function to plot classifier’s decision boundary.
  - `plotData.m`: Function to plot 2D classification data.

## Exercise Instructions

### 1. Logistic Regression

#### 1.1 Visualizing the Data
- Load and plot the data in `plotData.m`:
  ```matlab
  pos = find(y == 1);
  neg = find(y == 0);
  plot(X(pos, 1), X(pos, 2), 'k+','LineWidth', 2, 'MarkerSize', 7);
  plot(X(neg, 1), X(neg, 2), 'ko', 'MarkerFaceColor', 'y', 'MarkerSize', 7);
