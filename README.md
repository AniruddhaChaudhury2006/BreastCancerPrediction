# Breast Cancer Prediction using Logistic Regression

This notebook demonstrates the process of building a Logistic Regression model to predict breast cancer (malignant or benign) based on features from the Wisconsin Breast Cancer Dataset.

## Table of Contents
1. [Introduction](#introduction)
2. [Data Loading and Exploration](#data-loading-and-exploration)
3. [Data Preprocessing](#data-preprocessing)
4. [Model Training](#model-training)
5. [Model Evaluation](#model-evaluation)
6. [Prediction System](#prediction-system)

## 1. Introduction
This project aims to classify breast cancer as either malignant (0) or benign (1) using the Logistic Regression machine learning algorithm. The dataset used is the Breast Cancer Wisconsin (Diagnostic) Dataset, which contains various features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass.

## 2. Data Loading and Exploration
- The necessary libraries (NumPy, Pandas, scikit-learn) are imported.
- The breast cancer dataset is loaded using `sklearn.datasets.load_breast_cancer()`.
- The dataset is converted into a Pandas DataFrame for easier manipulation.
- Initial data exploration is performed to understand the dataset's structure, check for missing values, and analyze the distribution of the target variable.

## 3. Data Preprocessing
- The features (X) and target variable (Y) are separated from the DataFrame.
- The data is split into training and testing sets using `train_test_split` to evaluate the model's performance on unseen data.

## 4. Model Training
- A Logistic Regression model is initialized.
- The model is trained on the training data (`X_train`, `Y_train`).

## 5. Model Evaluation
- The trained model's accuracy is evaluated on both the training and test datasets.
- Accuracy scores are printed to assess how well the model generalizes.

## 6. Prediction System
- A system is demonstrated for making predictions on new, unseen data points.
- An example input data point is used to predict whether the cancer is malignant or benign.
