# Heart Disease Classification Model

## Problem Statement
The task is to build a machine learning model to classify if a patient is at risk of a heart attack. This project will utilize the UCI Heart Disease Dataset.

## Dataset
The dataset can be accessed from the following link: [UCI Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/Heart+Disease?spm=5176.100239.blogcont54260.8.TRNGoO)

## Lab Environment
This project will be implemented using Jupyter Notebooks.

## Domain
Healthcare

## Tasks
### 1. Data Analysis
- Import the dataset
- Gather information about the dataset (mean, max, min, quartiles, etc.)
- Find the correlation between all fields

### 2. Data Visualization
- Visualize the number of patients having heart disease and not having heart disease
- Visualize the relationship between age and whether a patient has a disease or not
- Visualize correlation between all features using a heat map

### 3. Logistic Regression
- Build a simple logistic regression model
  - Divide the dataset into a 70:30 ratio
  - Build the model on the train set and predict the values on the test set
  - Build the confusion matrix and get the accuracy score

### 4. Decision Tree
- Build a decision tree model
  - Divide the dataset into a 70:30 ratio
  - Build the model on the train set and predict the values on the test set
  - Build the confusion matrix and calculate the accuracy
  - Visualize the decision tree using the Graphviz package

### 5. Random Forest
- Build a Random Forest model
  - Divide the dataset into a 70:30 ratio
  - Build the model on the train set and predict the values on the test set
  - Build the confusion matrix and calculate the accuracy
  - Visualize the model using the Graphviz package

### 6. Select the Best Model
- Print the confusion matrix of all classifiers
- Print the classification report of all classifiers
- Calculate Recall, Precision, and F1 score of all the models
- Visualize confusion matrix using heatmaps
- Select the best model based on the best accuracies

