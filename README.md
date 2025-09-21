# Banking_data_analytics
📊 Banking Dashboard (Power BI)

This project presents a Power BI dashboard designed to analyze customer banking data and support risk analytics in financial services. The dashboard helps identify customer behavior patterns, loan risks, and financial trends, enabling data-driven decision-making.

🔎 Problem Statement

Banks and financial institutions face challenges in minimizing the risk of losing money while lending to customers. The objective is to:

Understand risk analytics in banking.

Use data to assess whether a customer is likely to repay a loan.

Support decision-making through interactive dashboards.

✅ Solution

A Power BI dashboard was built using modern tools to:

Analyze applicant profiles.

Identify patterns in deposits, loans, and fees.

Support loan approval/rejection decisions based on risk.

📝 Dataset

The project uses multiple interlinked tables (via primary & foreign keys):

Banking Relationship

Client-Banking

Gender

Investment Advisor

Period

Key Enhancements (Data Cleaning & Transformation):

Created new columns:

Engagement Timeframe – client’s timeline with the bank.

Engagement Days – total days since joining.

Income Band – income classified as Low (<100k), Mid (<300k), etc.

Processing Fees – applied based on fee structure.

Defined calculated measures with DAX:

SUM() → Total deposits

DISTINCTCOUNT() → Unique clients

SUMX() → Total fees (loan × processing fee)

SWITCH() → Categorical mappings

DATEDIFF() → Duration calculations

📈 Dashboard Features

Customer Demographics: Age, gender, income distribution

Financial Overview: Deposits, loans, credit scores

Churn Analysis: Customers exiting the bank

Risk Insights: Processing fees, engagement time, and repayment behavior

Interactive Filters: Explore by age, income, products, etc.

🚀 How to Use

Clone or download this repository:

git clone https://github.com/your-username/banking-dashboard.git
cd banking-dashboard


Open Banking Dashboard.pbix (or Banking Dashboard (2025).pbix) in Power BI Desktop
.

Ensure the dataset (Banking.csv, clients.csv, etc.) paths are correctly linked in Power BI.

Refresh data to load the latest values.
