# Machine Learning Programming Exercises

This repository contains solutions to various programming exercises from a machine learning course. Each exercise focuses on implementing key algorithms and applying them to different datasets. Below are details for each exercise.

## Table of Contents

- [ex1 - Linear Regression](#ex1---linear-regression)
- [ex2 - Logistic Regression](#ex2---logistic-regression)
- [ex3 - Multi-class Classification and Neural Networks](#ex3---multi-class-classification-and-neural-networks)
- [ex4 - Neural Network Learning](#ex4---neural-network-learning)
- [ex5 - Regularized Linear Regression and Bias vs. Variance](#ex5---regularized-linear-regression-and-bias-vs-variance)
- [ex6 - Support Vector Machines](#ex6---support-vector-machines)
- [ex7 - K-means Clustering and PCA](#ex7---k-means-clustering-and-pca)
- [ex8 - Anomaly Detection and Recommender Systems](#ex8---anomaly-detection-and-recommender-systems)

## ex1 - Linear Regression

### Introduction
This exercise involves implementing linear regression with one variable and applying it to data.

### Files Included
- `ex1.m`: Main script for the exercise.
- `ex1data1.txt`: Dataset for linear regression with one variable.
- `warmUpExercise.m`: Function to return a 5x5 identity matrix.
- `plotData.m`: Function to display the dataset.
- `computeCost.m`: Function to compute the cost of linear regression.
- `gradientDescent.m`: Function to run gradient descent.

### Exercise Instructions
- Implement the functions for warm-up exercise, cost computation, and gradient descent.
- Plot the data and visualize the linear fit.
- Experiment with different learning rates and iterations.

## ex2 - Logistic Regression

### Introduction
In this exercise, you will implement logistic regression and apply it to a dataset.

### Files Included
- `ex2.m`: Main script for the exercise.
- `ex2data1.txt`: Training set for logistic regression.
- `sigmoid.m`: Sigmoid function.
- `costFunction.m`: Logistic regression cost function.
- `predict.m`: Logistic regression prediction function.
- `costFunctionReg.m`: Regularized logistic regression cost function.

### Exercise Instructions
- Implement the sigmoid function, cost function, and gradient descent.
- Plot decision boundaries and visualize logistic regression results.
- Apply regularization and test on different datasets.

## ex3 - Multi-class Classification and Neural Networks

### Introduction
This exercise involves implementing one-vs-all logistic regression and neural networks to recognize handwritten digits.

### Files Included
- `ex3.m`: Script for one-vs-all logistic regression.
- `ex3_nn.m`: Script for neural networks.
- `ex3data1.mat`: Handwritten digits dataset.
- `ex3weights.mat`: Initial weights for the neural network.
- `sigmoid.m`: Sigmoid function.
- `lrCostFunction.m`: Logistic regression cost function.
- `oneVsAll.m`: Train a one-vs-all multi-class classifier.
- `predictOneVsAll.m`: Predict using a one-vs-all multi-class classifier.
- `predict.m`: Neural network prediction function.

### Exercise Instructions
- Implement logistic regression for multi-class classification.
- Implement feedforward propagation for neural networks.
- Train and test the models on the dataset.

## ex4 - Neural Network Learning

### Introduction
In this exercise, you will implement the backpropagation algorithm for neural networks and apply it to digit recognition.

### Files Included
- `ex4.m`: Main script for the exercise.
- `ex4data1.mat`: Handwritten digits dataset.
- `ex4weights.mat`: Neural network parameters.
- `sigmoid.m`: Sigmoid function.
- `computeNumericalGradient.m`: Numerically compute gradients.
- `checkNNGradients.m`: Function to check gradients.
- `debugInitializeWeights.m`: Function for initializing weights.
- `predict.m`: Neural network prediction function.
- `sigmoidGradient.m`: Compute the gradient of the sigmoid function.
- `randInitializeWeights.m`: Randomly initialize weights.
- `nnCostFunction.m`: Neural network cost function.

### Exercise Instructions
- Implement feedforward and cost function for neural networks.
- Implement backpropagation for training.
- Use numerical gradient checking to verify implementation.

## ex5 - Regularized Linear Regression and Bias vs. Variance

### Introduction
This exercise involves implementing regularized linear regression and using it to study bias-variance properties.

### Files Included
- `ex5.m`: Main script for the exercise.
- `ex5data1.mat`: Dataset for regression.
- `featureNormalize.m`: Feature normalization function.
- `fmincg.m`: Function minimization routine.
- `plotFit.m`: Plot a polynomial fit.
- `trainLinearReg.m`: Trains linear regression using your cost function.
- `linearRegCostFunction.m`: Regularized linear regression cost function.
- `learningCurve.m`: Generates a learning curve.
- `polyFeatures.m`: Maps data into polynomial feature space.
- `validationCurve.m`: Generates a cross-validation curve.

### Exercise Instructions
- Implement linear regression with regularization.
- Plot learning curves and study bias-variance trade-offs.
- Apply polynomial regression and experiment with different degrees and regularization parameters.

## ex6 - Support Vector Machines

### Introduction
In this exercise, you will be using support vector machines (SVMs) to build a spam classifier.

### Files Included
- `ex6.m`: Script for the exercise.
- `ex6data1.mat`: Example dataset 1.
- `ex6data2.mat`: Example dataset 2.
- `ex6data3.mat`: Example dataset 3.
- `svmTrain.m`: SVM training function.
- `svmPredict.m`: SVM prediction function.
- `plotData.m`: Plot 2D data.
- `visualizeBoundaryLinear.m`: Plot linear boundary.
- `visualizeBoundary.m`: Plot non-linear boundary.
- `linearKernel.m`: Linear kernel for SVM.
- `gaussianKernel.m`: Gaussian kernel for SVM.
- `dataset3Params.m`: Parameters for dataset 3.

### Exercise Instructions
- Implement and test linear and Gaussian kernels for SVM.
- Apply SVM to different datasets and visualize the decision boundaries.
- Implement a spam classifier using SVM.

## ex7 - K-means Clustering and PCA

### Introduction
In this exercise, you will implement the K-means clustering algorithm and apply it to image compression. You will also use PCA for dimensionality reduction.

### Files Included
- `ex7.m`: Script for K-means.
- `ex7_pca.m`: Script for PCA.
- `ex7data1.mat`: Example dataset for PCA.
- `ex7data2.mat`: Example dataset for K-means.
- `ex7faces.mat`: Faces dataset.
- `bird_small.png`: Example image.
- `displayData.m`: Displays 2D data stored in a matrix.
- `drawLine.m`: Draws a line over an existing figure.
- `plotDataPoints.m`: Initialization for K-means centroids.
- `plotProgresskMeans.m`: Plots each step of K-means.
- `runkMeans.m`: Runs the K-means algorithm.
- `pca.m`: Perform principal component analysis.
- `projectData.m`: Projects data into a lower-dimensional space.
- `recoverData.m`: Recovers the original data from the projection.
- `findClosestCentroids.m`: Find closest centroids for K-means.
- `computeCentroids.m`: Compute centroid means for K-means.
- `kMeansInitCentroids.m`: Initialization for K-means centroids.

### Exercise Instructions
- Implement K-means clustering and apply it to image compression.
- Visualize K-means steps and the compressed image.
- Implement PCA and apply it to dimensionality reduction on face images.

## ex8 - Anomaly Detection and Recommender Systems

### Introduction
In this exercise, you will implement the anomaly detection algorithm and apply it to detect failing servers on a network. You will also use collaborative filtering to build a recommender system for movies.

### Files Included
- `ex8.m`: Script for anomaly detection.
- `ex8_cofi.m`: Script for collaborative filtering.
- `ex8data1.mat`: First example dataset for anomaly detection.
- `ex8data2.mat`: Second example dataset for anomaly detection.
- `ex8_movies.mat`: Movie review dataset.
- `ex8_movieParams.mat`: Parameters for debugging.
- `multivariateGaussian.m`: Computes the probability density function for a Gaussian distribution.
- `visualizeFit.m`: 2D plot of a Gaussian distribution and a dataset.
- `checkCostFunction.m`: Gradient checking for collaborative filtering.
- `computeNumericalGradient.m`: Numerically compute gradients.
- `fmincg.m`: Function minimization routine.
- `loadMovieList.m`: Loads the list of movies into a cell-array.
- `movie_ids.txt`: List of movies.
- `normalizeRatings.m`: Mean normalization for collaborative filtering.
- `estimateGaussian.m`: Estimate the parameters of a Gaussian distribution.
- `selectThreshold.m`: Find a threshold for anomaly detection.
- `cofiCostFunc.m`: Implement the cost function for collaborative filtering.

### Exercise Instructions
- Implement anomaly detection using Gaussian distribution.
- Select the anomaly threshold using F1 score.
- Implement collaborative filtering for movie recommendations.
- Train the collaborative filtering model and make recommendations.

## Additional Resources
- Use `help` in Octave/MATLAB for function documentation.
- Refer to Octave and MATLAB documentation pages for further assistance.

Happy
