# Gender Voice Classification

This repository contains a project for classifying gender based on voice features using various machine learning algorithms. The dataset used for this project is voice.csv, which contains voice samples and their corresponding features.
# Introduction
This project aims to classify gender (male/female) based on voice features using several machine learning algorithms. The performance of each algorithm is evaluated to determine the best model for this classification task.
## Requirements

The following Python libraries are required to run the code:
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn

## Dataset

The dataset used is `voice.csv`, which contains various features extracted from voice recordings.

## Exploratory Data Analysis
- Displaying the first few rows of the dataset.
- Checking for null values.
- Visualizing the correlation matrix of the features.

## Preprocessing
- Encoding the labels: Replacing 'male' with 1 and 'female' with 0.
- Splitting the dataset into training and testing sets.

## Algorithms Used
The following machine learning algorithms are used for classification:

- Logistic Regression
- Random Forest Classifier
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Decision Tree Classifier

## Results

The accuracy of each model on the training and testing sets is as follows:

## Results

The accuracy of each model on the training and testing sets is as follows:

### Logistic Regression
- **Training Accuracy:** 91%
- **Testing Accuracy:** 91%

### Random Forest Classifier
- **Training Accuracy:** 100%
- **Testing Accuracy:** 97%

### K-Nearest Neighbors (KNN)
- **Training Accuracy (k=3):** 85%
- **Testing Accuracy (k=3):** 74%
- **Training Accuracy (k=5):** 81%
- **Training Accuracy (k=7):** 79%

### Support Vector Machine (SVM)
#### Linear Kernel
- **Training Accuracy:** 97%
- **Testing Accuracy:** 97%

#### Radial Basis Function (RBF) Kernel
- **Training Accuracy:** 92%
- **Testing Accuracy:** 91%

#### Polynomial Kernel
- **Training Accuracy:** 53%
- **Testing Accuracy:** 52%

### Decision Tree Classifier
- **Training Accuracy:** 100%
- **Testing Accuracy:** 97%


