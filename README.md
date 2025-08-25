# fintech-transactions-analysis
FinTech Customer Transactions Analysis using Python (EDA &amp; Visualizations)

 Project Overview

This project analyzes customer transaction data for a digital bank. The dataset includes deposits, withdrawals, transfers, and payments across different merchants and channels.
The goal is to provide insights into customer behavior, transaction patterns, and channel usage to help the bank understand its operations better.

Dataset

The dataset contains 500 transactions from 50 customers with the following key columns:

customer_id – Unique ID of each customer

transaction_id – Unique ID of transaction

transaction_date – Date of transaction

transaction_type – Deposit / Withdrawal / Transfer / Payment

amount – Amount of transaction (₦)

merchant – Where the money was spent (e.g., Uber, Amazon, Local Market)

channel – Mobile App, USSD, ATM, POS

balance_after_transaction – Account balance after each transaction



 
 Tools Used

Python (pandas, matplotlib, seaborn) → Data cleaning, analysis, visualization

Google Colab → Running Jupyter Notebook in the cloud



Key Insights

50 unique customers with ₦12.5M processed across 500 transactions.

Withdrawals (157) were the most common transaction type, followed closely by Deposits (146).

POS (136) was the most popular channel, showing reliance on in-person merchant payments.

Top merchants included Uber, Apple Store, Amazon, Airtime Topup, and Spotify → showing lifestyle spending.

Average transaction size was consistent at around ₦24k–₦26k.

Transactions trend was steady across the period (simulated data).


Visualizations

Distribution of Transaction Types

Channel Usage

Top 5 Merchants

Transaction Trend Over Time


 
 Next Steps

Build an interactive Power BI dashboard for business users.

Expand dataset to include customer demographics for deeper insights.

Apply predictive modeling (e.g., customer churn prediction).



Conclusion

This analysis provides a snapshot into customer financial behavior in a digital banking environment.
It demonstrates skills in data cleaning, EDA, and visualization — key foundations of a data analyst role.
