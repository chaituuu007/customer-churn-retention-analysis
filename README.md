# Customer Churn & Retention Analytics

> Data Analytics project analyzing customer churn, retention, Customer Lifetime Value (CLV), and Monthly Recurring Revenue (MRR) using Python.

## 📊 Project Overview

Customer churn is a major business challenge because losing customers directly affects recurring revenue.

This project analyzes customer subscription data to:

- Calculate customer churn rate
- Measure customer retention
- Calculate Customer Lifetime Value (CLV)
- Calculate Monthly Recurring Revenue (MRR)
- Measure MRR loss caused by churn
- Identify behavioral patterns associated with churn
- Compare churn across contract types, tenure, and payment methods
- Provide actionable recommendations for improving retention

## 🎯 Objectives

1. Understand customer churn behavior
2. Identify high-risk customer segments
3. Measure revenue impact of churn
4. Analyze customer lifetime value
5. Develop data-driven retention recommendations

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- GitHub

## 📈 Key Metrics

| Metric | Result |
|---|---:|
| Total Customers | 15 |
| Churned Customers | 7 |
| Churn Rate | 46.7% |
| Retention Rate | 53.3% |
| Monthly Recurring Revenue | $1,269.85 |
| MRR Lost from Churn | $409.93 |
| MRR Loss | 32.3% |
| Average Observed CLV | $2,088.48 |

## 🔍 Key Findings

### Contract Type
All month-to-month customers in this sample churned, while none of the one-year or two-year contract customers churned.

### Tenure
Customers with shorter tenure showed substantially higher churn. All customers in the 0–6 month group and 7–12 month group churned in this sample.

### Support Tickets
Churned customers averaged approximately 4.3 support tickets compared with 1.0 among retained customers.

This suggests that repeated support interactions may be useful as an early-warning indicator.

### Payment Method
Churn rates differed across payment methods, although the sample size is small and these differences should be validated using a larger dataset.

## 📊 Analysis & Visualizations

The project includes:

- Churn Rate by Contract Type
- Churn Rate by Tenure
- Churn Rate by Payment Method
- Customer Lifetime Value Distribution
- Correlation Heatmap
- Revenue Impact Analysis

## 💡 Business Recommendations

1. Improve onboarding during the first 12 months.
2. Encourage month-to-month customers to consider longer-term contracts.
3. Identify customers with repeated support tickets and proactively resolve their issues.
4. Investigate payment-related friction and failed transactions.
5. Validate these patterns using a larger customer dataset before making major business decisions.

## 📁 Project Files

```text
customer-churn-retention-analysis/
│
├── data/
│   └── customer_churn_sample.csv
│
├── charts/
│   ├── contract_churn.png
│   ├── tenure_churn.png
│   ├── clv_boxplot.png
│   ├── payment_churn.png
│   └── correlation_heatmap.png
│
├── Customer_Churn_Analytics_Report.pdf
├── churn_analysis.ipynb
└── README.md
