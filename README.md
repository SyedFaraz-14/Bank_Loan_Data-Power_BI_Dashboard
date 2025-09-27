# Bank Loan Performance and Risk Analysis Dashboard
## 📊 Project Overview
This project presents a dynamic and comprehensive Bank Loan Performance and Risk Analysis Dashboard built using Power BI. It provides critical insights into the bank's lending portfolio, focusing on loan distribution, financial performance, and key risk indicators.

The primary goal is to empower stakeholders, risk managers, and analysts to monitor the health of the loan portfolio in real-time, identify high-risk segments, and assess the efficiency of capital deployment.

## 💡 Key Information and Measures Used
The analysis is built around a structured data model incorporating detailed loan application and status data. The following measures and dimensions are used to provide a 360-degree view of the portfolio:

## A. Core Financial & Distribution Measures
1. Total Funded Amount: The cumulative principal amount distributed across all active and paid-off loans.
1.1 Insights Provided: Portfolio size and capital exposure.

2. Total Received Amount: The cumulative payments (principal + interest) collected to date.
2.1 Insights Provided: Cash flow and return tracking.

3. Average Interest Rate (APR): The average interest rate, weighted by the loan amount.
3.1 Insights Provided: Profitability and competitive pricing analysis.

4. Average Monthly Installment: The average required monthly payment across the portfolio.
4.1 Insights Provided: Cash flow prediction and affordability assessment.

## B. Risk and Performance Measures
1. Good Loans vs. Bad Loans: A classification based on loan status: Good Loans are 'Fully Paid' or 'Current'. Bad Loans are 'Charged Off' or 'Default'.
1.1. Insights Provided: Overall portfolio quality and write-off percentage.

2. Debt-to-Income (DTI): The average DTI ratio of borrowers in the portfolio.
2.1. Insights Provided: Borrower financial stability and external risk exposure.

3. Loan Default Rate: The percentage of loans classified as 'Bad Loans' relative to the total number of loans.
3.1. Insights Provided: Effectiveness of lending criteria and risk mitigation strategies.

4. Expected Loss Rate: The estimated loss amount based on charged-off loans.
4.1. Insights Provided: Reserve requirements and capital adequacy planning.

## C. Segmented Analysis
The dashboard allows for deep-dive analysis across critical dimensions:

1. Loan Purpose: Analyzing performance (e.g., 'Debt Consolidation', 'Home Improvement') to identify profitable or risky activities.

2. Loan Grade & Sub-Grade: Assessing performance by internal risk rating categories.

3. Term Length: Comparing the risk profiles and return metrics for 36-month vs. 60-month loans.

4. Geographical Analysis: Performance segmentation by State or Region.

5. Employment Length: Understanding the relationship between job stability and loan default risk.

## 🛠️ Technology Stack
1. Data Visualization & Reporting: Power BI Desktop (.pbit Template)
2. Data Modeling: Star Schema (or similar efficient model) for optimized query performance.
3. Calculations: Advanced DAX (Data Analysis Expressions) for creating sophisticated risk and financial metrics.
