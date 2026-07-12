# Customer Segmentation Analysis using Machine Learning

<div align="center">

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-success)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue)

### Customer Analytics • Machine Learning • K-Means Clustering • Business Intelligence

</div>

---

# Project Overview

Customer segmentation is one of the most valuable applications of **Unsupervised Machine Learning** in business analytics. Organizations use customer segmentation to understand purchasing behavior, improve customer engagement, personalize marketing campaigns, and maximize revenue.

This project implements an end-to-end **Customer Segmentation Pipeline** using the **K-Means Clustering Algorithm** on the Mall Customers Dataset. The workflow includes data preprocessing, exploratory data analysis (EDA), feature engineering, clustering, model evaluation, visualization, and business recommendations.

The final output groups customers into meaningful segments based on their **Annual Income** and **Spending Score**, enabling data-driven business decision-making.

---

# Project Objectives

- Perform comprehensive Exploratory Data Analysis (EDA)
- Understand customer demographics and purchasing behavior
- Clean and preprocess customer data
- Apply feature scaling for clustering
- Determine the optimal number of clusters using the Elbow Method
- Build a K-Means clustering model
- Evaluate clustering quality using Silhouette Score
- Visualize customer segments
- Generate business insights and marketing strategies

---

# Dataset Information

**Dataset:** Mall Customers Dataset

| Feature | Description |
|----------|-------------|
| CustomerID | Unique customer identifier |
| Gender | Male / Female |
| Age | Customer age |
| Annual Income (k$) | Annual income in thousand dollars |
| Spending Score (1–100) | Customer spending score assigned by the mall |

Dataset Size

- 200 Customers
- 5 Features
- No Missing Values

---

# Technology Stack

| Category | Technologies |
|----------|--------------|
| Programming Language | Python |
| Development Environment | Jupyter Notebook |
| Data Analysis | Pandas, NumPy |
| Data Visualization | Matplotlib |
| Machine Learning | Scikit-Learn |
| Model | K-Means Clustering |

---

# Machine Learning Workflow

```
Data Collection
        │
        ▼
Data Cleaning
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Feature Selection
        │
        ▼
Feature Scaling
        │
        ▼
Elbow Method
        │
        ▼
K-Means Clustering
        │
        ▼
Cluster Evaluation
        │
        ▼
Business Insights
```

---

# Exploratory Data Analysis

The notebook performs comprehensive exploratory data analysis including

- Dataset Overview
- Statistical Summary
- Missing Value Analysis
- Duplicate Record Detection
- Age Distribution
- Gender Distribution
- Annual Income Distribution
- Spending Score Distribution
- Age vs Spending Score
- Annual Income vs Spending Score
- Gender-wise Customer Analysis
- Correlation Matrix
- Customer Demographics
- Customer Behaviour Analysis

---

# Data Preprocessing

The following preprocessing techniques were applied before model training.

✔ Missing Value Detection

✔ Duplicate Record Check

✔ Feature Selection

✔ Standard Feature Scaling

Selected Features

- Annual Income (k$)
- Spending Score (1-100)

---

# Model Development

The project uses the **K-Means Clustering Algorithm**, an unsupervised learning algorithm that partitions customers into groups with similar characteristics.

## Steps

- Feature Scaling
- Elbow Method
- Optimal Cluster Selection
- Model Training
- Cluster Prediction
- Cluster Visualization
- Cluster Evaluation

---

# Model Evaluation

Evaluation Metric

- Silhouette Score

The Silhouette Score measures how well each customer belongs to its assigned cluster.

Higher values indicate better cluster separation.

---

# Data Visualizations

The notebook contains multiple professional visualizations including

- Customer Age Distribution
- Gender Distribution
- Annual Income Distribution
- Spending Score Distribution
- Age vs Income
- Age vs Spending Score
- Income vs Spending Score
- Customer Distribution by Gender
- Average Spending by Gender
- Average Income by Gender
- Correlation Matrix
- Elbow Method
- Customer Cluster Visualization
- Cluster Distribution
- Cluster Centers
- Customer Profile Summary

---

# Customer Segments

The K-Means algorithm successfully groups customers into five major segments.

### Cluster 1

Premium Customers

Characteristics

- High Income
- High Spending

Recommendation

- VIP Membership
- Exclusive Offers
- Loyalty Programs

---

### Cluster 2

Potential Customers

Characteristics

- High Income
- Low Spending

Recommendation

- Personalized Marketing
- Product Recommendations
- Premium Promotions

---

### Cluster 3

Regular Customers

Characteristics

- Average Income
- Average Spending

Recommendation

- Seasonal Discounts
- Bundle Offers

---

### Cluster 4

Value Customers

Characteristics

- Low Income
- High Spending

Recommendation

- Reward Programs
- Discount Coupons

---

### Cluster 5

Low Engagement Customers

Characteristics

- Low Income
- Low Spending

Recommendation

- Awareness Campaigns
- Entry-Level Products

---

# Business Insights

This project enables businesses to

- Identify premium customers
- Improve customer retention
- Increase marketing efficiency
- Personalize promotional campaigns
- Optimize customer engagement
- Increase overall profitability
- Understand customer purchasing behaviour
- Support data-driven decision making

---

# Project Structure

```
Customer-Segmentation-Analysis
│
├── Customer_Segmentation_Project.ipynb
├── Mall_Customers.csv
├── README.md
├── requirements.txt
│
├── images
│   ├── age_distribution.png
│   ├── gender_distribution.png
│   ├── income_distribution.png
│   ├── spending_distribution.png
│   ├── elbow_method.png
│   ├── customer_clusters.png
│   └── correlation_matrix.png
│
└── output
    └── Customer_Segmentation_Result.csv
```

---

# Future Enhancements

- Hierarchical Clustering
- DBSCAN Clustering
- Gaussian Mixture Models
- PCA for Dimensionality Reduction
- Interactive Plotly Visualizations
- Power BI Dashboard
- Customer Lifetime Value Prediction
- Customer Churn Prediction
- Real-Time Customer Analytics Dashboard

---

# Installation

Clone the repository

```bash
git clone https://github.com/Gurusaiprasadreddy/Customer-Segmentation-Analysis.git
```

Navigate to the project directory

```bash
cd Customer-Segmentation-Analysis
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

---

# Requirements

```
Python 3.10+

pandas

numpy

matplotlib

scikit-learn

jupyter
```

---

# Learning Outcomes

Through this project you will gain practical experience in

- Exploratory Data Analysis
- Customer Analytics
- Data Cleaning
- Data Visualization
- Feature Engineering
- Unsupervised Machine Learning
- K-Means Clustering
- Feature Scaling
- Cluster Evaluation
- Business Intelligence
- Marketing Analytics

---

# Author

## Guru Sai Prasad Reddy

**B.Tech Computer Science and Engineering**

Amrita Vishwa Vidyapeetham

GitHub

https://github.com/Gurusaiprasadreddy

LinkedIn

(Add Your LinkedIn URL)

---

# License

This project is released under the MIT License.

---

<div align="center">

⭐ If you found this project useful, consider giving it a star on GitHub.

</div>
