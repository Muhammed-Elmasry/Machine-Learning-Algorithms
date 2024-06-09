# Anomaly Detection and Recommender Systems Programming Exercise

## Introduction

In this exercise, you will implement the anomaly detection algorithm and apply it to detect failing servers on a network. In the second part, you will use collaborative filtering to build a recommender system for movies. Before starting on the programming exercise, we strongly recommend watching the video lectures and completing the review questions for the associated topics.

## Getting Started

1. **Prerequisites**:
   - Watch the video lectures related to anomaly detection and recommender systems.
   - Complete the review questions for these topics.

2. **Setup**:
   - Download and unzip the starter code into your working directory.
   - Use the `cd` command in Octave/MATLAB to navigate to this directory.

3. **Environment Setup**:
   - Refer to the “Environment Setup Instructions” on the course website for installing Octave/MATLAB.

## Files Included

- **Mandatory Files**:
  - `ex8.m`: Script for the first part of the exercise.
  - `ex8_cofi.m`: Script for the second part of the exercise.
  - `ex8data1.mat`: First example dataset for anomaly detection.
  - `ex8data2.mat`: Second example dataset for anomaly detection.
  - `ex8_movies.mat`: Movie review dataset.
  - `ex8_movieParams.mat`: Parameters provided for debugging.
  - `multivariateGaussian.m`: Computes the probability density function for a Gaussian distribution.
  - `visualizeFit.m`: 2D plot of a Gaussian distribution and a dataset.
  - `checkCostFunction.m`: Gradient checking for collaborative filtering.
  - `computeNumericalGradient.m`: Numerically compute gradients.
  - `fmincg.m`: Function minimization routine (similar to fminunc).
  - `loadMovieList.m`: Loads the list of movies into a cell-array.
  - `movie_ids.txt`: List of movies.
  - `normalizeRatings.m`: Mean normalization for collaborative filtering.
  - `estimateGaussian.m`: Estimate the parameters of a Gaussian distribution with a diagonal covariance matrix.
  - `selectThreshold.m`: Find a threshold for anomaly detection.
  - `cofiCostFunc.m`: Implement the cost function for collaborative filtering.

## Exercise Instructions

### 1. Anomaly Detection

#### 1.1 Gaussian Distribution
- Implement the function to estimate the parameters of a Gaussian distribution in `estimateGaussian.m`.

#### 1.2 Selecting the Threshold, ε
- Implement the function to select the threshold ε using the F1 score on a cross-validation set in `selectThreshold.m`.

#### 1.3 High Dimensional Dataset
- Apply the anomaly detection algorithm to a larger, high-dimensional dataset.

### 2. Recommender Systems

#### 2.1 Movie Ratings Dataset
- Load the dataset `ex8_movies.mat` and understand the structure of the matrices Y and R.

#### 2.2 Collaborative Filtering Learning Algorithm

##### 2.2.1 Collaborative Filtering Cost Function
- Implement the cost function for collaborative filtering in `cofiCostFunc.m`.

##### 2.2.2 Collaborative Filtering Gradient
- Implement the gradient computation for collaborative filtering in `cofiCostFunc.m`.

##### 2.2.3 Regularized Cost Function
- Add regularization to the cost function.

##### 2.2.4 Regularized Gradient
- Add regularization to the gradient computation.

#### 2.3 Learning Movie Recommendations
- Train the collaborative filtering model and make movie recommendations based on the trained parameters.
