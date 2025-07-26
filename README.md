# Telco Customer Churn Analysis - EDA

![Dashboard Preview](https://github.com/ontu001/Telco-Customer-Churn-Analysis---EDA_Python/blob/main/dashboard/dashboard%200.jpg)

## Overview
Exploratory Data Analysis of customer churn patterns in the telecommunications industry. This project identifies key attrition drivers and provides actionable retention strategies through data visualization and statistical analysis.

## Key Insights
- 26.5% overall churn rate with critical segments:
  - 42.7% churn for month-to-month contracts
  - 45.3% churn for electronic check users
  - 56.2% churn within first 3 months
- Strong retention factors:
  - 97.2% retention for 2-year contracts
  - 85%+ retention for automatic payment users

## Dashboard Preview

| ![Dashboard 1](https://github.com/ontu001/Telco-Customer-Churn-Analysis---EDA_Python/blob/main/dashboard/dashboard%200.jpg) | ![Dashboard 2](https://github.com/ontu001/Telco-Customer-Churn-Analysis---EDA_Python/blob/main/dashboard/Dashboard%201.jpg) |
|--------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------|
| **Churn Distribution & Contract Analysis**                                                                                | **Payment Method & Tenure Patterns**                                                                                      |

## Technical Implementation
```python
# Core Libraries
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt

# Sample Analysis Code
churn_rate = df['Churn'].value_counts(normalize=True)
sns.countplot(x='Contract', hue='Churn', data=df, palette=["#4c72b0", "#dd8452"])


How to Use
Clone repository:
git clone https://github.com/ontu001/Telco-Customer-Churn-Analysis---EDA_Python.git

Install requirements:

bash
pip install -r requirements.txt
Run analysis:

bash
python churn_analysis.py
