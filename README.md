# 📈 Retail Sales Performance Analysis

## 📌 Project Overview
This project provides a comprehensive analysis of retail sales data to identify key performance drivers, customer demographics, and seasonal trends. The goal is to transform raw transactional data into actionable business insights using **Excel**.

### 🎯 Objective
- Analyze sales performance across different product categories.
- Identify high-value customer segments (Age & Gender).
- Visualize monthly sales trends to detect seasonality.
- Provide data-driven recommendations for marketing and inventory management.

---

## 🛠️ Tools Used
- **Excel**: Data Cleaning, Pivot Tables, Pivot Charts, and Dashboarding.
- **Advanced Formulas**: `IFS`, `TEXT`, `YEAR`, `VLOOKUP`.
- **Data Visualization**: Slicers, Timelines, and Interactive Charts.

---

## 📊 Dashboard Preview
![Dashboard Preview](./screenshots/dashboard_preview.png)
*(Note: Replace this with your actual screenshot once you build the dashboard!)*

---

## 🔍 Key Data Insights
Based on the analysis of 1,000+ transactions:

1. **Top Category**: **Electronics** led all categories with **$156,905** in total revenue (approx. 34% of total sales).
2. **Seasonal Trends**: Revenue peaked significantly in **May ($53,150)** and **October ($46,580)**, suggesting successful spring and autumn promotional periods.
3. **Customer Demographics**: 
    - **Female customers** are the primary drivers of revenue, contributing **$232,840**.
    - The **45-54 age group** is the most profitable segment, spending over **$100,000**.
4. **Efficiency**: The Average Order Value (AOV) across all transactions is **$456**.

---

## 🛠️ Data Cleaning & Transformation
- **Date Formatting**: Standardized dates to ensure accurate time-series analysis.
- **New Features**: 
    - Created `Month` and `Year` columns for trend analysis.
    - Developed `Age Group` buckets (`18-24`, `25-34`, etc.) using `IFS` formulas to segment the customer base.
- **Data Integrity**: Checked for null values and duplicates to ensure 100% data accuracy.

---

## 💡 Recommendations
- **Targeted Marketing**: Increase ad spend for the **45-54 female demographic**, as they show the highest purchasing power.
- **Inventory Stocking**: Prepare for high-volume sales in **May** and **October** by increasing stock levels for Electronics.
- **Retention Strategy**: Develop a loyalty program specifically for the "Clothing" and "Beauty" categories to bring their revenue levels closer to Electronics.

---

## 🚀 How to Use
1. Download the `Retail_Sales_Analysis_Dashboard.xlsx` from the `dashboard` folder.
2. Open in Excel and use the **Slicers** (Region, Category, Gender) to filter the data dynamically.
