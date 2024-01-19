# System Tron Internship Week-1 Task
# Diabetes Prediction using SVM

## Overview

This Python program uses Support Vector Machines (SVM) for predicting diabetes based on a given dataset. It involves data preprocessing, model training, evaluation, and a simple predictive system.

## Dependencies

- `numpy`: For numerical operations.
- `pandas`: For handling and manipulating the dataset.
- `scikit-learn`:
  - `StandardScaler`: For standardizing the dataset.
  - `train_test_split`: For splitting the dataset into training and testing sets.
  - `svm.SVC`: Support Vector Machine classifier for classification.
  - `accuracy_score`: For evaluating the accuracy of the model.

## Dataset

The program assumes the existence of a CSV file named 'diabetes.csv', containing relevant data. It loads the dataset into a Pandas DataFrame and performs basic exploratory data analysis.

## Data Preprocessing

1. The 'Outcome' column is separated as the target variable (labels), and the rest of the columns are considered as features.
2. Standardization is applied to scale the features using `StandardScaler`.

## Model Training

The dataset is split into training and testing sets using `train_test_split`. The SVM classifier is trained on the training set with a linear kernel.

## Model Evaluation

The accuracy of the model is evaluated on both the training and testing sets using the `accuracy_score`.

## Predictive System

A simple predictive system is implemented to classify a new input based on the trained SVM model. The input data is standardized before making predictions.

## How to Use

1. Make sure to have the required dependencies installed (`numpy`, `pandas`, `scikit-learn`).
2. Prepare a CSV file named 'diabetes.csv' with the dataset.
3. Execute the provided Python script.

Note: Ensure that the dataset columns and structure align with the assumptions made in the program.

