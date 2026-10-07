# Banking-Analytics-Portfolio-Transactions-Risk

## Project Overview

Banking 360 is an end-to-end Banking Data Analytics and Business Intelligence project focused on analyzing loan portfolio performance and debit-credit transaction activity.

The project combines SQL, Microsoft Excel, Power BI, and Tableau to transform raw banking data into meaningful KPIs, interactive dashboards, risk analysis, business insights, and strategic recommendations.

The analysis covers 65,535 loans across 112 branches and 100,000 debit-credit transactions across 6 banks and 6 branches.

## Project Objectives

### Loan Portfolio Analytics

- Analyze total funded amount, collections, and interest income
- Measure loan portfolio growth across financial years
- Analyze delinquency and default risk
- Identify high-risk loan grades and loan terms
- Analyze funding across states, branches, and loan purposes
- Evaluate portfolio concentration and borrower patterns
- Identify opportunities to improve portfolio performance and risk management

### Debit and Credit Analytics

- Analyze total transaction amount
- Compare credit and debit transaction flows
- Calculate credit-to-debit ratio and net transaction flow
- Compare banks, branches, and payment methods
- Analyze monthly transaction trends
- Identify high-risk transactions
- Evaluate transaction volume and value patterns

## Dataset Overview

### Loan Dataset

| Attribute | Details |
|---|---:|
| Total Loans | 65,535 |
| Fields | 55 |
| Branches | 112 |
| Regions | 11 |
| States | 15 |
| Disbursement Period | November 2016 to February 2020 |
| Loan Amount | Rs. 751.0M |
| Funded Amount | Rs. 732.7M |
| Borrowers | 65,511 women (99.96%) |
| Age Range | 18 to 62 |

### Debit and Credit Dataset

| Attribute | Details |
|---|---:|
| Total Transactions | 100,000 |
| Fields | 14 |
| Period | January to December 2024 |
| Banks | 6 |
| Branches | 6 |
| Currency | INR |
| Total Transaction Value | Rs. 254.9M |

Payment methods included:

- Bank Transfer
- Credit Card
- Debit Card

## Tools and Technologies

### SQL

- Data exploration and analysis
- Business queries
- Aggregations and KPI calculations
- Advanced SQL analysis
- Risk and portfolio analysis

### Microsoft Excel

- Data cleaning and preparation
- Pivot Tables
- Advanced formulas
- Slicers
- VBA Macros
- Interactive dashboards

### Power BI

- Data modelling
- DAX measures
- KPI development
- Interactive dashboards
- Loan and transaction analysis

### Tableau

- Calculated fields
- KPI analysis
- Interactive visualizations
- Dashboard development
- Business performance analysis

## Project Workflow

```text
Raw Banking Data
        |
Data Cleaning and Preparation
        |
Data Validation
        |
SQL Analysis
        |
Excel Analysis and Dashboard
        |
Power BI Data Model and DAX
        |
Tableau Analysis and Dashboard
        |
KPI Validation
        |
Business Insights and Recommendations
```

The core KPIs were cross-checked across the different analytical tools to maintain consistency and improve the reliability of the final analysis.

## Key KPIs

### Loan Analytics

| KPI | Value |
|---|---:|
| Total Funded Amount | Rs. 732.7M |
| Total Loans | 65,535 |
| Total Collection | Rs. 814.9M |
| Interest Received | Rs. 155.3M |
| Delinquent Loan Rate | 10.84% |
| Default Loan Rate | 1.56% |
| Average Loan Amount | Rs. 11.5K |
| Average Interest Rate | 12.03% |
| Total Revenue | Rs. 156.6M |
| Recoveries | Rs. 6.5M |

### Debit and Credit Analytics

| KPI | Value |
|---|---:|
| Total Transaction Amount | Rs. 254.9M |
| Total Credit | Rs. 127.6M |
| Total Debit | Rs. 127.3M |
| Credit-to-Debit Ratio | 1.0025 |
| Total Transactions | 100,000 |
| High-Risk Transactions | 20.4% |
| Net Credit-Debit | Rs. 0.32M |

## Dashboards

### Bank Loan Analytics Dashboard

The loan analytics dashboard provides insights into:

- Portfolio size
- Total funding
- Collections
- Revenue and interest
- Delinquency and default rates
- Funding by state and branch
- Grade-wise risk analysis
- Borrower analysis
- Loan status
- Loan purpose
- Financial-year trends

### Credit and Debit Analytics Dashboard

The transaction analytics dashboard provides insights into:

- Total credit and debit
- Net transaction flow
- Credit-to-debit ratio
- Monthly transaction trends
- Bank-wise analysis
- Branch-wise analysis
- Payment-method analysis
- High-risk transaction analysis

## Key Business Insights

### Loan Portfolio

- Uttar Pradesh, Punjab, Bihar, and Haryana account for 58% of total funding, indicating significant geographical concentration.
- Loan risk increases significantly across grades, with delinquency increasing from 3.9% for Grade A to 26.0% for Grade G.
- Interest rates increase with risk grade, ranging from approximately 7% to 21%.
- FY19 represents the peak funding year, contributing 57% of total funding.
- Home loans represent the largest loan purpose at 37%.

### Debit and Credit Transactions

- Credit and debit activity is almost perfectly balanced, with a 1.0025 credit-to-debit ratio.
- High-risk transactions represent 20.4% of transaction volume but 36.1% of transaction value, indicating a disproportionate concentration of monetary risk.
- Monthly transaction activity remains relatively stable, generally ranging between Rs. 22M and Rs. 24M.
- Banks, branches, and payment methods show relatively similar transaction volumes and values.

## Business Recommendations

1. Strengthen pricing and approval limits for higher-risk loan grades such as D to G.
2. Introduce early-warning monitoring for E to G loan accounts.
3. Review the 60-month loan product because of its higher yield but increased default risk.
4. Prioritize growth in relatively lower-risk states such as Haryana and Odisha.
5. Reduce excessive geographical concentration across the major funding states.
6. Improve transaction risk detection by combining transaction amount with behavioral indicators rather than relying only on an amount threshold.

## Data Quality and Challenges

During the project, several data-quality challenges were identified:

- Mixed date formats
- Missing values in important loan fields
- Approximately 39% of loans missing grade, verification, or home-ownership information
- Large Excel workbook size
- Partial December transaction data
- Unique Customer IDs limiting repeat-customer analysis
- Differences in KPI definitions between some source sheets

These issues were documented rather than hidden to maintain transparency and reliability throughout the analysis.

## Key Learning Outcomes

This project strengthened practical skills in:

- End-to-end data analytics
- SQL-based business analysis
- Data cleaning and validation
- Excel dashboard development
- Power BI and DAX
- Tableau visualization
- KPI design and validation
- Financial and banking analytics
- Loan portfolio analysis
- Risk analysis
- Transaction analytics
- Business intelligence
- Data-driven decision-making

## Conclusion

Banking 360 demonstrates an end-to-end approach to banking analytics by combining loan portfolio analysis with debit-credit transaction analytics.

By integrating SQL, Microsoft Excel, Power BI, and Tableau, the project converts raw banking data into actionable business intelligence covering portfolio performance, transaction behavior, geographical concentration, and financial risk.

The project provides a 360-degree view of banking performance and risk, supporting better data-driven business decisions.

## Author

Vaishnavi Thakur

B.Com Business Analytics

