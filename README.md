## Marketing-Data-Analytics

## Overview
This project analyzes a marketing dataset using machine learning techniques to predict customer behaviors. The dataset comes from a banking institution and contains information about customer transactions, loans, and previous interactions.
## Problem Statement 
The goal of this analysis is to predict whether a customer will subscribe to a term deposit based on their financial history and previous interactions with the bank. This will help in targeting the right customers for marketing campaigns.
# Dataset
The dataset used in this project is Bank.csv, which contains the following key columns:
balance: Customer account balance
default: Whether the customer has credit in default (yes/no)
housing: Whether the customer has a housing loan (yes/no)
loan: Whether the customer has a personal loan (yes/no)
previous: Number of previous contacts
# Total Dataset: 45,210

## Data Analytics Methodology
# 1.	Data Cleaning & Preprocessing:
* Read the dataset using Pandas
* Converted categorical variables into numerical form using OrdinalEncoder().
* Split the data into training and testing sets.
# 2.	Model Training
* Trained a Decision Tree Classifier to predict customer subscription.
* Used GridSearchCV for hyperparameter tuning.
3.	Evaluation Metric
  The evaluation metrix was created by 
o	Classification Report
o	Confusion Matrix
Results & Findings
The Decision Tree model was evaluated using classification metrics. The confusion matrix and classification report provided insights into the model’s performance.
Future Improvements
•	Try other machine learning models like Random Forest or Logistic Regression.
•	Perform feature selection to improve accuracy.
•	Implement cross-validation for better generalization.
How to Use This Repository
1.	Clone the repository:
git clone <repository-url>
2.	Install dependencies:
pip install -r requirements.txt
3.	Run the notebook using Jupyter:
