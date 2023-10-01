# Multi-class classification of Cardiac Arrhythmia

The objective of this project is to utilize machine learning models for the classification of various types of Arrhythmia. The target variable comprises 16 distinct classes of Arrhythmia, resulting in a highly imbalanced dataset. Additionally, the dataset is characterized by high dimensionality. Hence, this project aims to employ diverse machine learning techniques to effectively identify and select the most pertinent features for the modeling process.

# DataSet

Its a UCI machine learning dataset with 279 features.
Path to dataset:  https://archive.ics.uci.edu/dataset/5/arrhythmia

# Feature selection Techniques

SelectKbest, Principle Component Analysis, Lasso Regression, Recursive Feature Selection in combination with Gradient Boost

# Classification Algorithms

Support Vector Machine, Naive Bayes, Random Forest, K-nearest Neighbors, LightGBM

# Evaluation Metrics

Accuracy, Precision, Recall, F1-Score, Kappa Statistics, Cross Validation

# Approach

Four Feature subsets are created using the Feature selection Techniques, and each feature subsets are trained using the 6 classification algorithms.
Performance of each classification algorithms are then compared.

# Results

The features selected by Recursive Feature Selection Technique and LightGBM classification model returns highest accuracy of 89%.






