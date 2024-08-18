# Credit Card Transaction Analysis

## Overview

This project provides a comprehensive analysis of credit card transaction data to uncover spending patterns and identify potential fraud. The analysis spans various demographic groups (age and gender) and spending categories, focusing on detecting trends and anomalies in transaction data.

## Objectives

- **Demographic Analysis**: Examine how age groups and genders affect spending behavior.
- **Fraud Detection**: Identify high-risk categories and demographic groups for fraudulent transactions.
- **Trend Analysis**: Track and visualize monthly variations in transaction and fraud patterns.

## Data Description

The project utilizes two primary datasets:

1. **Transaction Data**: Contains details about each transaction, including:
   - `transaction_id`: Unique identifier for each transaction.
   - `age`: Age of the cardholder.
   - `gender`: Gender of the cardholder (e.g., Male, Female).
   - `transaction_amount`: Amount spent in the transaction.
   - `transaction_type`: Type of transaction (e.g., Grocery Pos, Shopping Net).

2. **Fraud Data**: Flags transactions as fraudulent or legitimate, including:
   - `transaction_id`: Unique identifier for each transaction.
   - `is_fraud`: Boolean flag indicating if the transaction is fraudulent.

## Key Findings

### Age and Spending Patterns
- **High Spend by Millennials and Gen X**: The analysis reveals that Millennials (ages 25-40) and Gen X (ages 41-56) are the highest spenders compared to other age groups. This indicates that these demographics have greater purchasing power or spend more frequently.

### Fraudulent Categories
- **High Fraud Risk in Certain Categories**: Fraudulent transactions are notably higher in categories such as 'Grocery Pos' and 'Shopping Net'. This suggests that these types of transactions are more susceptible to fraudulent activities.

### Monthly Trends
- **Seasonal Variations**: There are significant fluctuations in transaction volumes and fraud rates throughout the year. For instance, fraud rates tend to spike during holiday seasons, possibly due to increased transaction volumes and shopping activity.

### Fraud by Profession: 
Interestingly, professions such as Materials Engineers and Trading Standards Officers saw the highest counts of fraud cases, potentially reflecting the correlation between job roles and the likelihood of being targeted by fraud.

### License
This project is licensed under the MIT License. See the LICENSE file for details.
