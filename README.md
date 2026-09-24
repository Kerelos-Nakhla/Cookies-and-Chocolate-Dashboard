# Cookie Sales Performance Dashboard

<p align="center">
  <b>Sales Performance, Product Contribution, Regional Trends & Profitability Analysis in Power BI</b>
</p>

---

## Executive Overview

The **Cookie Sales Performance Dashboard** is an interactive Power BI analytics project designed to evaluate revenue, profitability, product performance, regional contribution, and target achievement for a cookie business.

The report turns sales transactions into a business-facing analytical view that helps answer where revenue is generated, which products contribute most, which regions perform strongly, and how actual sales compare with targets.

### Core Commercial Metrics

- **Total Revenue:** **$4.68M**
- **Total Profit:** **$2.71M**
- **Profit Margin:** **57.94%**
- **Total Orders:** **699**
- **Sales Performance:** **223.9% above target**

---

## Business Problem & Key Findings

The dashboard addresses the following business questions:

1. Which products generate the most revenue?
2. Which regions contribute most strongly to sales?
3. How are revenue and profit changing over time?
4. How does actual sales performance compare with the target?
5. What does the product and customer mix imply for commercial performance?

### Key Findings

- Revenue increased from approximately **$1.1M in 2019** to **$3.6M in 2020**.
- **Chocolate Chip Cookies** generated the highest revenue.
- **White Chocolate Macadamia** ranked second by revenue.
- **Wisconsin** was the highest-performing state in the existing analysis.
- **New York** followed closely behind.
- The observed **57.94% profit margin** indicates strong profitability within the analyzed dataset.

---

## Dashboard Visual Tour

### 1. Dashboard
<p align="center">
  <img src="./Dashboard%20Previews/Dashboard.png" alt="Cookie Sales Performance Dashboard" width="95%">
</p>

---

## Data & Analysis

### Data Sources

The project uses separate Excel datasets for:

- **Cookie Types**
- **Customers**
- **Orders**

All source workbooks are organized in the repository's **Data** folder.

### Analytical Workflow

1. Data preparation with Power Query
2. Data profiling and cleaning
3. Relationship and model design
4. DAX measure development
5. KPI and target analysis
6. Product and regional performance analysis
7. Dashboard storytelling

---

## Data Architecture & Model

The report follows a **Star Schema** design.

### Fact Table

- **Orders Fact**

### Dimension Tables

- **Date Dimension**
- **Product Dimension**
- **Customer Dimension**

### Model Representation

<p align="center">
  <img src="./Dashboard%20Previews/Model.png" alt="Cookie Sales Performance — Power BI Data Model" width="95%">
</p>

---

## Tools & Technologies

- **Business Intelligence:** Microsoft Power BI Desktop
- **Data Transformation:** Power Query
- **Analytics & Calculations:** DAX
- **Data Modeling:** Star Schema
- **Visualization:** Power BI
- **Analysis:** KPI Development, Product Analysis, Regional Analysis, Target Tracking

---

## Files & Structure

```
Dashboard Previews/
├── Dashboard.png
└── Model.png

Data/
├── Cookie Types.xlsx
├── Customers.xlsx
└── Orders.xlsx

README.md
```

---

## How to Use

1. Open the Power BI report.
2. Explore the KPI overview and sales performance.
3. Filter the report to analyze products, customers, and regions.
4. Use the model view to understand the relationships between the fact and dimension tables.

---

## License & Usage

This repository is part of **Kerelos Nakhla's Data Analytics portfolio** and is provided for learning, demonstration, and portfolio purposes.
