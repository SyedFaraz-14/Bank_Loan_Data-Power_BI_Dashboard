# Bank Loan Performance and Risk Analysis Dashboard

### 📊 Project Summary
This project features a dynamic Bank Loan Performance and Risk Analysis Dashboard (Power BI Template, .pbit) designed for financial and risk management. 
It enables real-time monitoring of the lending portfolio, focuses on financial health and working of the bank, capital exposure, and important risk indicators to improve decision-making and resolve the loss making aspects.

### 🎯 Objective of the project
1. The primary objective of the project was Credit Risk Assessment i.e. to optimize the lending strategy.
2. Specially by distinguishing between Good Loan (Fully Paid and Current) Amount and Bad Loan (Charged Off) Amount.

### 🔍 Key Findings
1. Good Loan are above 86% and the Bad Loans (NPAs) are 14%.
2. Most Loans were taken for Debt Consolidations i.e. more then 47% of Total Loan Applications and also has high Bad Loan of about 16%.
3. Small Businesses had Highest Bad Loan about 25% ,followed by Renewable Energy at 18%.
4. Wedding Loans had highest Good Loan 90.7% and second is Credit Card 89.8%.
5. Applicants with Avg DTI above 20% have high Bad Loans.

### 📟 Dashboard Views
1. Financial Overview 💵: Top-level metrics on funded vs. received amounts, weighted APR, and overall portfolio distribution.
2. Risk Assessment 🛑: Deep dive into default rates, DTI ratios, and expected losses segmented by loan grade and purpose.
3. Geographic Analysis 🗺️: Visualization of portfolio size, performance, and risk density across different states and regions.
4. Customer Information 👤 : Analysis of loan performance segmented by customer characteristics (e.g., income, employment, credit score range).

### 📈 Key Portfolio Measures
This analysis utilizes advanced DAX measures to deliver actionable insights:

1. Total Funded Amount: The cumulative principal amount distributed, reflecting total capital exposure.
2. Total Received Amount: The cumulative payments (principal + interest) collected, used for cash flow and return tracking.
3. Weighted Average APR: The loan amount-weighted average interest rate, indicating portfolio profitability.
4. Debt-to-Income (DTI) Ratio: The average DTI of borrowers, reflecting external financial stability and risk.
5. Loan Default Rate: Percentage of 'Bad Loans' relative to the total portfolio, quantifying lending criteria effectiveness.
6. Expected Loss Rate: The estimated loss amount based on charged-off loans, vital for reserve planning.
7. Loan Count: The total number of loans, used for distribution and scale analysis.
8. Average Loan Term: The mean duration of all loans (e.g., 36 or 60 months).

### 🛡️ Performance Reflection (Good vs. Bad Loans)
Portfolio performance is reflected primarily through the classification of loans:

1. Good Loans: Loans classified as 'Fully Paid' or 'Current'. This group indicates successful, low-risk lending and strong cash flow.
Bad Loans: Loans classified as 'Charged Off' or 'Default'. This critical metric directly drives the Loan Default Rate and Expected Loss Rate, highlighting areas where lending risk or collection processes need immediate review.

### 🛠️ Technology & Setup
Platform: Power BI Desktop (.pbit Template).
Modeling: Efficient data model built for optimized query performance using DAX.
