# customer-churn-analysis
Analyzing customer behavior to identify key drivers of churn and provide data-driven recommendations to improve retention. 

# Customer Churn Analysis
This project analyzes customer churn using machine learning and data visualization to identify key drivers of customer attrition and provide actionable business insights.

## Objective
Predict customer churn and identify key factors driving customer retention.

## Dataset
- IBM Telco Customer Churn dataset
- Contains customer demographics, account informatino, and service usage
- Target variable: Churn (Yes/No) 

## Tools Used
- Python (Pandas, Scikit-learn)
- Jupyter Notebook
- Tableau Public

## Key Results
- Achieved ROC-AUC of 0.86 using Random Forest
- Identified tenure and monthly charges as top predictors

## Key Insights

- Customers who churned had significantly shorter tenure (18 months vs. 38 months)
- Churned customers paid higher monthly charges ($74 vs. $61)
- Customers on month-to-month contracts have the highest churn rate (~42%)
- Early-stage customers are at the highest risk of churn
- Pricing plays a major role in customer retention

## Machine Learning Model
- Model Used: Random Forest Classifier
- Accuracy: ~82%
- ROC-AUC: ~0.86

  ### Top Feautures:
  - Tenure
  - Monthly Charges

## Project Structure
- notebooks/churn_analysis.ipynb → full analysis
