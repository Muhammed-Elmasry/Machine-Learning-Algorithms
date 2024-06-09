# Regularized Linear Regression and Bias vs. Variance Programming Exercise

## Introduction

In this exercise, you will implement regularized linear regression and use it to study models with different bias-variance properties. Before starting the programming exercise, we strongly recommend watching the video lectures and completing the review questions for the associated topics.

## Getting Started

1. **Prerequisites**:
   - Watch the video lectures related to regularized linear regression and bias-variance.
   - Complete the review questions for these topics.

2. **Setup**:
   - Download and unzip the starter code into your working directory.
   - Use the `cd` command in Octave/MATLAB to navigate to this directory.

3. **Environment Setup**:
   - Refer to the “Environment Setup Instructions” on the course website for installing Octave/MATLAB.

## Files Included

- **Mandatory Files**:
  - `ex5.m`: Main script for the exercise.
  - `ex5data1.mat`: Dataset.
  - `featureNormalize.m`: Feature normalization function.
  - `fmincg.m`: Function minimization routine (similar to fminunc).
  - `plotFit.m`: Plot a polynomial fit.
  - `trainLinearReg.m`: Trains linear regression using your cost function.
  - `linearRegCostFunction.m`: Regularized linear regression cost function.
  - `learningCurve.m`: Generates a learning curve.
  - `polyFeatures.m`: Maps data into polynomial feature space.
  - `validationCurve.m`: Generates a cross validation curve.

## Exercise Instructions

### 1. Regularized Linear Regression

#### 1.1 Visualizing the Dataset
- Load and visualize the dataset containing historical records on the change in the water level and the amount of water flowing out of the dam.

#### 1.2 Regularized Linear Regression Cost Function
- Implement the regularized linear regression cost function in `linearRegCostFunction.m`.

#### 1.3 Regularized Linear Regression Gradient
- Implement the gradient computation for regularized linear regression in `linearRegCostFunction.m`.

#### 1.4 Fitting Linear Regression
- Train linear regression using `trainLinearReg.m` and visualize the best fit line.

### 2. Bias-Variance

#### 2.1 Learning Curves
- Implement the learning curves in `learningCurve.m` to diagnose bias-variance problems.

### 3. Polynomial Regression

#### 3.1 Polynomial Feature Mapping
- Implement polynomial feature mapping in `polyFeatures.m` to map the original training set into higher powers.

#### 3.2 Learning Polynomial Regression
- Train polynomial regression using `trainLinearReg.m` and visualize the polynomial fit.

### Optional Exercises

#### 3.3 Adjusting the Regularization Parameter
- Observe how the regularization parameter affects the bias-variance of polynomial regression by modifying the lambda parameter in `ex5.m`.

#### 3.4 Selecting λ Using a Cross Validation Set
- Implement `validationCurve.m` to select the best λ parameter using a cross validation set.

#### 3.5 Computing Test Set Error
- Compute the test error using the best value of λ found from the cross validation set.

#### 3.6 Plotting Learning Curves with Randomly Selected Examples
- Implement a strategy for computing learning curves with randomly selected examples to average the training error and cross validation error.

## Submitting Solutions

1. **Regularized Linear Regression Cost Function**:
   - Complete `linearRegCostFunction.m` and submit.
2. **Regularized Linear Regression Gradient**:
   - Complete `linearRegCostFunction.m` and submit.
3. **Learning Curve**:
   - Complete `learningCurve.m` and submit.
4. **Polynomial Feature Mapping**:
   - Complete `polyFeatures.m` and submit.
5. **Cross Validation Curve**:
   - Complete `validationCurve.m` and submit.

You can submit multiple times; only the highest score will be considered.

## Additional Resources
- Use `help` in Octave/MATLAB for function documentation.
- Refer to Octave and MATLAB documentation pages for further assistance.

Happy coding!
