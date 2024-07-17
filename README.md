# Weather-Prediction-using-KNN-and-Naive-Bayes
This repository contains a weather prediction analysis using two classification algorithms: K-Nearest Neighbors (KNN) and Naive Bayes (GaussianNB). The goal is to predict whether it will be sunny based on various weather-related features.

#Dataset Overview
The dataset includes features such as:
Date: The date of the observation.
Precipitation: Amount of precipitation recorded (inches).
Maximum Temperature: Maximum temperature recorded (°F).
Minimum Temperature: Minimum temperature recorded (°F).
Wind Speed: Wind speed recorded (mph).
Weather: Categorical variable indicating weather conditions (sunny, rainy, etc.).

#Key Steps in the Analysis
Data Loading and Overview: Load the dataset using Pandas and display basic statistics, including data types and missing values.
Data Preprocessing:
Convert the 'date' column to datetime type and extract year, month, and day.
Handle missing values in the precipitation column.
Perform one-hot encoding on the 'weather' categorical variable.
Exploratory Data Analysis (EDA):
Visualize the distribution of numerical variables using histograms.
Explore relationships between weather conditions and precipitation using box plots.
Analyze trends over time with line plots.
Modeling:
Naive Bayes: Train a Gaussian Naive Bayes classifier and evaluate its performance on the test set. Calculate accuracy, classification report, and confusion matrix.
K-Nearest Neighbors (KNN): Train a KNN classifier and evaluate its performance using similar metrics.
Model Evaluation: Present confusion matrices visually to compare the performance of the classifiers.

#Requirements
To run this analysis, you will need the following Python libraries:
numpy
pandas
matplotlib
seaborn
scikit-learn
