"Customer Churn Analysis"

Project Overview

This project analyzes customer churn trends using Python and various data visualization techniques. The dataset consists of customer demographics, subscription details, and usage patterns.
The goal is to identify key factors that influence churn and provide insights to reduce customer attrition.

"Dataset"

The dataset includes the following columns:

"Customer Details": Customer ID, Gender, Senior Citizen status, Partner, Dependents
"Service Usage": Tenure, Phone Service, Multiple Lines, Internet Service, Online Security, Online Backup, Device Protection, Tech Support, Streaming TV, Streaming Movies
"Subscription Details": Contract Type, Paperless Billing, Payment Method, Monthly Charges, Total Charges
"Churn": Indicates whether the customer has churned

"Data Processing"

Handled missing values by replacing blanks in TotalCharges with 0
Converted SeniorCitizen from 0/1 to Yes/No for better readability
Checked for duplicates and verified data consistency

"Exploratory Data Analysis (EDA)"

Churn Rate:   26.54% of customers have churned
Demographic Trends:   Senior citizens show a higher churn rate
Subscription Insights:   Customers with month-to-month contracts are more likely to churn than those with yearly contracts
Service Usage Impact:  Fiber optic users have a higher churn rate compared to DSL users
Lack of online security, tech support, and device protection increases churn likelihood
Customers without online backup or streaming subscriptions also show higher churn tendencies
Payment Method Impact:   Customers using electronic checks are more likely to churn

"Visualizations"

Count plots for churn distribution by gender, senior citizen status, contract type, and payment method
Histograms and pie charts to visualize tenure, service usage, and churn percentages
Stacked bar plots showing churn across different categories

"Conclusion"

Key takeaways from this analysis suggest that:
Long-term contracts reduce churn
Providing better tech support, online security, and device protection can improve retention
Encouraging customers to switch from electronic check payments to automatic bank transfers or credit cards may reduce churn

"Technologies used"

""Libraries":Pandas, NumPy, Matplotlib, Seaborn
"Data Processing": Cleaning, transforming, and visualizing customer churn trends
