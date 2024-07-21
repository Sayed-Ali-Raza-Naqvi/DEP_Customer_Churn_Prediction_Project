# Customer Churn Prediction Project
This project involves predicting customer churn using various machine learning techniques. The dataset used is Churn_Modelling.csv, which contains customer data for a bank. The goal is to classify whether a customer will exit or not based on their characteristics.

## Project Overview
The project covers the following steps:

### 1. Data Loading and Exploration:
- Load the dataset from a CSV file.
- Perform initial data exploration, including checking the dataset's shape, information, and statistics.

### 2. Data Preprocessing:
- Handle missing values and duplicate records.
- Encode categorical variables: 'Gender' and 'Geography' are mapped to numeric values.
- Drop irrelevant columns: 'RowNumber', 'CustomerId', and 'Surname'.
- Perform data visualization using histograms and boxplots to understand the distribution and identify outliers.
- Remove outliers based on the Interquartile Range (IQR) method.
- Scale features to a range between 0 and 1 using Min-Max scaling.

### 3. Feature Engineering and Splitting:
- Separate features (X) from the target variable (y).
- Split the data into training and testing sets.

### 4. Model Training and Evaluation:
- Train and evaluate Logistic Regression and Random Forest models using cross-validation.
- Assess the performance of the Random Forest model on the test set using various metrics: accuracy, precision, recall, F1 score, and ROC AUC.

## Metrics
The performance of the Random Forest model is evaluated using the following metrics:
- Accuracy: The ratio of correctly predicted instances to the total instances.
- Precision: The ratio of true positives to the sum of true positives and false positives.
- Recall: The ratio of true positives to the sum of true positives and false negatives.
- F1 Score: The harmonic mean of precision and recall.
- ROC AUC: The area under the Receiver Operating Characteristic curve.

## Requirements
- Python 3.x
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scikit-learn
