# Telecom Customer Churn Analysis & Prediction

## 📌 Project Overview

This project focuses on analyzing and predicting customer churn in the telecommunications industry.

The objective is to understand customer behavior, identify factors associated with customer churn, develop a machine learning model for churn prediction, and communicate actionable business insights through data visualization and an interactive Power BI dashboard.

The project follows an end-to-end data analytics and machine learning workflow using Python and Power BI.

## 🎯 Business Problem

Customer churn is a major challenge for telecommunications companies because losing existing customers can increase customer acquisition costs and negatively impact revenue.

The goal of this project is to identify customers who are more likely to churn and understand the key factors influencing customer retention.

## 🎯 Project Objectives

* Analyze customer churn patterns.
* Understand customer demographics and service usage.
* Identify factors associated with churn.
* Perform exploratory data analysis.
* Prepare and clean the dataset for modeling.
* Engineer relevant features for machine learning.
* Build a customer churn prediction model.
* Evaluate model performance using appropriate classification metrics.
* Develop an interactive Power BI dashboard.
* Generate actionable business recommendations.

## 📊 Dataset Overview

The dataset contains **7,043 customer records** with information related to:

* Customer demographics
* Customer tenure
* Contract information
* Internet services
* Phone services
* Payment methods
* Monthly charges
* Total charges
* Customer churn status

The target variable is **Churn**, which indicates whether a customer has left the company.

### Churn Distribution

* **No Churn:** approximately 73.4%
* **Churn:** approximately 26.6%

The target variable is therefore imbalanced, making metrics such as precision, recall, F1-score, and ROC-AUC important when evaluating the predictive model.

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Scikit-learn**
* **Jupyter Notebook**
* **Power BI**
* **DAX**
* **GitHub**

## 🔄 Project Workflow

The project follows these major stages:

1. Business problem understanding
2. Data loading
3. Data inspection
4. Data cleaning
5. Data preprocessing
6. Exploratory Data Analysis
7. Feature engineering
8. Customer churn analysis
9. Machine learning model development
10. Model evaluation
11. Power BI dashboard development
12. Business insights
13. Customer retention recommendations

## 🔍 Exploratory Data Analysis

The analysis investigates customer churn across several dimensions, including:

* Tenure
* Monthly Charges
* Total Charges
* Contract Type
* Payment Method
* Internet Service
* Online Security
* Online Backup
* Tech Support
* Device Protection
* Senior Citizen status
* Partner status
* Dependents
* Paperless Billing
* Phone Service

## 📈 Customer Churn Analysis

The project examines how churn varies across customer segments and service characteristics.

Particular attention is given to:

* Customer tenure
* Monthly charges
* Contract type
* Payment method
* Internet service
* Additional services
* Customer demographics

These analyses help identify customer segments that may require targeted retention strategies.

## 🤖 Machine Learning

A supervised machine learning classification approach is used to predict customer churn.

The machine learning workflow includes:

* Data preprocessing
* Missing-value handling
* Feature transformation
* Encoding categorical variables
* Feature selection
* Train-test split
* Model training
* Prediction
* Model evaluation

The model is evaluated using classification metrics appropriate for an imbalanced churn dataset.

### Evaluation Metrics

The project considers:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix
* ROC-AUC

**Note:** Model performance should be interpreted using multiple metrics rather than accuracy alone because customer churn is an imbalanced classification problem.

## 📊 Power BI Dashboard

The project includes an interactive Power BI dashboard designed to provide a business-focused view of customer churn.

The dashboard helps users analyze churn across different customer and service characteristics.

### Dashboard Analysis

The dashboard can be used to explore:

* Overall customer churn
* Churn by customer segment
* Churn by contract
* Churn by tenure
* Churn by payment method
* Churn by internet service
* Churn by monthly charges
* Churn across customer demographics

The Power BI report is available in the `PowerBI` folder.

## 🖼️ Dashboard Preview

A screenshot of the Power BI dashboard is available in the `Screenshots` folder.

The screenshot provides a quick visual overview of the dashboard, while the `.pbix` file contains the interactive Power BI report.

## 💡 Key Business Insights

The analysis highlights important customer retention patterns and identifies customer segments with comparatively higher churn risk.

Key areas of investigation include:

* Customers with shorter tenure
* Customers with higher monthly charges
* Contract type and customer commitment
* Internet service type
* Payment method
* Availability of additional support services

These factors can help businesses prioritize retention efforts.

## 💼 Business Recommendations

Based on the analysis, telecommunications companies could consider:

* Developing targeted retention programs for high-risk customer segments.
* Providing incentives for customers to move toward longer-term contracts.
* Monitoring customers with rapidly increasing or relatively high monthly charges.
* Improving customer support and technical assistance.
* Offering personalized retention incentives based on customer behavior.
* Monitoring early-tenure customers closely.
* Using predictive churn models as an early-warning system.
* Continuously monitoring churn patterns through business intelligence dashboards.

These recommendations should be combined with business context and customer-level analysis before implementation.

## 📁 Repository Structure

```text
Telecom-Customer-Churn-Analysis/
│
├── PowerBI/
│   ├── Telecom_Customer_Churn_Dashboard.pbix
│   └── README.md
│
├── Python/
│   ├── Telecom_Customer_Churn_Analysis.ipynb
│   └── README.md
│
├── Screenshots/
│   └── Telecom_Churn_Dashboard.png
│
├── README.md
└── requirements.txt
```

## 📂 Project Components

### Python Analysis

The `Python` folder contains the Jupyter Notebook used for data cleaning, exploratory analysis, feature engineering, and machine learning.

### Power BI Dashboard

The `PowerBI` folder contains the interactive Power BI dashboard.

### Dashboard Screenshot

The `Screenshots` folder contains a visual preview of the Power BI dashboard.

### Requirements

The `requirements.txt` file contains the Python libraries required to reproduce the analysis.

## 🚀 How to Run the Project

### Python Analysis

Open:

`Python/Telecom_Customer_Churn_Analysis.ipynb`

The notebook can be executed using Jupyter Notebook, JupyterLab, or Google Colab.

### Power BI Dashboard

Download:

`PowerBI/Telecom_Customer_Churn_Dashboard.pbix`

Open the file using **Power BI Desktop** to interact with the dashboard.

## ⚠️ Data Availability

The original customer-level dataset is not included in this repository.

The repository contains the analysis notebook, Power BI report, dashboard screenshot, project documentation, and required Python dependencies.

## 👩‍💻 Author

**Neha Priya**

**Skills:** Python | SQL | Power BI | Machine Learning | Data Analysis
