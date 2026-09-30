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

The **Cookies & Chocolate Sales Performance Dashboard** is an enterprise-grade retail analytics solution built in Power BI. Serving as an executive decision-support system, it evaluates commercial sales performance across products, regional corporate accounts, and multi-year time horizons.

The platform transforms **1,123,480 units sold** across **699 validated orders** into an executive analytical layer monitoring **$4.68M in gross revenue**, **$2.71M in operating profit**, and a robust **57.94% overall profit margin**.

---

## 📊 Commercial Financial Summary & Core KPIs

| Metric | Portfolio Value | Description / Business Impact |
| :--- | :---: | :--- |
| **Total Gross Revenue** | **$4,676,294.50 (~$4.68M)** | Total realized revenue across 699 wholesale/retail order transactions |
| **Total Product Cost** | **$1,966,789.63 (~$1.97M)** | Total cost of goods sold (COGS) based on product cost matrices |
| **Total Operating Profit** | **$2,709,504.88 (~$2.71M)** | Net profit cleared from product sales across all customer regions |
| **Overall Profit Margin** | **57.94%** | Portfolio-wide profitability margin across product categories |
| **Total Volume Sold** | **1,123,480 Units** | Gross cookie packages and confections shipped to clients |
| **Order Transactions** | **699 Orders** | Recorded business-to-business and commercial account purchases |
| **Average Order Value (AOV)** | **$6,689.98** | Mean sales ticket value per customer purchase (`Total Revenue / Orders`) |
| **Active Corporate Clients** | **5 Accounts (5 States)** | Distributed across Wisconsin, New York, Utah, Alabama, and Washington |
| **Year-over-Year Target Growth** | **223.9% Above Target** | Actual sales performance dramatically outperformed target benchmark |

---

## 📈 Product Contribution & Margin Analysis

The product portfolio comprises 6 core confectionery types exhibiting varied demand elasticity, pricing power, and margin contribution:

| Product Type | Units Sold | Total Revenue ($) | Total Cost ($) | Total Profit ($) | Profit Margin % | Revenue Share % |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| **Chocolate Chip** | 338,239.5 | $1,691,197.50 | $676,479.00 | $1,014,718.50 | **60.00%** | **36.17%** |
| **White Chocolate Macadamia Nut** | 160,098.5 | $960,591.00 | $440,270.88 | $520,320.13 | **54.17%** | **20.54%** |
| **Oatmeal Raisin** | 155,315.0 | $776,575.00 | $341,693.00 | $434,882.00 | **56.00%** | **16.61%** |
| **Snickerdoodle** | 146,846.0 | $587,384.00 | $220,269.00 | $367,115.00 | **62.50%** | **12.56%** |
| **Sugar** | 168,783.0 | $506,349.00 | $210,978.75 | $295,370.25 | **58.33%** | **10.83%** |
| **Fortune Cookie** | 154,198.0 | $154,198.00 | $77,099.00 | $77,099.00 | **50.00%** | **3.30%** |
| **Total / Weighted Average** | **1,123,480.0** | **$4,676,294.50** | **$1,966,789.63** | **$2,709,504.88** | **57.94%** | **100.0%** |

---

## 🌎 Geographic & Regional Account Breakdown

Sales volume is distributed across 5 primary state territories:

| State | Order Count | Units Sold | Total Revenue ($) | Total Profit ($) | Profit Margin % | Revenue Share % |
| :--- | :---: | :---: | :---: | :---: | :---: | :---: |
| **Wisconsin** | 207 | 329,084.5 | $1,422,437.00 | $823,852.40 | **57.92%** | **30.42%** |
| **New York** | 156 | 266,890.0 | $1,108,643.00 | $639,674.55 | **57.70%** | **23.71%** |
| **Utah** | 132 | 219,895.0 | $901,841.00 | $522,250.43 | **57.91%** | **19.29%** |
| **Alabama** | 114 | 179,447.5 | $725,758.50 | $423,499.63 | **58.35%** | **15.52%** |
| **Washington** | 90 | 128,163.0 | $517,615.00 | $300,227.88 | **58.00%** | **11.07%** |

---

## 💡 In-Depth Financial Analysis & Key Insights

1. **Volume & Profit Leader (Chocolate Chip):**
   - Generating **$1.69M in revenue (36.2% share)** and **$1.01M in profit**, Chocolate Chip is the undisputed commercial anchor. Combining high consumer demand with a **60.0% margin**, it drives over 37% of portfolio operating profits.
2. **Margin Champion (Snickerdoodle):**
   - Although 4th in sales volume ($587.4K), **Snickerdoodle boasts the portfolio's highest margin at 62.50%**, making it an ideal candidate for targeted B2B promotion and product bundling.
3. **Regional Market Concentration:**
   - **Wisconsin (30.4%) and New York (23.7%)** collectively capture more than **54% of total revenues ($2.53M)**, highlighting vital geographical dependencies.
