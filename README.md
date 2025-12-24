# Retail-Sales-Analysis
# 📌 Project Overview

This project is a complete **Retail Sales SQL Analysis Case Study** taught by **Zero Analyst**.
It simulates how raw transactional data is handled in real business environments — starting from table creation and CSV import, followed by data cleaning, exploratory analysis, and answering key business questions using SQL.

The goal of completing this project was not just to write queries, but to understand:

How structured transactional data is stored in relational databases
How businesses analyze customer behavior, sales trends, and performance metrics
How SQL is used to extract insights for business decision-making

All queries were executed and debugged independently while following the guided learning structure.

# 📘 Learning Outcomes

By completing this project, I gained hands-on experience in:

- Designing relational tables using DDL
- Importing large CSV datasets using the COPY command
- Identifying and removing invalid or incomplete records
- Writing analytical SQL queries using:
    - Aggregation functions
    - Subqueries
    - Common Table Expressions (CTEs)
    - Window Functions (RANK, PARTITION BY)
- Performing time-based analysis using date and time extraction
- Structuring SQL scripts for end-to-end analysis pipelines

# 🧹 Data Cleaning Strategy

After importing the dataset, null checks were performed across all critical columns to ensure data consistency.
Records containing null values in mandatory fields such as transaction ID, customer details, product category, quantity, pricing, or total sale were removed to maintain dataset integrity.
This step ensured that all subsequent analytical results were reliable and business-ready.

# 📊 Business Questions Solved

This project answers the following real-world business problems:

Question	- Business Purpose
Total sales by category	- Identify revenue-driving product lines
Average customer age by category -	Understand customer demographics
Best selling month per year	- Discover seasonal demand patterns
Top 5 customers by revenue -	Recognize high-value customers
Shift-based order analysis -	Optimize store operational hours
Unique customers per category -	Analyze customer-category relationships

# 🧠 Key Takeaways

- Clean data is more important than complex queries
- Window functions unlock powerful time-series insights
- SQL is not just for fetching rows — it’s a full analytics engine
- Real datasets rarely work perfectly on the first import

# 🙌 Acknowledgement

This project was completely taught by Zero Analyst as part of their SQL Project Series.
All credit for the dataset, problem statements, and overall project flow belongs to them.

This repository reflects my hands-on implementation, debugging experience, and structured learning of the complete workflow.
