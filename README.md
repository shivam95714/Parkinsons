# Parkinson's Disease Prediction

**Overview**

This Python script employs a Support Vector Machine (SVM) model to predict the presence or absence of Parkinson's disease based on specific features. SVM is a powerful machine learning algorithm known for its effectiveness in classification tasks by finding the optimal hyperplane that best separates different classes. The following is a high-level breakdown of the code:

## Importing Dependencies

The script starts by importing necessary libraries, including NumPy, Pandas, and scikit-learn components for SVM, data splitting, and evaluation metrics.

## Data Collection & Analysis

**Loading Data:** The Parkinson's dataset is loaded from a CSV file into a Pandas DataFrame.

**Data Overview:** The first few rows, shape, and information about the dataset are displayed.

**Missing Values:** The script checks for missing values in each column.

**Statistical Measures:** Basic statistical measures for the dataset are provided.

**Target Variable Distribution:** The distribution of the target variable ('status') is presented.

**Data Grouping:** Data is grouped by the target variable to explore mean values.

## Data Pre-Processing

**Separating Features & Target:** The dataset is split into features (X) and the target variable (Y).

**Data Splitting:** The data is further split into training and testing sets using scikit-learn's `train_test_split`.

**Data Standardization:** `StandardScaler` is used to standardize the training and testing data.

## Model Training

**Support Vector Machine Model:** An SVM model with a linear kernel is chosen for training. SVM works by finding the hyperplane that maximizes the margin between different classes, making it well-suited for classification tasks.

## Model Evaluation

**Accuracy Score:** The accuracy scores for both the training and testing data are calculated.

## Building a Predictive System

**Input Data:** A sample input data point is provided.

**Prediction:** The trained model is used to predict the presence or absence of Parkinson's disease for the input data.

**Output Display:** The script prints whether the person has Parkinson's disease or not based on the model prediction.

This code aims to demonstrate the use of SVM for medical diagnosis and provides a simple predictive system for Parkinson's disease based on the input features.
