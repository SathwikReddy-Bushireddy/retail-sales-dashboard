# 🛍️ Retail Sales Analytics Dashboard

> An interactive Business Intelligence dashboard built using **Power BI**, **Power Query**, **DAX**, and **Excel** to analyze retail sales performance, customer behavior, product profitability, and regional trends.

---

# 📌 Project Overview

The Retail Sales Analytics Dashboard is designed to help business stakeholders monitor key performance indicators (KPIs), identify sales trends, evaluate product performance, and gain actionable business insights.

The dashboard transforms raw retail transaction data into meaningful visualizations that support data-driven decision-making. It enables managers to understand which products, regions, and customer segments contribute the most to revenue and profitability.

---

# 🎯 Business Problem

Retail companies generate thousands of transactions every day, making it difficult to identify important business trends through raw data alone.

The company wanted answers to questions such as:

- What is the total sales revenue?
- How much profit is being generated?
- Which products generate the highest sales?
- Which customer segment contributes the most revenue?
- Which regions perform the best?
- How do sales change over time?
- What is the company's profit margin?

This dashboard provides a centralized solution to answer these questions.

---

# 🎯 Project Objectives

- Analyze retail sales performance
- Track important business KPIs
- Monitor monthly sales trends
- Identify top-performing products
- Compare regional sales performance
- Analyze customer segments
- Enable interactive filtering for business users
- Support data-driven business decisions

---

# 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Power BI | Dashboard Development |
| Power Query | Data Cleaning & Transformation |
| DAX | KPI Calculations |
| Microsoft Excel | Dataset Storage & Initial Cleaning |

---

# 📂 Dataset Information

Dataset: **Sample Superstore**

The dataset contains retail order information including:

- Order Details
- Customer Information
- Product Details
- Sales
- Profit
- Discount
- Quantity
- Shipping Details
- Region
- State

### Dataset Columns

- Row ID
- Order ID
- Order Date
- Ship Date
- Ship Mode
- Customer ID
- Customer Name
- Segment
- Country
- City
- State
- Postal Code
- Region
- Product ID
- Category
- Sub Category
- Product Name
- Sales
- Quantity
- Discount
- Profit

---

# 🧹 Data Preparation

The dataset was cleaned and transformed using Power Query.

### Data Cleaning Steps

- Removed duplicate records
- Verified missing values
- Corrected data types
- Converted date columns into Date format
- Standardized text values
- Created additional analytical columns:
  - Year
  - Month Number
  - Month Name
  - Quarter
  - Day Name

---

# 📊 Dashboard KPIs

The dashboard tracks the following Key Performance Indicators:

- 💰 Total Sales
- 📈 Total Profit
- 📦 Total Orders
- 👥 Total Customers
- 📊 Profit Margin

---

# 📐 DAX Measures

### Total Sales

```DAX
Total Sales =
SUM(Sheet1[Sales])
```

### Total Profit

```DAX
Total Profit =
SUM(Sheet1[Profit])
```

### Total Orders

```DAX
Total Orders =
DISTINCTCOUNT(Sheet1[Order_ID])
```

### Total Customers

```DAX
Total Customers =
DISTINCTCOUNT(Sheet1[Customer_ID])
```

### Profit Margin

```DAX
Profit Margin =
DIVIDE([Total Profit],[Total Sales])
```

---

# 📈 Dashboard Visualizations

The dashboard consists of the following visualizations:

## KPI Cards

- Total Sales
- Total Profit
- Total Orders
- Total Customers
- Profit Margin

---

## Monthly Sales Trend

Visual Type:
- Line Chart

Purpose:
- Analyze monthly sales growth over time.

---

## Sales by Category

Visual Type:
- Clustered Bar Chart

Purpose:
- Compare sales across product categories.

---

## Sales by Segment

Visual Type:
- Donut Chart

Purpose:
- Understand customer contribution by segment.

---

## Sales by Region

Visual Type:
- Bar Chart

Purpose:
- Compare sales performance across different regions.

---

## Top Products

Visual Type:
- Bar Chart

Purpose:
- Identify products generating the highest revenue.

---

## Interactive Filters

Users can filter the dashboard by:

- Year
- Region
- Category

---

# 📊 Business Insights

## Executive Summary

- Generated over **2 Million** in sales.
- Earned approximately **286K** in profit.
- Processed more than **5000** orders.
- Served **793** unique customers.
- Achieved a profit margin of approximately **12.47%**.

---

## Product Insights

- Technology generated the highest sales.
- Office Supplies maintained consistent performance.
- A few products contributed significantly to total revenue.

---

## Customer Insights

- Consumer segment contributed the highest sales.
- Corporate customers formed the second-largest customer base.
- Home Office segment contributed the least revenue.

---

## Regional Insights

- East region generated the highest sales.
- Central region showed comparatively lower performance.
- Regional differences indicate opportunities for targeted marketing.

---

## Sales Trend Insights

- Sales increased steadily over the years.
- Strong seasonal peaks suggest higher demand during certain periods.
- Business growth remained consistent throughout the analyzed period.

---

# 💼 Business Recommendations

Based on the analysis:

- Increase inventory for Technology products.
- Improve marketing efforts in lower-performing regions.
- Focus customer retention strategies on the Consumer segment.
- Optimize pricing and discount strategies to improve profitability.
- Monitor top-selling products to sustain revenue growth.

---

# 📷 Dashboard Preview

![Retail Sales Dashboard](Images/dashboard.png)


---

# 📁 Project Structure

```
Retail-Sales-Analytics-Dashboard
│
├── Dashboard
│      Retail Sales Analytics Dashboard.pbix
│
├── Dataset
│      Sample - Superstore.xlsx
│
├── Images
│      dashboard.png
│
├── README.md
│
└── LICENSE
```

---

# 🚀 Future Enhancements

Future improvements for this project include:

- Drill-through Reports
- Customer Lifetime Value Analysis
- Forecasting Sales
- Profit Forecasting
- Inventory Analysis
- Dynamic Report Tooltips
- Mobile Optimized Dashboard
- Power BI Service Deployment
- Automated Data Refresh

---

# 📚 Key Learnings

Through this project, I gained hands-on experience in:

- Business Intelligence
- Data Cleaning
- Data Transformation
- Data Visualization
- DAX Calculations
- Dashboard Design
- Business Storytelling
- KPI Development
- Interactive Report Building

---

# 🎯 Skills Demonstrated

- Microsoft Power BI
- Power Query
- DAX
- Data Cleaning
- Data Visualization
- Business Analytics
- Dashboard Design
- KPI Development
- Data Storytelling
- Retail Sales Analysis

---

# 👨‍💻 Author

**Sathwik Reddy**

---

# ⭐ If you found this project useful, consider giving it a star!