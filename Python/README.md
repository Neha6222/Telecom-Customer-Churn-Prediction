# Python — Telecom Customer Churn Analysis

## 📌 Overview

This folder contains the Python-based analysis and machine learning workflow developed for the Telecom Customer Churn Analysis & Prediction project.

The notebook covers the complete analytical process from data inspection and preprocessing to exploratory analysis and customer churn prediction.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## 🔍 Analytical Workflow

### 1. Data Understanding

The analysis begins with:

* Dataset inspection
* Data shape analysis
* Data type verification
* Summary statistics
* Identification of categorical and numerical variables

### 2. Data Cleaning

The preprocessing stage includes:

* Handling missing values
* Correcting data types
* Cleaning numerical fields
* Preparing the target variable
* Removing or transforming unsuitable variables

### 3. Exploratory Data Analysis

The notebook analyzes:

* Overall churn distribution
* Customer tenure
* Monthly charges
* Total charges
* Contract type
* Internet service
* Payment method
* Customer demographics
* Additional services

### 4. Feature Engineering

Relevant customer attributes are transformed into machine-learning-ready features through:

* Categorical encoding
* Numerical transformations
* Feature preparation
* Target variable preparation

### 5. Churn Prediction

A supervised classification approach is used to predict whether a customer is likely to churn.

The workflow includes:

* Train-test split
* Feature preprocessing
* Model training
* Predictions
* Model evaluation

## 📊 Model Evaluation

The predictive model is evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix
* ROC-AUC

Because the dataset contains fewer churned customers than non-churned customers, multiple evaluation metrics are considered to provide a more complete view of model performance.

## 💡 Analytical Objective

The Python analysis aims to answer two key questions:

1. **What factors are associated with customer churn?**
2. **Can machine learning identify customers who are more likely to churn?**

## 📁 Notebook

The main analysis file is:

`Telecom_Customer_Churn_Analysis.ipynb`

## ▶️ How to Run

The notebook can be opened using:

* Jupyter Notebook
* JupyterLab
* Google Colab

Install the required dependencies using:

```bash
pip install -r requirements.txt
```

## 🎯 Outcome

The Python analysis provides the analytical and machine-learning foundation for the project, while the Power BI dashboard transforms the findings into an interactive business reporting solution.
