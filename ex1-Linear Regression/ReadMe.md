# Linear Regression Programming Exercise

## Introduction

This exercise involves implementing linear regression and applying it to data using Octave/MATLAB. The exercise comprises two parts: linear regression with one variable (required) and linear regression with multiple variables (optional).

## Getting Started

1. **Prerequisites**:
   - Watch the video lectures related to linear regression.
   - Complete the review questions for these topics.

2. **Setup**:
   - Download and unzip the starter code into your working directory.
   - Use the `cd` command in Octave/MATLAB to navigate to this directory.

3. **Environment Setup**:
   - Refer to the “Environment Setup Instructions” on the course website for installing Octave/MATLAB.

## Files Included

- **Mandatory Files**:
  - `ex1.m`: Main script for the exercise.
  - `ex1data1.txt`: Dataset for linear regression with one variable.
  - `warmUpExercise.m`: Function to return a 5x5 identity matrix.
  - `plotData.m`: Function to display the dataset.
  - `computeCost.m`: Function to compute the cost of linear regression.
  - `gradientDescent.m`: Function to run gradient descent.

- **Optional Files**:
  - `ex1_multi.m`: Script for the exercise with multiple variables.
  - `ex1data2.txt`: Dataset for linear regression with multiple variables.
  - `submit.m`: Script to submit your solutions.
  - `computeCostMulti.m`: Cost function for multiple variables.
  - `gradientDescentMulti.m`: Gradient descent for multiple variables.
  - `featureNormalize.m`: Function to normalize features.
  - `normalEqn.m`: Function to compute the normal equations.

## Exercise Instructions

### 1. Simple Octave/MATLAB Function
- Modify `warmUpExercise.m` to return a 5x5 identity matrix:
  ```matlab
  A = eye(5);
