# Adidas US Sales — Power BI Dashboard Project

> **Role:** Aspiring Associate Data Analyst
> **Dataset:** Adidas US Sales Dataset — Kaggle (2020–2021)
> **Tools:** Power BI Desktop, DAX, Power Query
> **Focus:** Sales Performance · Regional Analysis · Retailer ROI · Product Profitability

---

## Project Overview

This project analyzes Adidas US sales data across 2020–2021 using Microsoft Power BI. The goal was to build an executive-ready dashboard that helps sales and marketing teams quickly understand where revenue is coming from, which products and regions are underperforming, and how different retail channels compare in profitability.

The analysis covers 9,648 transactions across 5 US regions, 6 product categories, 5 major retailers, and 3 sales methods — in-store, online, and outlet.

---

## Dataset Schema

| Column | Description |
|--------|-------------|
| Retailer | Foot Locker, Walmart, Sports Direct, West Gear, Amazon |
| Invoice Date | Transaction date Jan 2020 to Dec 2021 |
| Region | West, Northeast, Southeast, South, Midwest |
| State and City | US state and city of sale |
| Product | Men's and Women's Footwear and Apparel categories |
| Price per Unit | Sale price per item |
| Units Sold | Quantity sold per transaction |
| Total Sales | Revenue per transaction |
| Operating Profit | Profit after operating costs |
| Operating Margin | Profit as percentage of revenue |
| Sales Method | In-store, Online, Outlet |

---

## Business Questions Answered

| # | Question | Key Finding |
|---|----------|-------------|
| 1 | Which months drove peak revenue? | July 2021 peaked at $29M — summer footwear demand |
| 2 | Which product line is most profitable? | Men's Street Footwear = highest revenue at $82M |
| 3 | Which region leads in sales volume? | West region = 30% of total US revenue |
| 4 | Which retailer has the best margin? | West Gear outperforms on margin; Walmart leads volume |
| 5 | Is online or in-store more profitable? | Online sales average 12% higher operating margin |
| 6 | Which states are underperforming? | Several Southeast states show 40% below regional average |
| 7 | What is the YoY growth trend? | 2021 grew 43% over 2020 across all categories |

---

## Key Business Insights and Recommendations

### 1. Shift budget toward online channel
Online sales deliver 12% higher margins than in-store. Adidas should increase digital marketing spend and reduce dependence on low-margin outlet sales.

### 2. Women's apparel is underinvested
Women's Apparel has the best operating margin of all product lines but the lowest units sold. A targeted campaign could unlock significant profit growth.

### 3. Southeast region needs attention
Despite being the 3rd largest region by population, the Southeast consistently underperforms vs regional averages. A localized pricing or retailer strategy is needed.

### 4. West Gear is the star retail partner
West Gear delivers the best margin efficiency across all retailers. Deepening this partnership and replicating its model in underperforming regions should be a priority.

### 5. Q3 is the critical sales window
July through September drives disproportionate revenue across all categories. Inventory and campaign planning must be front-loaded for Q2 to capture this peak.

---

## Dashboard Pages

Page 1 — Executive Summary
KPI cards, monthly sales trend 2020 vs 2021, sales method breakdown, top products by revenue

Page 2 — Regional Deep Dive
US map by state, revenue by region bar chart, state-level table with conditional formatting

Page 3 — Product Analysis
Product by region matrix, revenue vs margin scatter plot, units sold breakdown

Page 4 — Retailer Performance
Retailer ranking, sales method mix per retailer, profit efficiency comparison

---

## Skills Demonstrated

- DAX — time intelligence, RANKX, CALCULATE, DIVIDE, SWITCH
- Power Query — data cleaning, type formatting, duplicate removal
- Data Modeling — date table creation, table relationships
- Dashboard Design — 4 page executive report structure
- Business Thinking — translating sales data into strategic recommendations

---

## How to Reproduce

1. Download the dataset from Kaggle: kaggle.com/datasets/heemalichaudhari/adidas-sales-dataset
2. Open Power BI Desktop
3. Load the CSV via Get Data then Text/CSV
4. In Power Query: set Invoice Date as Date type, Operating Margin as Percentage
5. Create a Date Table using the DAX measures file in this repo
6. Copy DAX measures from adidas_dax_measures.txt into your model
7. Build visuals following the page structure described above

---

## Dataset Source

Adidas US Sales Dataset — available on Kaggle
kaggle.com/datasets/heemalichaudhari/adidas-sales-dataset

This project is for portfolio purposes using a publicly available dataset.
