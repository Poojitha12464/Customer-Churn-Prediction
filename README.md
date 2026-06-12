# Customer-Churn-Prediction
# Customer Churn Prediction Using Deep Learning

## Project Overview

Customer churn is one of the biggest challenges faced by telecom companies. This project uses Deep Learning to predict whether a customer is likely to churn based on their demographic, service, and billing information.

The project also includes an interactive Power BI Dashboard that provides business insights into customer behavior, churn patterns, revenue impact, and customer segmentation.

---

## Problem Statement

Telecom companies lose revenue when customers discontinue their services. Identifying customers who are likely to churn allows businesses to take preventive actions and improve customer retention.

The objective of this project is to:

* Predict customer churn using Deep Learning.
* Analyze customer behavior through Exploratory Data Analysis (EDA).
* Build an interactive dashboard for business decision-making.
* Generate actionable insights for customer retention.

---

## Dataset

Dataset: Telco Customer Churn Dataset

Features include:

* Gender
* Senior Citizen
* Partner
* Dependents
* Tenure
* Phone Service
* Internet Service
* Contract Type
* Payment Method
* Monthly Charges
* Total Charges
* Churn Status

Target Variable:

* Churn (Yes / No)

---

## Technologies Used

### Programming & Analytics

* Python
* Pandas
* NumPy

### Visualization

* Matplotlib
* Seaborn
* Power BI

### Machine Learning

* TensorFlow
* Keras
* Scikit-Learn

---

## Project Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Data Preprocessing
6. Deep Learning Model Development
7. Model Training & Evaluation
8. Dashboard Development
9. Deployment & Documentation

---

## Exploratory Data Analysis

Performed analysis on:

* Churn Distribution
* Contract Type vs Churn
* Internet Service vs Churn
* Monthly Charges vs Churn
* Tenure vs Churn
* Revenue Analysis
* Customer Segmentation

Key Findings:

* Month-to-month customers have a higher churn rate.
* Customers with shorter tenure are more likely to churn.
* Higher monthly charges increase churn probability.
* Certain internet service plans show higher churn rates.

---

## Deep Learning Model

Model Architecture:

* Input Layer
* Dense Layer (64 Neurons, ReLU)
* Dense Layer (32 Neurons, ReLU)
* Output Layer (1 Neuron, Sigmoid)

Loss Function:

* Binary Cross Entropy

Optimizer:

* Adam

Evaluation Metrics:

* Accuracy
* Precision
* Recall
* F1 Score

---

## Dashboard Features

### Executive Overview

* Total Customers
* Churned Customers
* Churn Rate
* Total Revenue
* Revenue Lost Due to Churn

### Customer Analysis

* Gender Analysis
* Age Group Analysis
* Contract Type Analysis
* Tenure Analysis

### Churn Insights

* Churn Categories
* Churn Reasons
* Internet Service Impact
* Customer Segmentation

---

## Results

The Deep Learning model successfully predicts customer churn and helps identify high-risk customers.

Business users can leverage dashboard insights to:

* Improve customer retention
* Reduce churn rate
* Increase revenue
* Develop targeted marketing strategies

---

## Future Improvements

* Hyperparameter Tuning
* Explainable AI (SHAP)
* Real-time Prediction System
* Streamlit Web Application
* Cloud Deployment

---

## Repository Structure

customer-churn-prediction/

├── data/

├── notebooks/

├── dashboard/

├── models/

├── screenshots/

├── README.md

├── requirements.txt

└── churn_model.h5
