# Predictive-Machine-Failure-Analysis
This project is about predicting when a machine might fail using Artificial Intelligence (AI) and Machine Learning (ML). I have use real data from machines (like temperature, speed, and tool wear) and train models to find patterns that usually lead to machine failure. This helps prevent sudden breakdowns and saves time and money.

# Project Overview
Machines can stop working suddenly, which causes delays and extra costs. To avoid this, I can use data from the machines to predict failures before they happen. This is called predictive maintenance.

In this project, I have:
1.Used real machine data from a dataset.
2.Created models from scratch(Decision tree, SVM)
3.Clean and prepare the data for analysis.
4.Train AI models to detect early signs of machine failure.
5.Check how well the models perform.
6.Show the results using graphs and reports.

# The Dataset
I have used the AI4I 2020 Predictive Maintenance Dataset from the UCI Machine Learning Repository. It includes thousands of records from machines running in a factory.
Dataset link: 'https://archive.ics.uci.edu/ml/machine-learning-databases/00601/ai4i2020.csv'.

# Important Details:
Target (what we are predicting):
Machine failure (1 = failure, 0 = no failure)

Main Features (data we use to predict):
Air temperature
Process temperature
Rotational speed of the machine
Torque (twisting force)
Tool wear (how much the tool has been used)

# How the Project Works
Step 1: Load the Data
Load the dataset directly from the internet using pandas.

Step 2: Preprocess the Data
1.Fix any missing values
2.Make sure the labels are in the right format
3.Scale the features (standardize the values)

Step 3: Split the Data
I have divide the data into three parts:
1.Training Set – to train the model
2.Validation Set – to adjust the model
3.Test Set – to check final accuracy

Step 4: Train the Models
I have created machine learning models from scratch and then used the models for predicitng the failure. 
Models used in the code: 
1.Decision Tree
2.Support Vector Machines (SVM)
Each model learns from the training data to recognize failure patterns.

Step 5: Evaluate the Models
To check how well the models perform using:
1.Confusion Matrix
2.Accuracy
3.Precision
4.Recall
5.F1 Score
6.ROC-AUC Score

# Results & Graphs
To show results, I have used:
1.Heatmaps (for confusion matrix)
2.Line plots (for accuracy or ROC curves)
3.Tables (for scores and predictions)
