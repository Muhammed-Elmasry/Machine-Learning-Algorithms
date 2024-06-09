# Support Vector Machines Programming Exercise

## Introduction

In this exercise, you will be using support vector machines (SVMs) to build a spam classifier. Before starting on the programming exercise, we strongly recommend watching the video lectures and completing the review questions for the associated topics.

## Getting Started

1. **Prerequisites**:
   - Watch the video lectures related to support vector machines.
   - Complete the review questions for these topics.

2. **Setup**:
   - Download and unzip the starter code into your working directory.
   - Use the `cd` command in Octave/MATLAB to navigate to this directory.

3. **Environment Setup**:
   - Refer to the “Environment Setup Instructions” on the course website for installing Octave/MATLAB.

## Files Included

- **Mandatory Files**:
  - `ex6.m`: Script for the first half of the exercise.
  - `ex6data1.mat`: Example Dataset 1.
  - `ex6data2.mat`: Example Dataset 2.
  - `ex6data3.mat`: Example Dataset 3.
  - `svmTrain.m`: SVM training function.
  - `svmPredict.m`: SVM prediction function.
  - `plotData.m`: Plot 2D data.
  - `visualizeBoundaryLinear.m`: Plot linear boundary.
  - `visualizeBoundary.m`: Plot non-linear boundary.
  - `linearKernel.m`: Linear kernel for SVM.
  - `gaussianKernel.m`: Gaussian kernel for SVM.
  - `dataset3Params.m`: Parameters to use for Dataset 3.

- **Spam Classification Files**:
  - `ex6_spam.m`: Script for the second half of the exercise.
  - `spamTrain.mat`: Spam training set.
  - `spamTest.mat`: Spam test set.
  - `emailSample1.txt`: Sample email 1.
  - `emailSample2.txt`: Sample email 2.
  - `spamSample1.txt`: Sample spam 1.
  - `spamSample2.txt`: Sample spam 2.
  - `vocab.txt`: Vocabulary list.
  - `getVocabList.m`: Load vocabulary list.
  - `porterStemmer.m`: Stemming function.
  - `readFile.m`: Reads a file into a character string.
  - `processEmail.m`: Email preprocessing.
  - `emailFeatures.m`: Feature extraction from emails.

## Exercise Instructions

### 1. Support Vector Machines

#### 1.1 Example Dataset 1
- Load and visualize Example Dataset 1. Experiment with different values of the C parameter.

#### 1.2 SVM with Gaussian Kernels

##### 1.2.1 Gaussian Kernel
- Implement the Gaussian kernel in `gaussianKernel.m`.

##### 1.2.2 Example Dataset 2
- Load and visualize Example Dataset 2. Train the SVM with the Gaussian kernel.

##### 1.2.3 Example Dataset 3
- Load and visualize Example Dataset 3. Use the cross-validation set to determine the best C and σ parameters.

### 2. Spam Classification

#### 2.1 Preprocessing Emails
- Implement email preprocessing in `processEmail.m`.

#### 2.2 Extracting Features from Emails
- Implement feature extraction in `emailFeatures.m`.

#### 2.3 Training SVM for Spam Classification
- Train a SVM classifier using the preprocessed training dataset.

#### 2.4 Top Predictors for Spam
- Inspect the parameters to find the words most indicative of spam.

### Optional Exercises

#### 2.5 Try Your Own Emails
- Test the spam classifier on your own emails.

#### 2.6 Build Your Own Dataset
- Build your own dataset using the original emails from the SpamAssassin Public Corpus.
