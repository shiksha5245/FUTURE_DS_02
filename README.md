
# 📊 FUTURE_DS_02 — Telco Customer Churn Prediction

## 📌 Project Overview

Customer churn is one of the most significant challenges faced by telecommunications companies. Acquiring new customers is considerably more expensive than retaining existing ones, making churn prediction a critical business objective.

This project develops a **Machine Learning-based Customer Churn Prediction System** that analyzes customer demographics, service subscriptions, contract details, and billing information to predict whether a customer is likely to leave the company. The insights generated from this model can help businesses implement proactive retention strategies and improve customer loyalty.

---

# 🎯 Objectives

- Predict whether a customer is likely to churn.
- Analyze customer behavior using Exploratory Data Analysis (EDA).
- Compare multiple Machine Learning algorithms.
- Identify the most effective predictive model.
- Generate business insights to support customer retention strategies.

---

# 📂 Dataset

**Dataset:** Telco Customer Churn Dataset

The dataset contains information about telecom customers, including:

- Customer Demographics
- Account Information
- Services Subscribed
- Contract Type
- Payment Method
- Billing Information
- Monthly Charges
- Total Charges
- Customer Tenure
- Churn Status

### Dataset Summary

- **Total Records:** 7,032
- **Features:** 30+
- **Target Variable:** Churn

| Value | Meaning |
|-------|---------|
| **Yes** | Customer left the company |
| **No** | Customer stayed with the company |

---

# 🛠️ Technologies Used

## Programming Language

- Python

## Data Analysis

- Pandas
- NumPy

## Data Visualization

- Matplotlib
- Seaborn
- Plotly

## Data Preprocessing

- LabelEncoder
- OneHotEncoder
- StandardScaler
- MinMaxScaler

## Machine Learning

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Decision Tree
- Random Forest
- Gradient Boosting
- AdaBoost
- XGBoost
- Naive Bayes

## Model Evaluation

- Accuracy Score
- Confusion Matrix
- Classification Report
- GridSearchCV

---

# 🔄 Project Workflow

## 1. Data Loading

- Loaded the dataset using Pandas.
- Inspected dataset structure and data types.
- Reviewed missing values and feature distributions.

---

## 2. Data Cleaning

- Removed the `customerID` column.
- Converted `TotalCharges` from object to numeric format.
- Handled missing values.
- Verified data consistency.

---

## 3. Exploratory Data Analysis (EDA)

Comprehensive visualizations were created to understand customer behavior and identify factors influencing churn.

### Visualizations

- Churn Distribution
- Count Plots
- Histograms
- Density Plots
- Correlation Analysis
- Feature Distribution Charts

### Key Findings

- Customers with higher monthly charges are more likely to churn.
- Customers with shorter tenure exhibit significantly higher churn rates.
- Long-term customers tend to remain loyal.
- Contract type and payment method influence churn behavior.

---

## 4. Data Preprocessing

The following preprocessing techniques were applied:

### Label Encoding

Converted the target variable (`Churn`) into numerical values.

### One-Hot Encoding

Encoded categorical variables into machine-readable features.

### Feature Scaling

Applied **StandardScaler** to normalize numerical features.

### Train-Test Split

- **Training Data:** 80%
- **Testing Data:** 20%

---

## 5. Machine Learning Models

The following classification algorithms were trained and evaluated:

- Random Forest
- Gradient Boosting
- Support Vector Machine (SVM)
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- AdaBoost
- XGBoost
- Naive Bayes

Hyperparameter tuning was performed using **GridSearchCV** to optimize model performance.

---

# 📈 Model Performance

| Model | Accuracy |
|--------|---------:|
| Gradient Boosting | **79.8%** ⭐ |
| AdaBoost | 79.5% |
| XGBoost | 79.4% |
| Random Forest | 78.8% |
| KNN | 75.5% |
| Decision Tree | 75.0% |
| Logistic Regression | 72.6% |
| SVM | 72.5% |
| Naive Bayes | 64.5% |

---

# 🏆 Best Performing Model

## Gradient Boosting

**Accuracy:** **79.8%**

### Why It Performed Best

- High predictive accuracy
- Strong generalization capability
- Effective handling of complex relationships
- Reduced overfitting through boosting
- Robust performance on structured tabular data

---

# 📊 Model Comparison

A comparative bar chart was created to evaluate the performance of all machine learning models.

The visualization enables quick identification of the best-performing algorithm and provides an overall comparison of model effectiveness.

---

# 🔍 Key Insights

- Customers with **short tenure** are significantly more likely to churn.
- Higher **monthly charges** are associated with increased churn probability.
- Customers on **long-term contracts** demonstrate higher retention.
- Contract type and billing preferences influence customer loyalty.
- Machine learning enables telecom companies to identify at-risk customers before they leave.

---

# 💡 Business Recommendations

Based on the analysis, telecom companies can reduce customer churn by:

- Offering loyalty rewards to long-term customers.
- Providing personalized retention offers for high-risk customers.
- Reviewing pricing strategies for customers with high monthly charges.
- Promoting long-term contract plans through targeted incentives.
- Deploying predictive churn models for proactive customer engagement.

---

# 📁 Project Structure

```text
FUTURE_DS_02/
│
├── FUTURE_DS_02.ipynb
├── Telco-Customer-Churn.csv
├── README.md
├── requirements.txt
└── images/
    ├── churn_distribution.png
    ├── tenure_histogram.png
    ├── monthly_charges.png
    ├── confusion_matrix.png
    └── model_comparison.png
```

---

# 🚀 Future Enhancements

- Deploy the model using Streamlit or Gradio.
- Build a real-time churn prediction web application.
- Integrate explainable AI (SHAP/LIME) for model interpretability.
- Automate model retraining with new customer data.
- Explore deep learning models for improved predictive performance.

---

# 🎯 Conclusion

This project demonstrates how machine learning can be effectively applied to predict customer churn in the telecommunications industry. By leveraging customer demographics, service usage, contract details, and billing information, the model identifies customers at risk of leaving with a high level of accuracy.

Among all evaluated algorithms, **Gradient Boosting** achieved the best performance with an accuracy of approximately **79.8%**. The insights derived from this analysis can help telecom companies implement proactive retention strategies, optimize customer engagement, and reduce revenue loss due to churn.

Overall, this project showcases the practical application of data analytics and machine learning in solving a real-world business problem while supporting data-driven decision-making.
