# 📊 Customer Churn Analysis (SQL + Power BI)

---

## 📌 Project Overview

This project analyzes customer churn behavior using SQL and Power BI to uncover key patterns, customer segments, and revenue impact.

The objective is to understand why customers churn and provide actionable business insights to improve retention.

---

## 🛠️ Tools & Technologies

* SQL Server (Data Cleaning & Transformation)
* Power BI (Dashboard & Visualization)
* Excel (Data Source)

---

## 🔄 Project Workflow

1. Imported raw customer data into SQL Server
2. Performed data cleaning and handled missing values
3. Created staging and production tables
4. Built SQL views for analytical queries
5. Designed interactive Power BI dashboard for insights

---

## 📊 Key Analysis Performed

* Customer distribution by gender, state, and contract type
* Churn rate by services (Internet, Streaming, Support)
* Revenue contribution by churn status
* Monthly charge vs churn relationship
* Churn analysis by tenure groups

---

## 📈 Key Insights

* Customers with **month-to-month contracts** have the highest churn
* **Higher monthly charges** are associated with increased churn
* Customers with **short tenure (< 6 months)** churn more frequently
* Lack of services like **online security and support** increases churn risk
* Certain states show significantly higher churn concentration

---

## 📊 Dashboard Preview

![Dashboard](images/dashboard.png)

---

## 📂 Project Structure

```
churn-analysis-project/
│
├── data/
├── sql/
│   └── churn_analysis.sql
├── powerbi/
│   └── churn_dashboard.pbix
├── images/
│   └── dashboard.png
└── README.md
```

---

## 🧾 SQL Work Highlights

* Data cleaning using `ISNULL()` and transformations
* Creation of staging and production tables
* Aggregations for churn metrics
* Views for reusable analytics

---

## 👤 Author

**Aryaman Bhardwaj**
Data Analyst | SQL | Power BI

