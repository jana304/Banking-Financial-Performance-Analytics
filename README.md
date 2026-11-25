# Banking & Financial Performance Analytics Dashboard

## Project Overview

An interactive Banking and Financial Performance Analytics project developed using Microsoft Power BI and SQL to analyze banking operations, loan portfolios, deposit performance, customer relationships, financial metrics, and revenue generation.

The project combines data preparation, financial analysis, business intelligence, interactive visualization, customer drill-through analysis, and natural language Q&A to support data-driven decision-making in the banking sector.

## Business Objectives

- Monitor overall banking and financial performance.
- Analyze loan portfolios and business lending.
- Evaluate customer deposit behavior.
- Identify high-value customer segments.
- Analyze banking fee contributions.
- Understand customer loyalty and engagement.
- Monitor financial account balances.
- Enable interactive financial data exploration.
- Support strategic banking decisions.

## Tools & Technologies

| Technology | Purpose |
|---|---|
| Microsoft Power BI | Interactive dashboard development |
| SQL | Database querying and analysis |
| Power Query | Data cleaning and transformation |
| DAX | Financial measures and KPI calculations |
| Data Modeling | Table relationships and analytical modeling |
| CSV | Dataset storage |
| Power BI Q&A | Natural language data exploration |
| Microsoft PowerPoint | Project presentation |
| Visual Studio Code | Project documentation |
| Git & GitHub | Version control and portfolio management |

## Dataset Overview

The project uses banking datasets containing customer demographics, financial account information, banking relationships, investment advisors, and customer engagement records.

### Dataset Files

| File | Description |
|---|---|
| banking-clients.csv | Customer and financial information |
| banking-realtionships.csv | Banking relationship classifications |
| banking_clients_cleaned.csv | Processed banking dataset |
| gender.csv | Gender classification data |
| investment-advisiors.csv | Investment advisor information |

### Key Data Attributes

- Customer ID
- Customer Name
- Gender
- Age
- Nationality
- Occupation
- Income Band
- Banking Relationship
- Investment Advisor
- Loyalty Classification
- Engagement Length
- Bank Loans
- Business Lending
- Bank Deposits
- Savings Accounts
- Checking Accounts
- Foreign Currency Accounts
- Credit Card Balance
- Banking Fees

## Key Financial Metrics

| Financial Metric | Reported Value |
|---|---:|
| Total Loans | $4.38 Billion |
| Total Deposits | $3.77 Billion |
| Bank Loans | $1.77 Billion |
| Business Lending | $2.60 Billion |
| Total Fees | $158.19 Million |
| Bank Deposits | $2.01 Billion |
| Savings Account Balance | $698.73 Million |
| Checking Account Balance | $963.28 Million |
| Foreign Currency Amount | $89.65 Million |
| Credit Card Balance | $9.53 Million |

Values are approximate and may change depending on dashboard filters.

## Dashboard Architecture

The Power BI dashboard consists of six interactive analytical pages.

### Page 1: Executive Overview

Provides a centralized overview of major banking and financial performance indicators.

- Total clients
- Total loans
- Total deposits
- Total fees
- Credit card metrics
- Savings account balance
- Joining year filters
- Gender filters
- Interactive page navigation

### Page 2: Loan Analysis

Evaluates lending performance across different customer segments and banking relationships.

- Total loan portfolio
- Bank loan performance
- Business lending analysis
- Credit card balances
- Bank loans by income band
- Bank loans by banking relationship
- Loan distribution by nationality
- Lending by customer engagement timeframe

### Page 3: Deposit Analysis

Analyzes customer deposit behavior and financial account balances.

- Total deposit performance
- Bank deposits
- Savings account balances
- Checking account balances
- Foreign currency accounts
- Deposits by income band
- Deposits by banking relationship
- Deposits by nationality
- Customer engagement analysis

### Page 4: Financial Summary

Consolidates major financial and customer-related metrics into a comprehensive analytical report.

- Customer metrics
- Loan and deposit performance
- Business lending
- Banking fee contributions
- Financial account balances
- Credit card metrics
- Customer engagement length

### Page 5: Customer Drill-Through Analysis

Provides detailed customer-level financial and banking relationship analysis.

- Customer financial records
- Investment advisor information
- Customer engagement length
- Credit card balances
- Individual banking fee contributions
- Fees by loyalty classification
- Nationality-based analysis
- Interactive drill-through functionality

### Page 6: Natural Language Q&A

Uses Power BI's built-in Q&A functionality to enable natural language exploration of banking data.

Example business questions:

- What are the top income bands by total fees?
- Which income bands contribute the highest deposits?
- Which occupations have the highest credit card counts?
- Which banking contacts have the most clients?
- Which occupations contribute the highest bank loans?

## SQL Analysis

The project includes a SQL script named `Banking.sql` as a supporting analytical component.

SQL can support banking analytics through:

- Data exploration
- Financial aggregations
- Customer segmentation
- Loan and deposit analysis
- Banking relationship analysis
- Financial performance reporting

The SQL script is available in the root directory of the repository.

## Key Business Insights

- The overall loan portfolio amounts to approximately $4.38 billion.
- Business lending contributes approximately $2.60 billion, representing the largest component of the loan portfolio.
- Total customer deposits amount to approximately $3.77 billion.
- Total banking fees reach approximately $158.19 million.
- Checking account balances exceed savings account balances.
- Middle-income customers represent a significant segment in lending and deposit performance.
- Private banking represents a significant banking relationship segment.
- Customer loyalty classifications provide insights into banking fee contributions.
- Nationality-based segmentation helps identify differences in financial activity.
- Customer engagement analysis supports the evaluation of long-term banking relationships.

## Interactive Dashboard Features

- Dynamic KPI cards
- Interactive slicers
- Cross-filtering visualizations
- Customer segmentation
- Financial performance monitoring
- Page navigation buttons
- Customer drill-through analysis
- Natural language Q&A
- Detailed analytical tables
- Multi-dimensional financial analysis

## Project Workflow

1. Banking dataset collection
2. Data cleaning and preparation
3. SQL-based data analysis
4. Data transformation using Power Query
5. Data modeling and relationship creation
6. DAX measure development
7. Financial KPI calculation
8. Interactive dashboard development
9. Customer drill-through configuration
10. Natural language Q&A configuration
11. Business insight generation
12. Project presentation and documentation
13. GitHub portfolio deployment

## Repository Structure

    BANKING_FINANCIAL_ANALYTICS/
    |
    |-- data/
    |   |-- banking-clients.csv
    |   |-- banking-realtionships.csv
    |   |-- banking_clients_cleaned.csv
    |   |-- gender.csv
    |   |-- investment-advisiors.csv
    |
    |-- power bi/
    |   |-- Banking.pbix
    |
    |-- screenshots/
    |
    |-- Banking.sql
    |-- Presentation1.p