# 🏦 Bank Churn Analysis using MS SQL Server

## 📊 Project Overview

This project presents an in-depth **Bank Churn Analysis** using Microsoft SQL Server. It focuses on uncovering insights from a dataset that includes customer demographics, account information, credit usage, and tenure. The analysis aims to identify patterns related to customer churn and help the bank make data-driven decisions to improve customer retention and risk profiling.

---

## 🛠️ Tools & Technologies Used

- **Microsoft SQL Server**
- **SQL Server Management Studio (SSMS)**
- **Structured Query Language (SQL)**

---

## 📂 Dataset

The dataset used is named `bank_churn_data`, which includes the following columns:

- `clientnum`
- `customer_age`
- `income`
- `balance`
- `credit_limit`
- `utilization_ratio`
- `months_on_book`
- `marital_status`
- `card_category`
- `dependent_count`

> Note: The dataset was already assumed to be loaded into a table `[dbo].[bank_churn_data]`.

---

## 📌 Key SQL Analyses Performed

### 📈 KPIs
- Total number of customers
- Average credit limit
- Average utilization ratio
- Average customer age

### 🔎 Deep-Dive Insights
1. **Customer Distribution by Card Category**
2. **Average Balance by Income Level**
3. **Customers by Marital Status**
4. **Age Group Segmentation**
5. **Top 10 Customers by Credit Utilization**
6. **High Credit Limit but Low Balance Customers**
7. **Top 10 Long-Term Customers by Tenure**
8. **Average Dependents by Income Group**
9. **Credit Utilization Risk Index (Low, Medium, High)**
10. **VIP Segmentation (Tenure > 53 Months)**
