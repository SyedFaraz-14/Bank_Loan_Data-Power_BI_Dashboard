# Bank Loan Performance and Risk Analysis Dashboard

### 📊 Project Summary
This project features a dynamic Bank Loan Performance and Risk Analysis Dashboard (Power BI Template, .pbit) designed for financial and risk management. 
It enables real-time monitoring of the lending portfolio, focuses on financial health and working of the bank, capital exposure, and important risk indicators to improve decision-making and resolve the loss making aspects.

### Dashboard Views
Financial Overview 💵: Top-level metrics on funded vs. received amounts, weighted APR, and overall portfolio distribution.

Risk Assessment 🛑: Deep dive into default rates, DTI ratios, and expected losses segmented by loan grade and purpose.

Geographic Analysis 🗺️: Visualization of portfolio size, performance, and risk density across different states and regions.

Customer Information 👤 : Analysis of loan performance segmented by customer characteristics (e.g., income, employment, credit score range).

### 📈 Key Portfolio Measures
This analysis utilizes advanced DAX measures to deliver actionable insights:

Total Funded Amount: The cumulative principal amount distributed, reflecting total capital exposure.

Total Received Amount: The cumulative payments (principal + interest) collected, used for cash flow and return tracking.

Weighted Average APR: The loan amount-weighted average interest rate, indicating portfolio profitability.

Debt-to-Income (DTI) Ratio: The average DTI of borrowers, reflecting external financial stability and risk.

Loan Default Rate: Percentage of 'Bad Loans' relative to the total portfolio, quantifying lending criteria effectiveness.

Expected Loss Rate: The estimated loss amount based on charged-off loans, vital for reserve planning.

Loan Count: The total number of loans, used for distribution and scale analysis.

Average Loan Term: The mean duration of all loans (e.g., 36 or 60 months).

### 🛡️ Performance Reflection (Good vs. Bad Loans)
Portfolio performance is reflected primarily through the classification of loans:

Good Loans: Loans classified as 'Fully Paid' or 'Current'. This group indicates successful, low-risk lending and strong cash flow.
Bad Loans: Loans classified as 'Charged Off' or 'Default'. This critical metric directly drives the Loan Default Rate and Expected Loss Rate, highlighting areas where lending risk or collection processes need immediate review.

### 🛠️ Technology & Setup
Platform: Power BI Desktop (.pbit Template).
Modeling: Efficient data model built for optimized query performance using DAX.

