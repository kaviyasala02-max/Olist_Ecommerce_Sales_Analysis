# Olist_Ecommerce_Sales_Analysis

##Project Overview

This project analyzes the Brazilian e-commerce dataset from Kaggle to uncover key business insights using Power BI, SQL, and Excel. The goal is to understand sales performance, customer behavior, and payment trends to support data-driven decision-making.

Dataset Source: Olist E-Commerce Dataset (Kaggle)

Contains: Orders, Customers, Products, Payments, Reviews, Sellers Time Period: 2016 – 2017

Tools & Technologies Power BI – Data modeling & visualization SQL – Data extraction & transformation Excel – Data cleaning & preprocessing

##Step-by-Step Process

1️⃣ Data Extraction Downloaded dataset from Kaggle Imported CSV files into SQL and Excel for preprocessing

2️⃣ Data Loading Loaded cleaned data into Power BI Established relationships between tables

3️⃣ Data Modeling Designed Star Schema Fact Table: Orders / Sales Dimension Tables: Customers, Products, Sellers, Time Relationships: Many-to-One (Fact → Dimensions) Many-to-Many (handled using bridge tables where required)

4️⃣ Data Cleaning Removed null values Standardized column formats (dates, currency) Handled missing data using appropriate techniques

5️⃣ Data Validation Cross-checked totals between SQL, Excel, and Power BI Verified relationships and measures Ensured data consistency and accuracy

6️⃣ Data Transformation Created calculated columns and measures: Total Sales Average Order Value Total Orders Customer Count

##Dashboard & Visualizations KPI Cards

Total Orders: 31K

Total Sales: 4.38M

Avg Order Value: 140.71

Total Customers: Charts & Business Insights

Sales Trend (Line Chart) Question: How do sales vary over time?
Insight: Sales show consistent growth with seasonal peaks.

Orders vs Goal (Area Chart) Question: Are we meeting monthly targets?
Insight: Orders fall short of goals (~37% gap), indicating growth opportunities.

Payment Type Distribution (Donut Chart) Question: Which payment methods are most used?
Insight: Credit cards dominate transactions.

Sales by Product Category (Bar Chart) Question: Which products generate the most revenue?
Insight: Top categories significantly outperform others.

5 Sales by Customer City (Line/Bar Chart) Question: Which cities contribute most to sales?

Insight: Major cities drive the majority of revenue.

Orders by State (Bar Chart) Question: Which states have the highest orders?
Insight: Sao Paulo leads in total orders.

7 Time Filter (Slicer) Purpose: Enables dynamic analysis across date ranges

##Key Insights

Strong dominance of credit card payments

High revenue concentration in top cities and states

Noticeable gap between actual orders and targets

Seasonal sales growth patterns
