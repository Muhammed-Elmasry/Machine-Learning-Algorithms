# K-means Clustering and Principal Component Analysis Programming Exercise

## Introduction

In this exercise, you will implement the K-means clustering algorithm and apply it to compress an image. In the second part, you will use principal component analysis to find a low-dimensional representation of face images. Before starting on the programming exercise, we strongly recommend watching the video lectures and completing the review questions for the associated topics.

## Getting Started

1. **Prerequisites**:
   - Watch the video lectures related to K-means clustering and principal component analysis.
   - Complete the review questions for these topics.

2. **Setup**:
   - Download and unzip the starter code into your working directory.
   - Use the `cd` command in Octave/MATLAB to navigate to this directory.

3. **Environment Setup**:
   - Refer to the “Environment Setup Instructions” on the course website for installing Octave/MATLAB.

## Files Included

- **Mandatory Files**:
  - `ex7.m`: Script for the first exercise on K-means.
  - `ex7_pca.m`: Script for the second exercise on PCA.
  - `ex7data1.mat`: Example dataset for PCA.
  - `ex7data2.mat`: Example dataset for K-means.
  - `ex7faces.mat`: Faces dataset.
  - `bird_small.png`: Example image.
  - `displayData.m`: Displays 2D data stored in a matrix.
  - `drawLine.m`: Draws a line over an existing figure.
  - `plotDataPoints.m`: Initialization for K-means centroids.
  - `plotProgresskMeans.m`: Plots each step of K-means as it proceeds.
  - `runkMeans.m`: Runs the K-means algorithm.
  - `pca.m`: Perform principal component analysis.
  - `projectData.m`: Projects a data set into a lower-dimensional space.
  - `recoverData.m`: Recovers the original data from the projection.
  - `findClosestCentroids.m`: Find closest centroids (used in K-means).
  - `computeCentroids.m`: Compute centroid means (used in K-means).
  - `kMeansInitCentroids.m`: Initialization for K-means centroids.

## Exercise Instructions

### 1. K-means Clustering

#### 1.1 Implementing K-means

##### 1.1.1 Finding Closest Centroids
- Implement the function `findClosestCentroids.m` to assign each training example to its closest centroid.

##### 1.1.2 Computing Centroid Means
- Implement the function `computeCentroids.m` to recompute the mean of each centroid based on the assigned examples.

#### 1.2 K-means on Example Dataset
- Run K-means on a toy 2D dataset to visualize how the algorithm works.

#### 1.3 Random Initialization
- Complete the function `kMeansInitCentroids.m` to initialize the centroids by selecting random examples from the dataset.

#### 1.4 Image Compression with K-means
- Apply K-means to compress an image by reducing the number of colors.

### 2. Principal Component Analysis (PCA)

#### 2.1 Example Dataset
- Visualize a 2D dataset to understand the effects of PCA.

#### 2.2 Implementing PCA
- Implement PCA in `pca.m` by computing the covariance matrix and using SVD to compute the eigenvectors.

#### 2.3 Dimensionality Reduction with PCA

##### 2.3.1 Projecting the Data onto the Principal Components
- Complete the function `projectData.m` to project the data onto a lower-dimensional space.

##### 2.3.2 Reconstructing an Approximation of the Data
- Complete the function `recoverData.m` to project the data back onto the original space and recover an approximation.

#### 2.4 Face Image Dataset
- Use PCA on a dataset of face images to reduce the dimensionality and visualize the effects.
