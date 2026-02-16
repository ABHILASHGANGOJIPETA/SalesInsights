# Sales Insights Dashboard – Power BI Project

## 📌 Project Overview

This project simulates a real-world business scenario where a computer hardware company (Atlware) struggled to understand its sales performance due to scattered reports and large Excel files. The goal was to transform raw transactional data into clear, interactive insights using SQL and Power BI.

The final outcome is an interactive Sales Insights Dashboard that enables management to monitor revenue, sales quantity, customer contribution, product performance, and trends over time.

---

## 🧩 Business Problem

The Sales Director was receiving verbal updates and large spreadsheets that were difficult to interpret. Because of this, the company could not:

* Identify high and low performing markets
* Track revenue trends
* Understand customer and product contributions
* Make timely data-driven decisions

The objective was to build a centralized dashboard providing accurate and real-time insights.

---

## 🎯 Project Objectives (AIMS Grid)

**Purpose:** Provide clear visibility into sales performance
**Stakeholders:** Sales team, Marketing team, IT team, Leadership
**End Result:** Interactive Power BI dashboard
**Success Criteria:** Faster reporting and improved decision making

---

## 📂 Dataset Description

The dataset contains multiple related tables:

**Fact Table**

* Sales Transactions (~150K+ records)
* Columns: Date, Sales Amount, Quantity, Product Code, Customer Code, Market Code, Currency

**Dimension Tables**

* Customers
* Products
* Markets

This multi-table structure allowed real-world modeling and analysis.

---

## 🛠 Tools & Technologies Used

* MySQL Workbench – Data exploration and validation
* Power Query – Data cleaning and transformation (ETL)
* Power BI – Data modeling, DAX measures, dashboard creation
* DAX – Business metrics and KPIs

---

## 🔍 SQL Data Exploration

Performed data profiling using SQL:

* Joins between transactions, products, customers, and markets
* Aggregations (SUM, COUNT)
* Filtering using WHERE clause
* Checking duplicates and invalid records

This step helped understand data quality before visualization.

---

## 🔄 Data Cleaning (ETL Process)

Handled in Power Query:

* Removed invalid markets
* Filtered negative and zero sales
* Fixed duplicate transactions
* Converted currency from USD to INR
* Standardized data types

---

## 🧠 Data Modeling

Implemented a Star Schema:

* Fact Table: Sales Transactions
* Dimension Tables: Customers, Products, Markets

Benefits:

* Faster query performance
* Simplified DAX calculations
* Better scalability

---

## 📊 DAX Measures Created

* Total Revenue
* Total Sales Quantity
* Revenue Trends (Time-based analysis)
* Top Customers
* Top Products

---

## 📈 Dashboard Features

* Revenue & Sales KPI Cards
* Revenue by Market
* Sales Quantity by Market
* Monthly Revenue Trend
* Top Customers
* Top Products
* Interactive Filters (Year & Month)
* Mobile Layout Support

---

## 🔎 Key Insights

* Delhi NCR contributed the highest revenue
* Several markets generated negligible sales
* Revenue declined after 2019
* High dependency on a single customer
* Product contribution imbalance detected

---

## 💼 Business Impact

* Enabled data-driven decision making
* Reduced manual reporting dependency
* Identified underperforming markets
* Highlighted revenue decline early
* Improved communication across teams

---

## 🚀 How to Use

1. Open the .pbix file in Power BI Desktop
2. Refresh the dataset (if database connected)
3. Interact with filters and visuals
4. Publish to Power BI Service for sharing

---

## 🧾 Resume Highlights

* Built end-to-end BI solution using SQL and Power BI
* Implemented star schema data model
* Performed ETL using Power Query
* Created DAX measures for business KPIs
* Generated actionable sales insights

---

## 👤 Author

Abhilash Gangojipeta
Data Analyst | Power BI | SQL
