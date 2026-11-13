### 🛒 E-Commerce Customer Churn Analysis (EDA)
### 📌 Project Overview
This project performs an Exploratory Data Analysis (EDA) on an E-Commerce customer dataset containing 50,000 records and 48 features. The primary objective is to uncover patterns in customer purchasing behavior, engagement metrics, satisfaction levels, and key drivers behind customer churn.

### 📊 Dataset Summary
Dataset File: E-commerce_Customer_Churn_2026.csv

Total Records: 50,000 customers

Total Features: 48 columns (demographic, behavioral, transactional, and churn-related metrics)

Overall Churn Rate: ~41.31% (58.7% retained vs. 41.3% churned)

Average Customer Tenure: ~30 months

Average Total Spend: $25,039.36

Average Churn Risk Score: 41.16 / 100

Average Customer Satisfaction Score: 3.01 / 5.0

Average Support Tickets Raised: 9.41 tickets

Average Customer Health Score: 88.60

Average Retention Probability: 44.78%

Average Revenue Impact due to Churn: $4,135.55

### 🧹 Data Cleaning & Preprocessing
Duplicate Check: 

Verified that there are 0 duplicate rows in the dataset.

Missing Value Handling:

Identified missing values in three categorical columns and imputed them appropriately:

subscription_type (13,142 missing) 

→ Filled with "unknown"

prevention_method (36,874 missing) 

→ Filled with "Not Recorded"

social_media_engagement (15,004 missing) 

→ Filled with "unknown"

### 🔍 Exploratory Data Analysis & Key Insights
1. Customer Churn Distribution
58.7% of customers remain active with the company, whereas 41.3% have churned—indicating a significant retention challenge that requires targeted intervention.
2. Customer Segment Distribution
The Consumer segment holds the largest share of the customer base, followed by Premium and Small Business.
The Enterprise segment has the lowest customer count.
3. Geographical Distribution (Top 5 Countries)
Among the top 5 countries by customer volume, Singapore leads with the highest number of customers.
4. Churn Reason Analysis
Analyzed primary reasons for customer attrition (such as Found Alternative and Poor Customer Service) to identify actionable areas for improving customer retention.

### 🛠️ Technologies & Libraries Used
Python 3

Pandas – Data manipulation and analysis

NumPy – Numerical operations

Matplotlib & Seaborn – Data visualization

