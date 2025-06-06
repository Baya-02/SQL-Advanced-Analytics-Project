# 📊 Advanced SQL Project – Data Analysis Based on Data Warehouse

This repository presents an **Advanced SQL Data Analysis** project based on the **Data Warehouse** I previously built (see: [`SQL-DataWarehouse-Project`](https://github.com/Baya-02/SQL-DataWareHouse-Project)).  
The goal of this project is to perform comprehensive **exploratory and analytical queries** using advanced SQL techniques to uncover insights across several business dimensions.

---

## 🧠 Project Objectives

This project focuses on **deep-dive data analysis** and reporting using SQL, following multiple analytical paths:

---

### 1. 📈 Change Over Time Analysis
**Purpose:**
- Track trends, growth, and changes in key metrics over time.
- Perform time-series analysis and identify seasonality patterns.
- Measure growth or decline over specific periods.

🛠 *Example:*  
- Monthly sales changes
- Growth rates across different quarters or years

---

### 2. 🔁 Cumulative Analysis
**Purpose:**
- Calculate running totals and moving averages.
- Understand cumulative performance metrics.
- Identify long-term trends or compounding behaviors.

🛠 *Example:*  
- Cumulative revenue by month
- Rolling 3-month average of orders

---

### 3. 🚀 Performance Analysis (YoY / MoM)
**Purpose:**
- Compare performance across time periods (Year-over-Year, Month-over-Month).
- Benchmark growth across categories.
- Identify top-performing entities over time.

🛠 *Example:*  
- Compare total sales in 2024 vs 2023
- MoM growth of new customers

---

### 4. 🧩 Part-to-Whole Analysis
**Purpose:**
- Analyze proportion of individual categories to the total.
- Support A/B testing or regional/categorical comparisons.

🛠 *Example:*  
- Market share by region
- Contribution of each product category to total sales

---

### 5. 🎯 Data Segmentation Analysis
**Purpose:**
- Group and analyze data by meaningful segments.
- Enable deeper insights into customers, products, or geographies.

🛠 *Example:*  
- Customer segmentation based on order volume
- Sales by region and customer tier

---

### 6. 👥 Customer Report
**Purpose:**
- Consolidate key metrics and behaviors at the customer level.
- Understand customer value, frequency, and retention.

🛠 *Metrics:*  
- Total orders per customer  
- Average order value  
- Repeat purchase rate

---

### 7. 📦 Product Report
**Purpose:**
- Provide key product-level performance insights.
- Track best-selling products, returns, and product lifecycle.

🛠 *Metrics:*  
- Units sold per product  
- Product return rates  
- Revenue per product line

---

## 🗃️ Data Source

All analyses are based on the **star schema** structure from my [`SQL_DataWarehouse-Project`](https://github.com/Baya-02/SQL-DataWareHouse-Project) repository.  
The data includes dimensions such as:
- `dim_date`
- `dim_product`
- `dim_customer`
- `dim_region`
- `fact_sales`

---

## 🛠 Technologies Used

- PostgreSQL (Standard SQL Syntax)
- Window Functions (e.g., `ROW_NUMBER`, `RANK`, `SUM OVER`)
- CTEs (Common Table Expressions)
- Joins and Aggregations
- Time-Series and Comparative Analysis

---

## 📁 Folder Structure

```bash
/
├── 1_change_over_time.sql
├── 2_cumulative_analysis.sql
├── 3_performance_analysis.sql
├── 4_part_to_whole_analysis.sql
├── 5_data_segmentation.sql
├── 6_customer_report.sql
├── 7_product_report.sql
└── README.md