4. **Target Outperformance:**
   - With sales pacing from $1.1M (2019) to over $3.6M (2020), actual commercial velocity outpaced target forecasts by **223.9%**, driven by strong wholesale re-order rates.

---

## 📐 Key DAX Measures & Formula Reference

All core calculations are centralized inside the dedicated `Dax` table in the Power BI Semantic Model:

### 1. Revenue, Cost & Profit Engine
Calculates line-level commercial realization across the transactions fact table:

```dax
// Total Gross Revenue across all orders
Total Revenue = 
SUM('fact_orders'[CC Total Revenue])

// Total Cost of Goods Sold (COGS)
Total Cost = 
SUM('fact_orders'[CC Total Cost])

// Net Gross Profit Realization
Total Profit = 
SUM('fact_orders'[CC Total Profit])

// Overall Profitability Ratio
Profit Margin % = 
DIVIDE([Total Profit], [Total Revenue])
```

### 2. Operational Volume & Customer Metrics
Measures transaction frequency, customer base breadth, and order density:

```dax
// Total unique purchase orders
Count Orders = 
DISTINCTCOUNT('fact_orders'[order_key])

// Total unique corporate customer accounts
Count Customers = 
COUNTROWS('dim_customer')

// Market geographic footprint
Count Cities = 
DISTINCTCOUNT('dim_customer'[city])

// Average order ticket value (AOV)
AVG Sales by Order = 
DIVIDE([Total Revenue], [Count Orders])
```

### 3. Dynamic Time Intelligence & YoY Benchmarking
Evaluates performance trends against prior-year milestones:

```dax
// Same Period Last Year Revenue
SPLY = 
CALCULATE(
    [Total Revenue], 
    SAMEPERIODLASTYEAR('dim_date'[Date])
)
```

---

## 🎯 Business Problem & Objectives

1. 📈 **Sales Expansion & Velocity:** Track revenue growth across monthly and quarterly cycles.
2. 🍪 **Product Portfolio Optimization:** Benchmark profitability across product types to determine optimal manufacturing allocation.
3. 🌎 **Geographic Penetration:** Identify high-yield sales territories and underserved regional accounts.
4. 💰 **Margin Protection:** Ensure cost fluctuations do not erode the healthy 57%+ target margin.
5. 🎯 **Target Benchmark Tracking:** Continuously monitor actual vs. expected target lines using Power BI KPI visuals.

---

## 🖼️ Dashboard Visual Tour & Storytelling

### 1. Executive Overview Dashboard
<p align="center">
  <img src="./Dashboard%20Previews/Overview%20Page.jpg" alt="Cookies & Chocolate Sales Performance — Overview Dashboard" width="95%">
</p>

*The overview page synthesizes KPI cards (Total Revenue, Total Profit, Profit Margin %, Count Orders), an Area Chart for date drill-down, a Product Revenue Column Chart, a State-level Bar Chart, and a YoY Target KPI indicator.*

### 2. Enterprise Star Schema Data Model
<p align="center">
  <img src="./Dashboard%20Previews/Model.png" alt="Cookies & Chocolate Sales Performance — Power BI Data Model" width="95%">
</p>

*Normalized dimensional model connecting central transactional orders with customer, product, date, and measure calculation tables.*

---

## 🏗️ Data Architecture & Star Schema

The enterprise model is architected as an optimized **Star Schema**:

- **Fact Table:**
  - `fact_orders` — Grain: individual order line items. Contains `order_key`, `Date`, `Units Sold`, foreign keys (`product_key`, `customer_key`), and calculated monetary columns (`CC Total Revenue`, `CC Total Cost`, `CC Total Profit`).
- **Dimension Tables:**
  - `dim_product` — Catalog dimension storing `product_type`, `revenue_per_product`, `cost_per_product`, and `product_key`.
  - `dim_customer` — Geographic and account dimension storing `customer_name`, `customer_address`, `city`, `state`, `zip_code`, and `country`.
  - `dim_date` — Calendar dimension supporting continuous time intelligence (`Year`, `Quarter`, `Month`, `Day`).
  - `Dax` — Dedicated calculation group table holding all DAX measures.

---

## 🛠️ Tools & Technologies

- 📊 **Power BI Desktop:** KPI design, visual storytelling, custom chart configuration, and interactive slicers.
- 📐 **DAX (Data Analysis Expressions):** Profit margins, distinct counting, average order sizing, and SPLY time intelligence.
- 🗄️ **Power BI Project (PBIP) & TMDL:** Source-control versioning for enterprise tabular model definitions.
- ⚡ **Power Query (M):** Automated state normalization, null-customer key imputation, and multi-sheet staging.
- 🏗️ **Dimensional Data Modeling:** 1-to-many single-direction star schema architecture.

---

## 📜 License & Author

- **Author:** Kerelos Nakhla ([GitHub](https://github.com/Kerelos-Nakhla))
- **License:** MIT License
