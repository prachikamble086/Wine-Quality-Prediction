# Wine-Quality-Prediction
# Readme

Wine Quality Analysis
This repository contains code for analyzing the quality of wine based on various features. The dataset used for analysis is the 'wine_quality.csv' file.

Dataset
The dataset consists of the following columns:

Fixed Acidity
Volatile Acidity
Citric Acid
Residual Sugar
Chlorides
Free Sulfur Dioxide
Total Sulfur Dioxide
Density
pH
Sulphates
Alcohol
Quality
Id
Code
The analysis is performed using Python and the following libraries:

pandas
sklearn
matplotlib
seaborn
The code performs the following steps:

Load the dataset and remove duplicates.
Handle missing values by dropping the corresponding rows.
Display the cleaned dataset.
Generate a correlation matrix and create a heatmap to visualize the correlation between the features.
Calculate the correlation of each feature with the 'quality' column and create a bar plot to display the results.
Scale the numerical features using StandardScaler.
Split the data into training and testing sets.
Train three classifiers: Naive Bayes, Random Forest, and Support Vector Machine (SVM).
Evaluate the accuracy of each classifier on the test set.
Visualize the accuracy of the classifiers using a bar plot.
Create additional visualizations, including a histogram of alcohol content, a count plot of wine quality, a scatter plot matrix, and a violin plot of wine quality by pH.
Results
The accuracy of the classifiers on the test set is as follows:

Naive Bayes: 0.611
Random Forest: 0.672
SVM: 0.616
Additional Visualizations
The repository includes several visualizations to provide insights into the wine quality dataset, including a histogram of alcohol content, a count plot of wine quality, a scatter plot matrix, and a violin plot of wine quality by pH.

Please refer to the code and visualizations for a detailed analysis of the wine quality dataset.
