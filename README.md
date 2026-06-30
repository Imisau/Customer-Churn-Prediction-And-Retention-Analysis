# Customer-Churn-Prediction-And-Retention-Analysis

# Introduction
This project analyzes customer churn using historical customer and pricing data to identify the factors influencing customer attrition and develop a predictive machine learning model for early churn detection. Using Python, exploratory data analysis (EDA), feature engineering, and a Random Forest classifier the project provides actionable insights to help businesses improve customer retention and reduce revenue loss.

# Business Problem

Customer churn is a major challenge for subscription-based businesses, directly affecting revenue growth and customer lifetime value. Without understanding why customers leave, organizations struggle to implement effective retention strategies.
This project analyzes customer behavior, pricing, and consumption patterns to identify customers most likely to churn and recommend targeted retention strategies.

# Business Objectives
- Measure the overall customer churn rate.
- Identify the key drivers of customer attrition.
- Build a machine learning model to predict customer churn.
- Evaluate model performance using classification metrics.
- Provide actionable recommendations to improve customer retention.

# Dataset Overview

| Metric           |                 Value |
| ---------------- | --------------------: |
| Customer Records |                14,606 |
| Churn Rate       |                  9.7% |
| Data Sources     | Client & Pricing Data |
| Target Variable  |                 Churn |

# Tools And Technologies

| Category         | Tools                    |
| ---------------- | ------------------------ |
| Programming      | Python                   |
| Data Analysis    | Pandas, NumPy            |
| Visualization    | Matplotlib, Seaborn      |
| Machine Learning | Scikit-learn             |
| Model            | Random Forest Classifier |
| Notebook         | Jupyter                  |

# Project Overflow

 Client Data
      │
      ▼
 Data Cleaning
      │
      ▼
 Exploratory Data Analysis
      │
      ▼
 Feature Engineering
      │
      ▼
 Model Development
      │
      ▼
 Model Evaluation
      │
      ▼
 Business Recommendations

# Data Cleaning

- Merged customer and pricing datasets.
- Removed duplicate records.
- Handled missing values.
- Converted data types.
- Created analytical features.

# Exploratory Data Analysis

Analyzed:

- Customer churn distribution
- Energy consumption
- Pricing trends
- Contract characteristics
- Customer tenure
- Forecast consumption

# Feature Engineering

Created variables including:

- Price difference
- Average price
- Consumption trends
- Contract duration
- Customer tenure

# Machine Learning

Model Used:

#### Random Forest Classifier

Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Feature Importance

![](https://github.com/Imisau/Customer-Churn-Prediction-And-Retention-Analysis/blob/main/Forest%20cls1.png)
![](https://github.com/Imisau/Customer-Churn-Prediction-And-Retention-Analysis/blob/main/Forest%20cl2.png)
![](https://github.com/Imisau/Customer-Churn-Prediction-And-Retention-Analysis/blob/main/Forest%20cls3.png)
![](https://github.com/Imisau/Customer-Churn-Prediction-And-Retention-Analysis/blob/main/Forest%20cls4.png)
  # Key Result

| KPI                | Result    |
| ------------------ | --------- |
| Customers Analyzed | 14,606    |
| Churn Rate         | **9.7%**  |
| Model Accuracy     | **90.3%** |
| Precision          | **78.3%** |

# Key Insights

1. Low Overall Churn

Only 9.7% of customers churned, indicating relatively strong customer retention.

2. Pricing Influences Churn

Customers experiencing higher pricing changes showed an increased likelihood of leaving.

3. Consumption Patterns Matter

Lower and declining energy consumption was associated with higher churn risk.

4. Customer Tenure

Newer customers were more likely to churn than long-term customers.

5. Contract Characteristics
Contract-related variables significantly influenced churn probability.

# Business Recommendations
-  Identify high-risk customers before contract renewal.
- Offer targeted retention incentives to customers experiencing significant price increases.
- Monitor declining energy consumption as an early churn signal.
- Prioritize retention campaigns for new customers during their first year.
- Integrate predictive churn scores into CRM systems to support proactive customer engagement.

# Business Value Delivered
- Measured a 9.7% customer churn rate across 14,606 customers.
- Built a Random Forest model with 90.3% accuracy and 78.3% precision.
- Identified the primary behavioral and pricing drivers of churn.
- Produced actionable recommendations to improve customer retention and support data-driven decision-making.

 # Repository Structure
![](https://github.com/Imisau/Customer-Churn-Prediction-And-Retention-Analysis/blob/main/Repository%20%20Structure.png)

# Skills Demonstrated

- Python
- Pandas
- NumPy
- Scikit-learn
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Data Cleaning
- Statistical Analysis
- Machine Learning
- Predictive Analytics
- Business Intelligence
- Data Storytelling
  
