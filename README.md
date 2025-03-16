# Hypermarket Sales Performance Analysis (Power BI)

## Overview
For this project, I worked on analyzing sales data for a hypermarket using Power BI. My focus was on cleaning the dataset, designing a well-structured data model, and implementing Year-to-Date (YTD) and Previous Year-to-Date (PYTD) measures to track performance trends. I created various visualizations to explore sales performance across different categories like product, customer segments, and time periods.

## Data Cleaning & Preparation
To ensure accurate analysis, I started by:
- Renaming columns for consistency and clarity.
- Removing duplicates in primary keys and duplicate orders.
- Checking for data integrity before moving on to modeling.
- Creating a date dimension table for time intelligence calculations.
- Merging and transforming the initial sales table to create a star schema, ensuring efficient data modeling and analysis.

## Data Modelling
I structured the data using a star schema, making it efficient for querying and analysis. The model consists of:
- **Fact Table:** Sales transactions.
- **Dimension Tables:**
  - Customers (customer details)
  - Products (product catalog)
  - Date (calendar table for time-based analysis)
 
    ![Screenshot 2025-03-16 164835](https://github.com/user-attachments/assets/11fc11d1-d21e-4d53-9a61-7439de146bf8)


## Key DAX Measures
To gain insights into business performance, I created several key measures:

### Sales & Profit Measures
- Total Sales
- Total Quantity
- Gross Profit
- Average Order Value (AOV)

### Time Intelligence Measures
- Year-to-Date (YTD) Sales
- Previous Year-to-Date (PYTD) Sales
- YTD vs. PYTD Growth Percentage

### Customer Metrics
- Total Customers
- Customer Lifetime Value (CLV)
- Churn Rate
- Average Revenue Per Customer (ARPC)

## Visualizations & Insights
To bring the data to life, I designed three interactive report pages:

### 1. YTD vs. PYTD Analysis
- **Sales YTD vs. PYTD by Month, Segment, and State**: Highlights performance trends across time periods.
- **YTD vs. PYTD by Category**: Compares product category performance over time.
- **Gross Profit YTD & PYTD by Month**: A stacked bar and line chart showing profit breakdowns.
- **Sales Heatmap by Region**: Identifies regional performance patterns.
  
  ![image](https://github.com/user-attachments/assets/0bdcf76c-5b2b-4676-b747-30a63d5c4d52)


### 2. Product Performance Analysis
- **Top and Bottom Products by Sales and GP%**: Identifies best and worst-performing products.
- **Total Sales by Category and Subcategory**: Shows revenue distribution across product types.
- **Sales vs. GP% Scatter Plot**: Highlights product profitability.
- **Stock Turnover Insights**: Analyzes product demand and inventory efficiency.
  
  ![image](https://github.com/user-attachments/assets/101b2097-c12a-4b13-8047-a2f0ace8d807)


### 3. Customer Performance Analysis
- **Total Customers, ARPC, CLV, and Churn Rate**: Key customer KPIs.
- **Customer Acquisition & Churn Trends**: Line and bar charts tracking customer growth and retention.
- **Sales & Churn Rate by Customer Segment**: Compares performance across consumer, corporate, and home office segments.
- **CLV Analysis by Year and Segment**: Examines how customer value evolves over time.
  
  ![image](https://github.com/user-attachments/assets/5874bf88-1397-4d3b-809e-d06efd88a078)


## Tools Used
- Power BI
- DAX
- Power Query


This project provides a comprehensive analysis of hypermarket sales performance, covering sales trends, product performance, and customer behavior. The insights from this report can be used to improve decision-making, optimize marketing strategies, and enhance overall business performance.
