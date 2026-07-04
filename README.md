# Telco Customer Churn Analysis

An end-to-end analysis of customer churn using SQL, Excel, Python, and Tableau — 
identifying key drivers of churn and quantifying revenue at risk for a telecom business.

## 📊 Project Overview
This project analyzes a telecom company's customer data to answer: 
**Why are customers leaving, and how much revenue is at risk because of it?**

The analysis was conducted using a multi-tool workflow to reflect a real-world 
analytics pipeline — from raw data to a stakeholder-ready dashboard.

## 🛠️ Tools Used
- **Python (pandas)** — data cleaning, initial exploratory analysis
- **SQL (SQLite)** — business-question queries, aggregations
- **Excel** — pivot tables, percentage breakdowns, charts
- **Tableau** — final interactive dashboard

## 🔑 Key Findings
- **Contract type** is the strongest churn driver: Month-to-month customers churn at 
  ~43%, vs. ~11% for one-year and ~3% for two-year contracts.
- **Electronic check** users churn at ~45%, nearly 3x higher than other payment methods.
- **Fiber optic** internet customers churn at ~42%, compared to ~19% for DSL.
- Customers **without dependents** churn at ~31%, nearly double the rate of those with 
  dependents (~15%).
- **Gender showed no meaningful impact** on churn (~27% vs ~26%).
- Churned customers represent **~$139,000/month in revenue at risk** — roughly 30.5% 
  of total monthly revenue, despite being only 26.5% of the customer base.

## 📁 Repository Structure
- `/data` — cleaned dataset used across all tools
- `/sql` — business-question SQL queries
- `/excel` — pivot table analysis
- `/tableau` — interactive dashboard (.twbx)
- `/screenshots` — dashboard preview image

## 📈 Dashboard Preview
![Dashboard](screenshots/dashboard_preview.png)

## 🎯 Business Recommendation
Focus retention efforts on month-to-month, fiber-optic customers paying via 
electronic check — this segment shows disproportionately high churn risk and 
represents significant recoverable revenue.

## 🔗 Dataset Source
[Telco Customer Churn — Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
