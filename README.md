# **Rock-vs-Mine-Prediction**
This repository contains a machine learning project to classify sonar signals as either Rock or Mine using various machine learning models, with a focus on the CatBoost Classifier. The dataset used is composed of sonar returns obtained by bouncing sound waves off different surfaces.
Project Workflow

# Machine Learning Models:

The primary model used is the CatBoost Classifier, a high-performance gradient boosting algorithm. It provides excellent accuracy with minimal tuning and is especially well-suited for tabular data.
Random Forest and Linear Regression models have also been explored for comparison purposes.

# Metrics:

Training and Test accuracy are calculated.
Cross-validation is also performed to ensure robust performance.

# Optional Improvements:

Feature importance is explored to understand which features have the greatest impact on the model’s predictions.
Hyperparameter tuning can be applied to improve the CatBoost model’s performance.

# Dataset
Source: UCI Machine Learning Repository - Sonar Dataset
Description: The dataset contains 208 samples with 60 features each, where each feature represents the energy in a particular frequency band. The task is to classify the samples as either Mine (M) or Rock (R).

# Requirements
To run this project, you need the following Python libraries:

numpy
pandas
scikit-learn
catboost
matplotlib
seaborn

# Results

The CatBoost Classifier achieves high accuracy on both the training and test datasets, making it a suitable model for this classification task.
