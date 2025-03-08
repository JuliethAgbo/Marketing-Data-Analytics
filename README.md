## Marketing-Data-Analytics

## Overview
This project aims to analyze customer data and build a predictive model to determine whether a customer will subscribe to a term deposit. The dataset comes from a banking institution and contains information about customer transactions, loans, and personal details like job, marital status, and education. The dataset was cleaned, pre-processed, and used to build a Decision Tree Classifier, with its performance optimized using GridSearchCV.
## Problem Statement 
Banks run marketing campaigns to encourage customers to subscribe to term deposits, but targeting the right customers efficiently results in a challenge. This project aims to solve the problem by developing a machine learning model that can increase conversion rates and reduce waste of resources

Total Dataset: 45,210 rows and 15 columns

## Data Analytics Methodology
 1.	Data Cleaning & Preprocessing:
* Read the dataset using Pandas
* Converted categorical variables into numerical form 
* Split the data into training and testing sets.
2.	Model Training
Used GridsearchCV for hyperparameter tuning and used the decision tree classifier as the model estimator

3.	Evaluation Matrix
  The evaluation matrix was created by using a Classification Report, and Confusion Matrix

## Key findings & Result

1.	The initial Decision Tree model achieved 83% accuracy in predicting customer subscription. A further optimization was carried out while ensuring we do not overfit the model
2.	After hyperparameter tuning, the optimized model improved to 88% accuracy demonstrating the importance of fine-tuning for a better predictions
3.	At each stage of training the dataset, the model’s performance was evaluated using a confusion matrix and classification report, ensuring a balanced approach to precision and recall.

