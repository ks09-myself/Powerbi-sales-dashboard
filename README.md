# 🚴 Adventure Works Sales & Customer Analytics | Power BI

An end-to-end **Power BI data analytics project** built using the Adventure Works dataset to analyze sales performance, customer behavior, product performance, profitability, orders, returns, and geographical trends.

The project demonstrates how raw business data can be transformed using **Power Query, data modeling, DAX, and Power BI visualizations** to create an interactive business intelligence dashboard and generate meaningful insights.

---

# 📌 Project Overview

The **Adventure Works Sales & Customer Analytics** project analyzes business data across customers, products, product categories, territories, orders, revenue, profit, and returns.

The project was created as part of my **Power BI training through a Udemy course** and focuses on developing practical skills in data preparation, data modeling, DAX calculations, interactive visualizations, and dashboard design.

The analysis focuses on:

* Overall sales performance
* Revenue and profit analysis
* Order performance
* Customer analysis
* Product performance
* Product category analysis
* Return rate analysis
* Geographic sales analysis
* Monthly and weekly trends
* Top-performing products
* Customer-level analysis
* Business performance KPIs

The project follows an end-to-end analytics workflow:

**Raw CSV Data → Power Query → Data Cleaning & Transformation → Data Modeling → DAX → Power BI Dashboard → Business Insights**

---

# 🎯 Business Objective

The main objective of this project is to analyze Adventure Works business data and create an interactive Power BI solution that helps users understand sales performance, customer behavior, product performance, profitability, and returns.

The analysis aims to answer questions such as:

* What is the total revenue generated?
* What is the total profit?
* How many orders were placed?
* How many customers were served?
* What is the return rate?
* Which products generate the highest revenue?
* Which product categories perform best?
* How are sales changing over time?
* Which customers generate the most revenue?
* Which territories contribute the most to sales?
* Which products have higher return rates?
* How does revenue compare with previous periods?
* Which factors contribute to changes in business performance?

---

# 🛠️ Tech Stack

### Power BI

* **Power BI Desktop**
* **Power Query** for data cleaning and transformation
* **DAX** for calculated measures and KPIs
* Data modeling
* Relationships between tables
* Interactive visualizations
* Slicers and filters
* Drill-through analysis
* Tooltips
* Bookmarks
* Decomposition Tree
* Map visualization
* Dashboard navigation

### Data

* CSV files
* Adventure Works business dataset
* Customer data
* Product data
* Product category and subcategory data
* Calendar/date data
* Territory data
* Sales/order data
* Returns data

---

# 📂 Data Source

The project uses raw CSV files based on the **Adventure Works** dataset.

The raw data is loaded into Power BI and transformed using Power Query before being used for data modeling and analysis.

The dataset contains information related to:

* Customers
* Products
* Product categories
* Product subcategories
* Orders
* Calendar/date
* Territories
* Returns

### Raw Data Files

The raw CSV files used in this project are included in the repository.

Example project structure:

```text
Data/
├── Customers.csv
├── Products.csv
├── Product_Categories.csv
├── Product_Subcategories.csv
├── Calendar.csv
├── Territories.csv
├── Sales.csv
└── Returns.csv
```

> File names should be updated according to the exact CSV filenames you upload to GitHub.

---

# 🧹 Data Preparation & Transformation

Power Query was used to prepare the raw data before analysis.

The data preparation process includes:

* Importing raw CSV files
* Reviewing data types
* Cleaning and transforming columns
* Handling data inconsistencies
* Creating required calculated columns
* Preparing date fields
* Structuring lookup tables
* Preparing data for relationships
* Creating a suitable data model for reporting

---

# 🧩 Data Model

The Power BI project uses a relational data model consisting of multiple lookup and supporting tables.

Key tables include:

* **Customer Lookup**
* **Product Lookup**
* **Product Categories Lookup**
* **Product Subcategories Lookup**
* **Calendar Lookup**
* **Territory Lookup**
* **Measure Table**
* Customer and product metric selection tables

The model enables analysis across different business dimensions such as customer, product, category, date, and geography.

---

# 📐 DAX & KPI Development

DAX was used to create business measures and KPIs required for the dashboard.

Key metrics include:

* **Total Revenue**
* **Total Profit**
* **Total Orders**
* **Total Customers**
* **Total Returns**
* **Return Rate**
* **Revenue per Customer**
* Monthly Revenue
* Monthly Orders
* Monthly Profit
* Monthly Returns
* Previous Month Revenue
* Previous Month comparisons

These measures are used throughout the dashboard to provide dynamic and interactive analysis.

---

# 📊 Power BI Dashboard

The Power BI report contains multiple analytical pages designed for different business perspectives.

### Main Dashboard Pages

1. **Executive Dashboard**
2. **Customer Detail**
3. **Product Detail**
4. **Map**
5. **Decomposition Tree**

Additional supporting pages are used for interactive tooltips and dashboard functionality.

---

# 📊 Page 1 — Executive Dashboard

The **Executive Dashboard** provides a high-level overview of overall business performance.

### KPI Cards

The dashboard includes KPIs such as:

* **Revenue**
* **Profit**
* **Orders**
* **Return Rate**
* **Total Customers**

### Trend Analysis

The dashboard provides trend-based analysis including:

* Monthly Revenue
* Monthly Orders
* Monthly Profit
* Monthly Returns
* Weekly Orders

Performance can also be compared against targets and previous periods.

### Product Analysis

The dashboard includes a **Top 10 Products** analysis using metrics such as:

* Orders
* Revenue
* Return Rate

This allows users to quickly identify important products and evaluate their performance.

---

# 👥 Page 2 — Customer Detail

The **Customer Detail** page focuses on customer-level analysis.

The analysis includes:

