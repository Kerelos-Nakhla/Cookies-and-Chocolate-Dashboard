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

The **Cookies & Chocolate Sales Performance Dashboard** is an interactive **Power BI** business intelligence solution designed to evaluate sales performance across products, customers, regions, and time.

The project transforms transactional order data into an executive analytical layer covering **revenue, profit, order volume, product contribution, regional performance, sales trends, and target achievement**.

> **Business question:** Where is the business generating revenue and profit, which products and regions drive performance, and how effectively is actual sales performance tracking against target?

---

## 📊 Portfolio KPIs & Commercial Performance

| Metric | Value | Business Meaning |
| :--- | :---: | :--- |
| **Total Revenue** | **$4.68M** | Total sales generated across the analyzed transactions |
| **Total Profit** | **$2.71M** | Profit generated across the analyzed sales portfolio |
| **Profit Margin** | **57.94%** | Overall profitability of the analyzed sales |
| **Total Orders** | **699** | Recorded customer orders |
| **Target Performance** | **223.9% Above Target** | Actual sales exceeded the modeled target benchmark |
| **Analysis Period** | **2019–2020** | Period covered by the reported time-trend analysis |

---

## 🎯 Business Problem & Objectives

The dashboard was developed to answer five core commercial questions:

1. 📈 **Revenue Growth** — How does sales performance change over time?
2. 🍪 **Product Contribution** — Which products generate the largest share of revenue?
3. 🌎 **Regional Performance** — Which states and regions contribute most to sales?
4. 💰 **Profitability** — How much profit is generated and what is the resulting margin?
5. 🎯 **Target Achievement** — How does actual performance compare with the target?

---

## 💡 In-Depth Sales Analysis & Business Insights

### 1. Revenue Expansion

Revenue increased from approximately **$1.1M in 2019** to **$3.6M in 2020**, making time-based performance an important analytical dimension.

### 2. Product Contribution

**Chocolate Chip Cookies** generated the highest revenue contribution, followed by **White Chocolate Macadamia**.

This identifies the products that contribute most strongly to the commercial portfolio.

### 3. Regional Performance

**Wisconsin** recorded the highest sales performance in the existing analysis, followed closely by **New York**.

Regional comparison helps identify where commercial activity is concentrated.

### 4. Profitability

The portfolio generated **$2.71M in profit from $4.68M in revenue**, resulting in a **57.94% profit margin**.

The analysis therefore evaluates profitability alongside revenue rather than treating sales volume as the only performance indicator.

### 5. Target Achievement

Actual sales performance reached **223.9% above the modeled target**, providing a dedicated target-vs-actual perspective within the dashboard.

---

## 🧠 Analytical Framework

**Raw Transactions → Data Preparation → Star Schema Modeling → DAX KPI Development → Product Analysis → Regional Analysis → Time Analysis → Target Tracking → Business Insights**

The workflow is designed around business questions and decision-support outcomes rather than isolated visuals.

---

## 🖼️ Dashboard Visual Tour & Storytelling

### 1. Executive Overview

<p align="center">
  <img src="./Dashboard%20Previews/Overview%20Page.jpg" alt="Cookies & Chocolate Sales Performance — Overview Dashboard" width="95%">
</p>

The executive overview brings together the main commercial KPIs, sales trends, product contribution, regional performance, profitability, and target tracking.

### 2. Data Model

<p align="center">
  <img src="./Dashboard%20Previews/Model.png" alt="Cookies & Chocolate Sales Performance — Power BI Data Model" width="95%">
</p>

The semantic model connects the transactional order fact table with reusable customer, product, and date dimensions to support consistent filtering and aggregation.

---

## 🏗️ Data Architecture & Star Schema

The project uses a **Star Schema** to separate transactional sales records from descriptive business dimensions.

### Fact Table

- **`fact_orders`** — Transaction-level order records, sales values, product references, customer references, and order dates

### Dimension Tables

- **`dim_date`** — Date and time-based analysis
- **`dim_product`** — Cookie and chocolate product attributes
- **`dim_customer`** — Customer and geographic attributes

### 📐 Model Design

The fact table acts as the analytical center of the model while the dimension tables provide reusable filtering and grouping across product, customer, regional, and time perspectives.

---

## 🛠️ Tools & Technologies

- 📊 **Power BI Desktop** — Dashboard development, KPI reporting, filtering, and visualization
- ⚡ **Power Query (M)** — Data ingestion, cleaning, transformation, and preparation
- 📐 **DAX** — Revenue, profit, margin, order, target, and analytical calculations
- 🧩 **Star Schema Modeling** — Fact/dimension architecture and relationship design
- 📈 **Business Analytics** — Product contribution, regional performance, time-series analysis, profitability, and target tracking

---

## 📁 Data Sources

The current repository contains the normalized datasets used by the updated Power BI model:

```
Data/
├── dim_customer.xlsx
├── dim_date.xlsx
├── dim_product.xlsx
└── fact_orders.xlsx
```

| Dataset | Role |
| :--- | :--- |
| **dim_customer.xlsx** | Customer and geographic attributes |
| **dim_date.xlsx** | Date dimension for time-based analysis |
| **dim_product.xlsx** | Product and cookie/chocolate attributes |
| **fact_orders.xlsx** | Transaction-level order and sales data |

The previous source workbooks have been removed from the repository to keep the project aligned with the current Star Schema model.

---

## 📂 Repository Structure

```
Cookies-and-Chocolate-Dashboard/
│
├── Cookies & Chocolate.pbix
│
├── Dashboard Previews/
│   ├── Overview Page.jpg
│   └── Model.png
│
├── Data/
│   ├── dim_customer.xlsx
│   ├── dim_date.xlsx
│   ├── dim_product.xlsx
│   └── fact_orders.xlsx
│
├── LICENSE
└── README.md
```

---

## 🚀 How to Explore the Project

1. Download or clone the repository.
2. Open **`Cookies & Chocolate.pbix`** in Power BI Desktop.
3. Review the executive overview and core KPIs.
4. Explore product and regional performance.
5. Analyze revenue and profit trends over time.
6. Compare actual performance against target.
7. Use the report filters to investigate different customers, products, regions, and dates.
8. Review the **Dashboard Previews** folder to understand the report structure and data model.

---

## 🎯 Portfolio Focus

This project demonstrates practical **Data Analyst / BI Developer** capabilities across:

- Business question formulation
- Data cleaning and transformation
- Star Schema data modeling
- DAX measure development
- KPI design
- Product and regional performance analysis
- Profitability analysis
- Target-vs-actual analysis
- Interactive Power BI storytelling

The objective is to demonstrate how transactional sales data can be transformed into a structured analytical product that supports commercial decision-making.

---

## 📜 License & Author

- **Author:** Kerelos Nakhla ([GitHub](https://github.com/Kerelos-Nakhla))
- **License:** MIT License

---

<p align="center">
  <b>Built with Power BI • Power Query • DAX • Business Intelligence</b>
</p>
