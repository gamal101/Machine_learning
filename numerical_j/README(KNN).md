Housing Price Prediction - Regression Models
This repository contains code for predicting housing prices using various regression models, including Linear Regression and K-Nearest Neighbors (KNN) Regression.

Overview
This updated script incorporates:

Building a KNN Regression model for predicting housing prices.
Evaluating the KNN Regression model's performance alongside the Linear Regression model.
Visualizing the results of KNN Regression through a scatter plot and evaluation metrics.
Requirements
Make sure you have the following installed:

Python 3.x
Libraries:
pandas
scikit-learn
matplotlib
seaborn
Usage
Dataset Preparation:

Ensure the housing dataset ('housing.csv') is available.
The script handles missing values in numeric columns by filling them with medians.
Regression Model Implementation:

The code creates a preprocessing pipeline for numeric and categorical features.
Implements both Linear Regression and KNN Regression models for housing price prediction.
Running the Script:

Execute the script and observe the comparison between Linear Regression and KNN Regression.
Review the scatter plot and evaluation metrics for the KNN Regression model.
Instructions
Linear Regression:

The script uses Linear Regression for housing price prediction.
It calculates R-squared and Mean Squared Error (MSE) for model evaluation.
KNN Regression:

Utilizes the KNN Regression model with n_neighbors=5 for housing price prediction.
Calculates R-squared and MSE, and displays a scatter plot for visual analysis.
Results
Linear Regression Score on test data.
KNN Regression Score on test data.
Scatter plot depicting the relationship between actual and predicted housing prices for KNN Regression.
Mean Squared Error (MSE) and R-squared on test data for KNN Regression.
Note
Ensure the dataset is correctly formatted and accessible.
Experiment with hyperparameters or models for better performance if needed.
Author

Jamal Syed