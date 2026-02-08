# Telecom Customer Churn Analysis

## Overview

This project analyzes the **Telco Customer Churn dataset** sourced from Kaggle to understand customer attrition patterns and identify key drivers of churn.

The objective is to simulate how a telecom company would use data analytics to:
- Monitor churn rate
- Measure revenue at risk
- Segment customers by tenure and value
- Design data-driven retention strategies

The project integrates Python for data preprocessing, SQL for business problem analysis, and Power BI for dashboard visualization.

---

## Tech Stack

- **Python (Pandas)** – Data cleaning and preprocessing
- **SQL (MySQL / BigQuery syntax)** – Business-driven churn analysis
- **Power BI** – Interactive dashboard development

---

## Dataset Source

### Telco Customer Churn Dataset (Kaggle)

[https://www.kaggle.com/datasets/blastchar/telco-customer-churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

---

## Repository Structure

### 📊 Dashboard

Contains Power BI dashboard screenshots visualizing churn rate, revenue at risk, tenure segmentation, and customer risk categories.

### 📁 Dataset

Includes:

- Raw dataset
- Cleaned dataset used for analysis and visualization

### 🐍 Python

Contains preprocessing scripts used to:

- Handle missing values
- Convert categorical variables
- Create churn indicators
- Engineer tenure and segmentation features

### 📝 SQL Query

Business-oriented SQL queries answering core churn-related questions such as contract impact, tenure segmentation, revenue loss, and risk categorization.

### 📈 SQL Query Results

Contains query outputs used to validate KPIs and dashboard metrics.

---

## Cleaned Dataset – Data Dictionary

The cleaned dataset (**WA_Fn-UseC_-Telco-Customer-Churn_cleaned.csv**) includes the following key variables:

| Column Name | Description |
|---|---|
| customerID | Unique identifier for each customer |
| gender | Customer gender |
| SeniorCitizen | Indicates whether customer is a senior citizen (1 = Yes, 0 = No) |
| Partner | Whether the customer has a partner |
| Dependents | Whether the customer has dependents |
| tenure | Number of months the customer has stayed with the company |
| PhoneService | Whether the customer has phone service |
| MultipleLines | Whether multiple phone lines are active |
| InternetService | Type of internet service (DSL, Fiber optic, None) |
| OnlineSecurity | Whether online security service is subscribed |
| OnlineBackup | Whether online backup service is subscribed |
| DeviceProtection | Whether device protection service is subscribed |
| TechSupport | Whether tech support service is subscribed |
| StreamingTV | Streaming TV subscription |
| StreamingMovies | Streaming movies subscription |
| Contract | Contract type (Month-to-month, One year, Two year) |
| PaperlessBilling | Paperless billing indicator |
| PaymentMethod | Payment method used by the customer |
| MonthlyCharges | Monthly subscription charges |
| TotalCharges | Total amount charged to the customer |
| Churn | Target variable indicating whether customer left (Yes/No or Boolean) |

---

## Analytical Scope

The project includes the following analytical components:

- Overall churn rate calculation
- Contract-wise churn comparison
- Tenure-based churn segmentation
- Revenue at risk estimation
- Payment method impact on churn
- Value vs Risk segmentation
- CLV and average tenure comparison

### Advanced SQL Techniques Applied

- Common Table Expressions (CTEs)
- Conditional segmentation logic
- Churn rate calculations
- Revenue risk percentage
- Ranking functions

---

## Key Business Insights

- **Contract Impact**: A significant portion of churn occurs among month-to-month contract customers.
- **Tenure Effect**: Early-tenure customers show the highest churn probability.
- **Pricing Sensitivity**: Higher monthly charge customers tend to churn more frequently.
- **Revenue Exposure**: A measurable percentage of total revenue is directly exposed to churn risk.

---

## Business Objective

To identify **high-risk customer segments** and **revenue exposure** so that targeted retention strategies, pricing adjustments, and contract restructuring can be implemented.
