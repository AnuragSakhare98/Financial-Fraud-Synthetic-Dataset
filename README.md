# Synthetic Financial Transaction Dataset

This repository contains a synthetic financial transaction dataset generated for research, educational, and machine learning purposes. The dataset simulates realistic financial activities to support experimentation in fraud detection, transaction analysis, customer behavior modeling, and financial risk assessment.

## 📄 Dataset Overview

The dataset is composed of individual transaction records containing a wide range of financial, geographic, temporal, and customer-related attributes. The data is **fully synthetic**, meaning it was artificially created and does **not represent any real individuals or banks**.

### 📌 Dataset Summary

- **Total Rows**: 5,000
- **Total Columns**: 30+
- **File Format**: CSV
- **Target Variable**: `Fraud` (binary: 0 = non-fraud, 1 = fraud)

Each row in the dataset represents a single transaction.

---

## 📊 Features Description

| Column Name                     | Description |
|--------------------------------|-------------|
| `Transaction ID`               | Unique identifier for each transaction |
| `Transaction Timestamp`        | Date and time of the transaction |
| `Transaction Amount`           | Monetary value of the transaction |
| `Transaction Currency`         | Currency used in the transaction (e.g., INR, AED) |
| `Transaction Type`             | Nature of the transaction (e.g., UPI, Bank Transfer, Stock Trading) |
| `Transaction Status`           | Status of the transaction (Completed, Reversed, Failed) |
| `Round-Number Transactions`    | Binary flag indicating if amount was a rounded number |
| `Account Age`                  | Age of the account in days |
| `Country/Region`               | Country where the transaction occurred |
| `City`                         | City where the transaction occurred |
| `Latitude` / `Longitude`       | Geolocation of the transaction |
| `Fraud`                        | Target label: 1 if fraudulent, 0 if legitimate |
| `Bank Name`                    | Simulated name of the associated bank |
| `Customer ID`                  | Unique ID of the customer |
| `Customer Name`                | Simulated full name of the customer |
| `Customer Age`                 | Age of the customer |
| `Credit Score`                 | Simulated credit score |
| `Annual Income`                | Simulated annual income of the customer |
| `Access Method`                | How the transaction was performed (e.g., Mobile App, Branch Visit) |
| `Account Balance`              | Account balance at the time of transaction |
| `account_type`                 | Type of account (e.g., Fixed Deposit, Checking, Savings) |
| `transactions_in_hour`        | Number of transactions made in the same hour |
| `is_new_account`              | Binary flag indicating whether the account is newly created |
| `Loan_IQ`                      | Simulated loan index for that customer |
| `transaction_location`         | Combined city and country |
| `high_risk_country_flag`       | Binary flag if transaction happened in a high-risk country |
| `browser_type`                 | Browser used during transaction (if online) |
| `historical_transaction_count`| Total past transactions made by the customer |
| `historical_avg_spending`     | Average historical spending by the customer |

---

## 🎯 Use Cases

This dataset can be used for:

- Fraud detection using machine learning
- Feature engineering and pattern recognition
- Customer segmentation based on transaction behavior
- Exploratory data analysis and data visualization
- Simulating real-world banking environments for academic purposes

---

## 🛡️ License and Terms

This dataset is made publicly available under the **Creative Commons Attribution 4.0 International License** (CC BY 4.0). You are free to use, share, and adapt the dataset with appropriate credit.

> ⚠️ **Note**: This is a synthetic dataset and should not be used to make real-world financial or policy decisions.

---

## 🧾 Citation

If you use this dataset in your work or project, please cite it as:

```plaintext
Sakhare, A. (2025). Synthetic Financial Transaction Dataset [Data set]. GitHub. https://github.com/AnuragSakhare98/Financial-Fraud-Synthetic-Dataset
