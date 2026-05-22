# 🏦 Mitron Bank – Credit Card Strategy Analysis

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Domain](https://img.shields.io/badge/Domain-Banking%20%7C%20FinTech-blue?style=for-the-badge)

---

## 📌 Project Overview

Mitron Bank, a legacy financial institution headquartered in Hyderabad, wants to expand its product portfolio by launching a new line of credit cards. To support this decision, the bank partnered with **IOTA Data Services** to conduct a pilot analysis on a sample dataset of **4,000 customers across 5 cities**.

As a **Business Analyst**, the goal was to explore customer demographics, spending behavior, and income utilization patterns — and deliver actionable recommendations to guide the product and strategy teams.

---

## 🎯 Problem Statement

Analyze the sample dataset to:
- Classify customers by **demographics** (age, gender, occupation, city)
- Calculate **income utilization %** to identify likely credit card users
- Understand **spending patterns** across categories and payment types
- Identify **high-value customer segments** for credit card targeting
- Recommend **credit card features** based on data insights

---

## 📁 Dataset Description

### `dim_customers` – Customer Demographics

| Column | Description |
|---|---|
| `customer_id` | Unique identifier for each customer |
| `gender` | Male / Female |
| `age_group` | 21-24, 25-34, 35-45, 45+ |
| `marital_status` | Single / Married |
| `city` | Mumbai, Delhi-NCR, Chennai, Hyderabad, Bengaluru |
| `occupation` | Salaried IT, Salaried Other, Business Owner, Freelancer, Government |
| `average_income` | Monthly average income (INR) |

### `fact_spends` – Customer Spending Details

| Column | Description |
|---|---|
| `customer_id` | Links to dim_customers |
| `month` | May to October |
| `category` | Bills, Groceries, Electronics, Travel, etc. |
| `payment_type` | Credit Card, UPI, Debit Card, Net Banking |
| `spends` | Total amount spent (INR) |

---

## 📊 Dashboards

### Dashboard 1 – Customer & Spending Overview
![Dashboard 1](./Customer%20%26%20spending%20overview.JPG)

### Dashboard 2 – Customer Spending Behavior Analysis
![Dashboard 2](./Customer%20Spending%20Behavior.JPG)

---

## 🔑 Key Metrics Analyzed

| Metric | Value |
|---|---|
| Total Customers | 4,000 |
| Average Monthly Income | ₹51.7K |
| Average Spend | ₹614.5 |
| Income Utilization | ₹10.3K |

---

## 💡 Key Insights

### 💳 Payment Behavior
- **Credit Cards dominate** with ₹216M in total spend — the highest among all payment types
- UPI follows at ₹141M, Debit Card at ₹120M, and Net Banking at ₹54M

### 🌆 City-wise Spending
- **Mumbai** leads with ₹172M in total spend
- Delhi-NCR (₹111M) and Bengaluru (₹100M) follow

### 👥 Demographics
- **Male customers** account for ~67% of total spend across all age groups
- **25–34 age group** is the highest-spending customer segment

### 💼 Occupation & Income
- **Business Owners** have the highest average income at ₹70K/month
- **Salaried IT Employees** follow at ₹61K/month

### 🛒 Spending Categories
- **Bills** (₹104.9M), **Groceries** (₹86.3M), and **Electronics** (₹79.6M) are the top 3 categories
- Travel (₹59.2M) and Health & Wellness (₹65.6M) present premium rewards opportunities

---

## 🎯 Recommendations

| Feature | Rationale |
|---|---|
| **Cashback on Bills & Groceries** | Top 2 spending categories — high daily usage drives card stickiness |
| **EMI on Electronics** | ₹79.6M in electronics spend supports 0% EMI feature |
| **Travel Rewards / Lounge Access** | Travel spend of ₹59.2M from high-income segments |
| **Health & Wellness Benefits** | ₹65.6M spend supports gym/pharmacy cashback |
| **Target: 25–45 age group** | Highest income utilization and overall spend |
| **Priority City: Mumbai** | Strongest spending market at ₹172M |

---

## 🛠 Tools Used

- **Power BI** – Data modeling, DAX measures, interactive dashboards

---

## 📂 Project Structure

```
mitron-bank-credit-card-analysis/
│
├── README.md
├── Customer & spending overview.JPG     # Customer & Spending Overview
├── Customer Spending Behavior.JPG       # Spending Behavior Analysis
└── Mitron_Bank_Analysis.pbix   # Power BI file
```

---

## 🙋‍♂️ About

This project was built as part of a data analytics portfolio to demonstrate skills in:
- Business understanding & problem framing
- Data exploration and segmentation
- Dashboard design in Power BI
- Deriving actionable business recommendations from data

---
