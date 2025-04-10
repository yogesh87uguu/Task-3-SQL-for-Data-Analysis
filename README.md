# Task-3-SQL-for-Data-Analysis
Use SQL queries to extract and analyze data from a database.

# 📊 Mobile Sales Data Analysis (SQL Project)

This project provides a comprehensive analysis of mobile sales using structured SQL queries. The dataset contains information about customer transactions, mobile brands, units sold, cities, payment methods, and customer ratings.

---

## 📁 Dataset Overview

**Table:** `mobile_sales`  
**Source:** `mobile_sales.csv`

### Key Columns:
- `Transaction_ID`  
- `Date`, `Day_Name`  
- `Brand`, `Mobile_Model`, `Price_Per_Unit`, `Units_Sold`  
- `Customer_Name`, `Customer_Age`, `Customer_Ratings`  
- `City`, `Payment_Method`

---

## 🛠️ Features and Analysis Performed

### ✅ Basic Data Exploration
- Total transactions
- Unique brands
- Sales period (first and last transaction dates)

### 📈 Sales Analysis
- Total units sold and revenue by brand
- Top 5 best-selling mobile models
- Monthly and daily sales trends

### 🧑‍🤝‍🧑 Customer Analysis
- Age group segmentation
- City-wise transaction volume and revenue
- Rating averages by age group

### 💳 Payment Method Insights
- Popular payment methods by usage and ratings

### 🧠 Advanced SQL
- Subqueries to identify top 10% high-value transactions
- Views to analyze brand-city performance
- Conditional segments (e.g., Budget vs Premium phones)

### 📅 Seasonal Analysis
- Monthly and quarterly sales by brand

### ⚙️ Performance Optimization
- Indexes on `Brand`, `Date`, `City`, and `Payment Method` for faster queries

---

## 💾 Requirements

- MySQL (recommended version 8.0+)
- SQL client: MySQL Workbench, phpMyAdmin, or CLI
- CSV import functionality

---

## 🧪 How to Use

1. **Create the table** using the provided SQL structure.
2. **Import the dataset** (`mobile_sales.csv`) into MySQL.
3. **Run the analysis queries** from the SQL script.
4. Explore views and indexed queries for better performance.

---

## 📌 Future Improvements
- Automate loading with Python or ETL tools
- Build a Power BI or Tableau dashboard using the same dataset
- Add stored procedures for interactive querying

---

