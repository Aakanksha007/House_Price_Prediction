Advanced House Price Predictions

Overview

Welcome to the Advanced House Price Predictions project! This repository contains the code for performing data preprocessing, exploratory data analysis, and building multiple machine learning models to predict house prices. The dataset used for this project is sourced from a Kaggle competition, and the goal is to predict the final sale price of homes based on various features.

Table of Contents

Introduction
Dataset
Project Workflow
Data Preprocessing
Exploratory Data Analysis
Model Building
Linear Regression
Lasso Regression
Random Forest Regressor
Gradient Boosting Regressor
Model Ensemble
Results
Usage
Contributing
License
Introduction

In this project, we aim to predict house prices using advanced machine learning techniques. We start by cleaning and preprocessing the data, followed by exploratory data analysis to understand the relationships between different features and the target variable (SalePrice). Finally, we build and evaluate several regression models to identify the best-performing model.

Dataset

The dataset contains various features of houses, such as lot area, year built, number of rooms, and more. The target variable is the sale price of the houses.

Project Workflow

Data Preprocessing: Handling missing values, encoding categorical variables, and outlier analysis.
Exploratory Data Analysis: Visualizing the data to identify patterns and relationships.
Model Building: Training and evaluating multiple regression models.
Model Ensemble: Combining the predictions of different models to improve accuracy.
Data Preprocessing

Dropping Irrelevant Features: We drop features like 'Id' and other features with a high percentage of missing values.
Handling Missing Values: For numerical features with missing values, we use the median strategy. For categorical features, we use the most frequent value or a new label 'Missing'.
One-Hot Encoding: Categorical variables are encoded using one-hot encoding to convert them into numerical format.
Exploratory Data Analysis

We use various plots and statistical methods to understand the data:

Box Plots: To identify outliers in numerical features.
Scatter Plots: To visualize relationships between features and the target variable.
Correlation Heatmap: To identify the strength of relationships between different features and the target variable.
Model Building

Linear Regression
A simple linear regression model to understand the basic relationship between features and the target variable.

Lasso Regression
A regularized linear model that uses L1 regularization to handle multicollinearity and feature selection.

Random Forest Regressor
An ensemble model that uses multiple decision trees to improve prediction accuracy and handle overfitting.

Gradient Boosting Regressor
An ensemble model that builds trees sequentially to correct the errors of previous trees, providing high prediction accuracy.

Model Ensemble
Combining the predictions of all models to improve overall performance.

Results

Linear Regression:

Score: 87%
Mean Absolute Error: 19122
Lasso Regression:

Score: 87.5%
Mean Absolute Error: 18834.56
Random Forest Regressor:

Score: 89%
Mean Absolute Error: 16343.10
Gradient Boosting Regressor:

Score: 91.6%
Mean Absolute Error: 14460.84
Model Ensemble:

Mean Absolute Error: Combining predictions from all models resulted in improved performance.