* Customer revenue
* Customer orders
* Customer performance
* Customer segmentation
* Customer income level
* Customer occupation
* Top customers

The dashboard also provides interactive customer analysis to help understand which customer groups contribute most to business performance.

---

# 🛍️ Page 3 — Product Detail

The **Product Detail** page provides a detailed view of individual product performance.

The analysis can be used to evaluate:

* Product revenue
* Product orders
* Product performance
* Product subcategories
* Product categories
* Product return performance

The page also supports **drill-through analysis**, allowing users to move from a high-level product view to detailed product-level information.

---

# 🗺️ Page 4 — Geographic Analysis

The **Map** page provides geographic analysis of business performance.

The dashboard uses territory-related information to analyze performance across different geographic areas.

This helps users understand:

* Regional performance
* Sales distribution
* Geographic contribution
* Territory-level business activity

---

# 🌳 Page 5 — Decomposition Tree

The **Decomposition Tree** provides interactive analytical exploration.

It allows users to break down business metrics across different dimensions and investigate the factors contributing to overall performance.

This type of visualization is useful for answering questions such as:

* What factors contribute to revenue?
* Which categories drive performance?
* Which territories perform better?
* Which customer or product segments contribute most?

---

# 🔎 Interactive Dashboard Features

The Power BI report includes several interactive features designed to improve data exploration.

### Filters & Slicers

Users can dynamically filter the report and analyze specific portions of the dataset.

### Drill-through

The Product Detail page supports drill-through functionality to move from summary-level analysis to detailed product analysis.

### Tooltips

Custom tooltip pages provide additional information when users interact with dashboard visuals.

### Bookmarks

Bookmarks are used to support interactive report navigation and dashboard presentation.

### Decomposition Tree

Users can interactively explore the factors contributing to business metrics.

### Map Analysis

Geographic visuals provide another perspective for analyzing business performance.

---

# 💡 Key Business Insights

The dashboard is designed to identify insights related to:

### 1. Overall Business Performance

Revenue, profit, orders, customers, and returns provide an overall view of business health.

### 2. Revenue Trends

Monthly revenue analysis helps identify changes in business performance over time.

### 3. Profitability

Profit analysis helps evaluate whether revenue growth is translating into stronger profitability.

### 4. Customer Performance

Customer-level analysis helps identify high-value customers and understand customer characteristics.

### 5. Product Performance

Top-performing products can be identified based on revenue and order volume.

### 6. Returns

Return analysis helps identify products and areas where return rates may require further investigation.

### 7. Geographic Performance

Territory and map analysis provides insights into regional business performance.

---

# 🎯 Business Recommendations

Based on the analysis available through the dashboard, businesses can use these insights to:

### 📌 Focus on High-Performing Products

Identify products generating strong revenue and order volumes and prioritize them for inventory and marketing strategies.

### 📌 Improve Customer Retention

Analyze high-value customers and customer segments to develop targeted customer retention strategies.

### 📌 Monitor Product Returns

Identify products with relatively high return rates and investigate potential product or customer-related causes.

### 📌 Analyze Regional Performance

Use geographic analysis to identify stronger and weaker territories and optimize regional strategies.

### 📌 Monitor Trends

Use monthly and weekly trends to support planning around demand, revenue, orders, and profitability.

---

# 📸 Dashboard Preview

## Executive Dashboard

![Executive Dashboard](Screenshots/Executive_Dashboard.png)

The Executive Dashboard provides an interactive overview of revenue, profit, orders, customers, returns, product performance, and business trends.

## Customer Detail

![Customer Detail](Screenshots/Customer_Detail.png)

The Customer Detail page provides customer-level analysis and helps identify high-value customer segments.

## Product Detail

![Product Detail](Screenshots/Product_Detail.png)

The Product Detail page provides detailed analysis of individual products and their performance.

## Geographic Analysis

![Map Analysis](Screenshots/Map_Analysis.png)

The Map page provides geographic analysis of business performance across territories.

## Decomposition Tree

![Decomposition Tree](Screenshots/Decomposition_Tree.png)

The Decomposition Tree allows interactive exploration of the factors contributing to business performance.

> Update the screenshot filenames above to match the actual files you upload to GitHub.

---

# 📁 Project Structure

```text
Adventure-Works-PowerBI-Dashboard/
│
├── Data/
│   ├── Customers.csv
│   ├── Products.csv
│   ├── Product_Categories.csv
│   ├── Product_Subcategories.csv
│   ├── Calendar.csv
│   ├── Territories.csv
│   ├── Sales.csv
│   └── Returns.csv
│
├── Screenshots/
│   ├── Executive_Dashboard.png
│   ├── Customer_Detail.png
│   ├── Product_Detail.png
│   ├── Map_Analysis.png
│   └── Decomposition_Tree.png
│
├── Adventure-Works-PowerBI-Dashboard.pbix
└── README.md
```

---

# 📚 Skills Demonstrated

```text
- Power BI
- Power Query
- DAX
- Data Cleaning & Transformation
- Data Modeling
- Data Analysis
- KPI Development
- Data Visualization
- Dashboard Design
- Interactive Reporting
- Drill-through Analysis
- Tooltip Design
- Bookmark Navigation
- Customer Analysis
- Product Analysis
- Sales Analysis
- Profitability Analysis
- Return Rate Analysis
- Geographic Analysis
- Trend Analysis
- Business Intelligence
- Business Insights
- Data-Driven Decision Making
```

---

# 🚀 Project Outcome

This project demonstrates the complete process of converting raw CSV business data into an interactive Power BI business intelligence solution.

It showcases practical experience with:

**Data Preparation → Data Modeling → DAX → Visualization → Interactive Analysis → Business Insights**

The project was developed during Power BI training through a Udemy course as a practical exercise to strengthen Power BI and data analytics skills.
