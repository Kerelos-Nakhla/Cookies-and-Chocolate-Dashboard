# 🍪 Cookies & Chocolate Sales Performance Analytics

<p align="center">
  <b>Executive Sales Intelligence, Product Contribution, Regional Performance & Profitability Analysis in Power BI</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI" />
  <img src="https://img.shields.io/badge/Power_Query-ETL-blue?style=for-the-badge" alt="Power Query" />
  <img src="https://img.shields.io/badge/DAX-Commercial_Analytics-success?style=for-the-badge" alt="DAX" />
  <img src="https://img.shields.io/badge/Sales_Analytics-Profitability-orange?style=for-the-badge" alt="Sales Analytics" />
</p>

---

## 📌 Executive Overview

The **Cookies & Chocolate Sales Performance Dashboard** is an interactive business intelligence solution built in **Power BI** to analyze sales performance across products, customers, regions, and time.

The project transforms transactional order data into an executive-level analytical view that connects **revenue, profit, order volume, product contribution, regional performance, and target achievement**.

The analysis is designed to answer a practical commercial question:

> **Where is the business generating revenue and profit, which products and regions drive performance, and how effectively is actual sales performance tracking against target?**

---

## 📊 Portfolio KPIs & Commercial Performance

| Metric | Value | Business Meaning |
| :--- | :---: | :--- |
| **Total Revenue** | **$4.68M** | Total sales generated across the analyzed transactions |
| **Total Profit** | **$2.71M** | Profit generated after the modeled product costs |
| **Profit Margin** | **57.94%** | Overall profitability of the analyzed sales portfolio |
| **Total Orders** | **699** | Number of recorded customer orders |
| **Target Performance** | **223.9% Above Target** | Actual sales significantly exceeded the modeled target |
| **Analysis Period** | **2019–2020** | Period used for the reported time-trend analysis |

---

## 🎯 Business Problem & Objectives

The dashboard was developed to provide management with a structured view of commercial performance and answer five core business questions:

1. 📈 **Revenue Growth:** How does sales performance change over time?
2. 🍪 **Product Contribution:** Which cookie and chocolate products generate the largest share of revenue?
3. 🌎 **Regional Performance:** Which states and regions contribute most to overall sales?
4. 💰 **Profitability:** How much profit is generated and what is the resulting profit margin?
5. 🎯 **Target Achievement:** How does actual sales performance compare with the defined target?

---

## 💡 In-Depth Sales Analysis & Key Insights

### 1. Strong Revenue Expansion

Revenue increased from approximately **$1.1M in 2019** to **$3.6M in 2020**, indicating substantial year-over-year expansion in the analyzed dataset.

This makes the time dimension an important part of the dashboard because overall performance is not only driven by product mix, but also by when sales were generated.

### 2. Product Contribution Concentration

**Chocolate Chip Cookies** generated the highest revenue contribution, followed by **White Chocolate Macadamia**.

This provides a clear starting point for product-level analysis by identifying the products responsible for the largest commercial contribution.

### 3. Regional Performance Differences

**Wisconsin** recorded the highest sales performance in the existing analysis, with **New York** following closely.

Regional comparison therefore provides another analytical layer for understanding where commercial activity is concentrated.

### 4. Strong Profitability

The analyzed portfolio generated **$2.71M in profit** from **$4.68M in revenue**, resulting in an overall **57.94% profit margin**.

This allows the dashboard to move beyond revenue reporting and evaluate the relationship between sales volume and profitability.

### 5. Target Achievement

Actual sales performance reached **223.9% above the modeled target**, indicating that the analyzed sales portfolio substantially exceeded the target benchmark.

Target tracking is therefore treated as a core performance indicator rather than an additional dashboard metric.

---

## 🧠 Analytical Framework

The project follows a business-first analytical workflow:

**Raw Transactions → Data Preparation → Data Modeling → KPI Development → Product Analysis → Regional Analysis → Time Analysis → Target Tracking → Business Insights**

This approach keeps the dashboard focused on **decision-support questions** rather than presenting charts independently.

---

## 🖼️ Dashboard Visual Tour & Storytelling

### 1. Executive Sales Dashboard

The main dashboard consolidates the core commercial KPIs and provides a high-level view of revenue, profit, orders, target performance, product contribution, regional performance, and sales trends.

> Dashboard preview assets can be added to the repository under `Dashboard Previews/` using the same standardized structure as the portfolio's other projects.

---

## 🏗️ Data Architecture & Star Schema

The project uses a **Star Schema** to separate transactional sales data from descriptive business dimensions.

### Fact Table

- `fact_orders` — Transaction-level order records, sales values, product references, customer references, and order dates

### Dimension Tables

- `dim_date` — Date, year, month, and time-based analysis
- `dim_product` — Cookie and chocolate product information
- `dim_customer` — Customer attributes and customer segmentation
- `dim_target` — Target values used for performance comparison

### 📐 Model Representation

The Power BI semantic model connects the order fact table to reusable dimensions, enabling consistent filtering and aggregation across product, customer, regional, and time perspectives.

---

## 🛠️ Tools & Technologies

- 📊 **Power BI Desktop:** Interactive dashboard development, KPI reporting, filtering, and visual analytics
- ⚡ **Power Query (M):** Data ingestion, cleaning, transformation, and preparation
- 📐 **DAX:** Revenue, profit, margin, order volume, target performance, and analytical calculations
- 🧩 **Data Modeling:** Star Schema design and dimensional relationships
- 📈 **Business Analytics:** Product contribution, regional performance, time-series analysis, profitability, and target tracking

---

## 📁 Data Sources

The project uses three Excel workbooks organized in the repository's `Data/` folder:

```
Data/
├── Cookie Types.xlsx
├── Customers.xlsx
└── Orders.xlsx
```

### Dataset Roles

| Dataset | Purpose |
| :--- | :--- |
| **Cookie Types.xlsx** | Product-level attributes and cookie/chocolate classifications |
| **Customers.xlsx** | Customer and geographic information |
| **Orders.xlsx** | Transaction-level sales and order activity |

---

## 📂 Repository Structure

```
Cookies-and-Chocolate-Dashboard/
│
├── Dashboard.pbix
├── Data/
│   ├── Cookie Types.xlsx
│   ├── Customers.xlsx
│   └── Orders.xlsx
│
└── README.md
```

---

## 🚀 How to Explore the Project

1. Download or clone the repository.
2. Open `Dashboard.pbix` in **Power BI Desktop**.
3. Review the executive KPIs.
4. Explore product contribution and regional performance.
5. Analyze revenue and profit trends over time.
6. Compare actual performance against the target.
7. Use the report filters to investigate specific products, customers, and regions.

---

## 🎯 Portfolio Focus

This project demonstrates practical **Data Analyst / BI Developer** capabilities across:

- Business question formulation
- Data cleaning and transformation
- Dimensional data modeling
- DAX measure development
- KPI design
- Product and regional performance analysis
- Profitability analysis
- Target-vs-actual analysis
- Interactive Power BI storytelling

The objective is to demonstrate how raw transactional data can be transformed into a structured analytical product that supports commercial decision-making.

---

## 📜 License & Author

- **Author:** Kerelos Nakhla ([GitHub](https://github.com/Kerelos-Nakhla))
- **License:** MIT License

---

<p align="center">
  <b>Built with Power BI • Power Query • DAX • Business Intelligence</b>
</p>
