# FUTURE_DS_02

Telco Customer Churn Prediction

Project Overview

Customer churn is a major challenge for telecom companies. Retaining existing customers is more cost-effective than acquiring new ones.
In this project, I built a Machine Learning model to predict whether a telecom customer will churn or not based on their service usage, contract details, and billing information.
The goal is to help companies identify customers who are likely to leave and take preventive actions.

Dataset

Dataset used: Telco Customer Churn Dataset
The dataset contains information about:
Customer demographics
Account information
Services subscribed
Billing details
Churn status
Target Variable
Churn
Yes → Customer left the company
No → Customer stayed
Total Records: 7032
Features: 30+

 Tools & Technologies
 
Programming
Python
Libraries
Data Handling
pandas
numpy
Data Visualization
matplotlib
seaborn
plotly
Data Preprocessing
sklearn preprocessing
LabelEncoder
OneHotEncoder
StandardScaler
MinMaxScaler
Machine Learning
Logistic Regression
KNN
Support Vector Machine
Decision Tree
Random Forest
Gradient Boosting
AdaBoost
XGBoost
Naive Bayes
Model Evaluation
accuracy_score
classification_report
confusion_matrix

Project Workflow

Data Loading
Loaded dataset using pandas
Checked dataset structure and column types
Data Cleaning
Removed customerID
Converted TotalCharges from object → numeric
Removed missing values
Exploratory Data Analysis (EDA)
EDA was performed to understand customer behavior.
Visualizations used:
Churn distribution (Pie chart)
Count plots for categorical variables
Histogram plots for:
Tenure
Monthly Charges
Total Charges
Density plots to compare churn vs non-churn customers

Key insights:

Customers with higher monthly charges tend to churn more
Customers with short tenure are more likely to churn
Long-term customers usually stay with the company
Data Preprocessing
Steps performed:
Label Encoding
Converted target variable Churn into numeric values.
One-Hot Encoding
Converted categorical variables into numerical format.
Feature Scaling
Applied StandardScaler to numerical features.
Train-Test Split
80% training data
20% testing data
Machine Learning Models Tested
The following models were trained and evaluated:
Random Forest
Gradient Boosting
Support Vector Machine (SVM)
Logistic Regression
K-Nearest Neighbors
Decision Tree
AdaBoost
XGBoost
Naive Bayes
Hyperparameter tuning was performed using GridSearchCV.

 Model Performance

Model
Accuracy
Random Forest
0.788
Gradient Boosting
0.798
SVM
0.725
Logistic Regression
0.726
KNN
0.755
Decision Tree
0.750
AdaBoost
0.795
XGBoost
0.794
Naive Bayes
0.645
Best Model: Gradient Boosting
Accuracy: ~79.8%
 Model Comparison Visualization
A bar chart was created to compare the accuracy of all machine learning models.
This helps identify which algorithm performs best for the churn prediction problem.

Key Insights:

Customers with short tenure are more likely to churn

Customers with higher monthly charges have higher churn probability

Machine learning models can help companies predict churn and improve retention strategies
