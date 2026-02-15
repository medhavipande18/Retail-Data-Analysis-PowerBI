# Retail Data Analysis

## Overview

This project presents an end-to-end retail data analysis workflow, from raw dataset preparation to customer segmentation and interactive business reporting. The goal is to transform transactional retail data into meaningful insights that support data-driven decision making.

The dataset includes the following attributes:

- **bill** — Invoice or transaction identifier  
- **merchandise id** — Unique identifier for each merchandise item  
- **product** — Product name  
- **quota** — Quantity purchased in the transaction  
- **amount** — Product price or transaction value  
- **customer id** — Unique customer identifier  
- **country** — Customer’s country  

---

## Data Preparation (SQL)

Before performing analysis and visualization, the dataset was cleaned and standardized using SQL to ensure data quality and reliability.

Key data preparation steps included:

- Removing records with missing or null values  
- Converting columns to appropriate data types  
- Eliminating duplicate or redundant records  
- Validating and standardizing data for consistency  

This preprocessing step ensured that downstream analysis and reporting were based on accurate and structured data.

---

## Analysis and Visualization

After cleaning the data, analytical modeling and reporting were performed using SQL and Power BI.

### RFM Customer Segmentation

RFM (Recency, Frequency, Monetary) analysis was implemented in SQL to segment customers based on purchasing behavior. This helps identify high-value customers and understand engagement patterns.

### Power BI Retail Dashboard

An interactive Power BI dashboard was developed to visualize key retail metrics and trends.

**Included Visualizations**

- **Quantity Orders vs Invoice Date** — Order volume trend over time  
- **Total Sales vs Invoice Date** — Revenue trend over time  
- **Highest Sold Product** — Best-performing product by sales  
- **Country-wise Revenue Table** — Total and average revenue by country  
- **Most Valuable Customer (RFM)** — Top customer segment based on RFM scoring  
- **Monthly Revenue Metrics** — Total and average revenue by month  
- **RFM Distribution** — Number of customers in each RFM segment  

**Dashboard Filters**

Users can dynamically filter data by:

- Year  
- Month  
- Country  

These filters enable focused exploration of specific time periods or geographic segments.

---

## Data Source

Dataset obtained from Kaggle:  
https://www.kaggle.com/datasets/coldperformer/online-retail-data-v3

---

## Project Structure

- `RetailData.xlsx` — Original dataset from Kaggle  
- `Cleansed RetailData.csv` — Cleaned dataset after SQL processing  
- `RFM RetailData Analysis.csv` — Dataset with RFM segmentation results  
- `Cleansed RetailData Script.sql` — SQL script used for data cleaning  
- `Retail Analysis Report.pbix` — Power BI dashboard file  
- `README.md` — Project documentation  

---

## Using the Dashboard

1. Open the Power BI report file.  
2. Interact with visual elements to explore trends and insights.  
3. Apply filters (year, month, country) to analyze specific segments.  
4. Use labeled visuals to quickly interpret customer behavior and sales performance.

---

## Summary

This project demonstrates a complete retail analytics pipeline — from raw data cleansing to advanced customer segmentation and business intelligence reporting. The resulting insights provide visibility into purchasing behavior, revenue trends, and customer value, enabling more informed retail strategy and decision making.
