# UPI Transaction Analysis and Fraud Detection

## 📌 Project Overview

This project analyzes **250,000 UPI transactions** to identify fraud patterns and understand transaction behavior. It uses Python for data analysis, SQL for querying transaction data, and Power BI for interactive dashboard development.

The goal is to identify trends across transaction types, merchant categories, banks, customer age groups, devices, networks, and transaction timings.

## 🎯 Project Objectives

* Analyze UPI transaction data and fraud distribution.
* Identify fraud patterns across different transaction categories.
* Compare fraud rates across banks, devices, and network types.
* Explore transaction trends by hour, day, and customer age group.
* Build an interactive Power BI dashboard to present key findings.

## 🛠️ Tools and Technologies

* **Python** — Data analysis
* **Pandas** — Data manipulation and cleaning
* **NumPy** — Numerical calculations
* **Matplotlib** — Data visualization
* **SQL / MySQL** — Transaction queries and analysis
* **Power BI** — Interactive dashboards

## 📂 Dataset Information

* **Total Transactions:** 250,000
* **Total Columns:** 17
* **Fraud Transactions:** 480
* **Genuine Transactions:** 249,520
* **Overall Fraud Rate:** 0.192%

### Key Dataset Columns

* Transaction ID and Timestamp
* Transaction Type and Merchant Category
* Transaction Amount and Status
* Sender and Receiver Age Groups
* Sender State and Bank Details
* Device Type and Network Type
* Fraud Flag, Hour of Day, Day of Week, and Weekend Indicator

## 🔍 Project Workflow

1. **Data Understanding** — Reviewed dataset structure, columns, and data types.
2. **Data Cleaning** — Checked missing values and duplicate records.
3. **Exploratory Data Analysis (EDA)** — Analyzed fraud distribution and transaction patterns.
4. **SQL Analysis** — Queried transactions to compare fraud counts and rates across categories.
5. **Data Visualization** — Created charts to highlight important patterns.
6. **Power BI Dashboard** — Presented key metrics and findings in an interactive format.

## 📊 Key Insights

* The overall fraud rate was **0.192%**.
* Recharge transactions had the highest observed fraud rate among transaction types at **0.239%**.
* WiFi transactions had the highest observed fraud rate among network types at **0.235%**.
* Web transactions had the highest observed fraud rate among device types at **0.206%**.
* Karnataka recorded the highest observed state-wise fraud rate at **0.232%**.
* Fraud rates varied across transaction timings, customer age groups, and merchant categories.

*Note: These are observed patterns in the dataset and do not establish the causes of fraud.*

## 📈 Dashboard Highlights

The planned Power BI dashboard includes:

* Total Transactions
* Fraud Transactions
* Genuine Transactions
* Overall Fraud Rate
* Fraud Analysis by Transaction Type
* Fraud Rate by Merchant Category
* State-wise Fraud Analysis
* Device and Network Analysis
* Time-based Transaction Trends

## 💡 Conclusion

This project demonstrates how Python, SQL, and Power BI can be used together to analyze transaction data, identify potential fraud patterns, and communicate insights through visualizations. The analysis supports better understanding of transaction behavior and helps highlight areas for further investigation.

* GitHub: [saziya03](https://github.com/saziya03)
