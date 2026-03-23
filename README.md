# Bank-Attrition-Analysis

## Overview

Customer attrition (churn) is a critical challenge in the banking industry,
as retaining existing customers is significantly more
cost-effective than acquiring new ones. This project performs a
comprehensive analysis of customer-level data to identify the key
factors influencing churn and to generate actionable insights that
support customer retention strategies.

## Problem Statement

The objective of this project is to analyze customer demographics,
financial behavior, and engagement patterns to identify the primary
drivers of attrition and help the business reduce churn through
data-driven decision-making.

## Objectives

-   Analyze customer demographics, financial attributes, and behavioral
    patterns
-   Identify key factors contributing to customer churn
-   Segment customers based on churn risk indicators
-   Evaluate the impact of satisfaction, complaints, and product usage
-   Provide actionable business recommendations to improve retention

## Dataset Description

The dataset consists of structured banking customer data, including: -
Demographics: Age, Gender, State
- Financial Attributes: Salary, Balance, Credit Score
- Product Information: Number of Products, Credit Card Ownership, Loan
Status, Fixed Deposit Status
- Behavioral Metrics: Satisfaction Score, Number of Complaints, Tenure
- Target Variable: Exited (1 = Churned, 0 = Retained)

## Tools and Technologies

-   Python (Pandas, NumPy)
-   Matplotlib, Seaborn (Visualization)
-   Plotly (Interactive Dashboard)
-   Google Colab

## Data Preparation

-   Standardized column names
-   Handled missing values using median/mode
-   Removed records with missing gender
-   Treated outliers using IQR method

## Feature Engineering

-   Debt-to-Income Ratio
-   Loyalty Score
-   High Complainer Indicator

## Exploratory Data Analysis

### Univariate Analysis

-   Majority of customers fall within mid-income segments
-   Limited product usage observed across customers

### Bivariate Analysis

-   Longer tenure → more product usage
-   Higher engagement → lower churn

### Multivariate Analysis

-   Churned customers show lower satisfaction and engagement
-   Behavioral factors dominate financial variables

## Customer Behavior & Feedback Analysis

-   Low satisfaction customers are highly prone to churn
-   Complaint frequency strongly correlates with churn
-   Loyalty score effectively captures disengagement

## Financial Analysis

-   Higher balance → lower churn probability
-   Salary alone is not a strong predictor
-   Low balance + high products → higher churn

## Product & Engagement Analysis

-   Fewer products → higher churn
-   Cross-selling improves retention
-   Engagement is key to customer stickiness

## Demographic Analysis

-   Regional differences exist in churn
-   Age groups show varied churn behavior
-   Gender has minimal impact

## Key Metrics

-   High complaint customers show significantly higher churn
-   Low satisfaction segment has highest churn concentration
-   Product engagement reduces churn risk

## Key Findings

-   Low satisfaction
-   High complaints
-   Low engagement
-   Short tenure

These are the strongest churn drivers.

## Business Recommendations

1.  Improve complaint resolution systems
2.  Target low satisfaction customers
3.  Increase cross-selling strategies
4.  Focus on early tenure engagement
5.  Implement churn monitoring

## Future Work

-   Build predictive models (Logistic Regression, Random Forest)
-   Evaluate using ROC-AUC
-   Deploy dashboard tools

## Business Impact

-   Identifies high-risk customers
-   Enables retention strategies
-   Supports data-driven decisions

## Author

Lakshay Kumar\
Business Analytics Graduate\
Data Analyst
