# Telecom Customer Churn Prediction & Customer Segmentation using Machine Learning


##  Project Overview

Customer churn is one of the biggest challenges faced by subscription-based businesses such as telecom companies. Retaining existing customers is significantly more cost-effective than acquiring new ones.

This project develops an end-to-end **Machine Learning pipeline** to:

- Predict customers who are likely to churn.
- Identify the key factors influencing customer attrition.
- Segment customers into meaningful groups using clustering.
- Generate actionable business insights for customer retention strategies.

The project combines **Supervised Learning (Random Forest Classification)** and **Unsupervised Learning (K-Means Clustering)** to provide both predictive and analytical solutions.

---

## Business Problem

Telecom companies lose significant revenue when customers discontinue their services.

The objective of this project is to answer two important business questions:

- Which customers are likely to churn?
- How can customers be grouped for targeted marketing and retention campaigns?

---

## Dataset

**Dataset:** Telecom Customer Churn Dataset

The dataset contains customer demographic information, subscription details, service usage, billing information, and churn status.

### Important Features

- Gender
- Senior Citizen
- Partner
- Dependents
- Tenure Months
- Phone Service
- Internet Service
- Online Security
- Online Backup
- Device Protection
- Tech Support
- Streaming TV
- Streaming Movies
- Contract Type
- Payment Method
- Monthly Charges
- Total Charges
- Customer Lifetime Value (CLTV)
- Churn Label

---

#  Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

#  Project Workflow

```
Dataset
    │
    ▼
Exploratory Data Analysis
    │
    ▼
Data Cleaning & Preprocessing
    │
    ▼
Feature Engineering
    │
    ▼
Random Forest Classification
    │
    ▼
Model Evaluation
    │
    ▼
Hyperparameter Tuning
    │
    ▼
Cross Validation
    │
    ▼
ROC-AUC Analysis
    │
    ▼
Customer Segmentation (K-Means)
    │
    ▼
Business Insights
```

---

#  Exploratory Data Analysis

Performed detailed exploratory analysis using various visualizations.

### Analysis Included

- Customer Churn Distribution
- Contract Type Analysis
- Monthly Charges Distribution
- Tenure Distribution
- Internet Service Analysis
- Payment Method Analysis
- Tech Support Analysis
- Correlation Heatmap
- Contract vs Churn Comparison

---

#  Data Preprocessing

The preprocessing pipeline includes:

- Handling missing values
- Converting Total Charges into numeric format
- Removing unnecessary columns
- One-Hot Encoding categorical variables
- Feature selection
- Train-Test Split

---

#  Machine Learning Model

The primary classification model used is:

## Random Forest Classifier

Random Forest was selected because it:

- Handles non-linear relationships effectively.
- Is robust against overfitting.
- Performs well with mixed numerical and categorical features.
- Provides feature importance scores.

---

## Model Improvements

The model was further enhanced by:

- Handling class imbalance using Balanced Random Forest
- Hyperparameter tuning
- Feature importance analysis
- Cross Validation

---

#  Model Evaluation

The model was evaluated using multiple classification metrics:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC Curve
- ROC-AUC Score
- Cross Validation

###  ROC-AUC Score

**ROC-AUC = 0.857**

The ROC curve demonstrates good discriminative ability, indicating that the model effectively distinguishes between customers who churn and customers who remain.

---

#  Customer Segmentation

To complement churn prediction, customers were segmented using **K-Means Clustering**.

### Steps Performed

- Feature Scaling
- Elbow Method
- K-Means Clustering
- Cluster Visualization
- Cluster Profiling

The resulting customer segments can be used for:

- Personalized marketing
- Customer retention campaigns
- Loyalty programs
- Targeted promotional offers

---

#  Key Business Insights

- Customers with Month-to-Month contracts are significantly more likely to churn.
- Long-tenure customers are generally more loyal.
- Higher monthly charges are associated with increased churn.
- Customers subscribed to Tech Support and Online Security exhibit lower churn rates.
- Customer segmentation enables targeted retention strategies for different customer groups.

---

#  Repository Structure

```
Telecom-Churn-Prediction-and-Customer-Segmentation-using-Machine-Learning/
│
├── README.md
├── requirements.txt
│
├── data/
│   ├── Telecom_Churn_Prediction_and_Customer_Segmentation.ipynb
│
└── Images/
    ├── churn_distribution.png
    ├── correlation_heatmap.png
    ├── roc_curve.png
    ├── SHAP_summary_plot.png
    └── customer_clusters.png
```

---

#  Skills Demonstrated

- Machine Learning
- Customer Analytics
- Classification
- Clustering
- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis
- Data Visualization
- Model Evaluation
- Business Intelligence

---

#  Acknowledgement

This project was developed as part of my **Summer Internship Programme** at **Coding Blocks School Of Technology (CBSOT)**.

I sincerely thank my mentors and the CBSOT team for their continuous guidance, valuable feedback, and support throughout the project.

---

##  Author

**Devika Dinesh**

MS Artificial Intelligence & Data Science

ABV-Indian Institute of Information Technology and Managaement, Gwalior, Madhya Pradesh

GitHub: https://github.com/devikadinesh2003

LinkedIn: www.linkedin.com/in/devika-dinesh-354b9023a



---
