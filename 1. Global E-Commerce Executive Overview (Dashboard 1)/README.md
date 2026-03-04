# Global E-Commerce Executive Overview

**Organization:** Amazon (Simulated Enterprise E-Commerce Model)  
**Tool:** Power BI  
**Dataset:** Synthetic Global E-Commerce Dataset – 100,000 Transaction Records  
**Dashboard Focus:** Executive-Level Performance Snapshot across Sales, Customers, Marketing, Products, Inventory, Operations, Financials, and Forecasting  
**Date:** 05 March 2026  
**Created by:** Soham S. Amburle  

---

## Overview

The **Global E-Commerce Executive Overview Dashboard** delivers a strategic top-level view of a global e-commerce business model inspired by Amazon. Built using a synthetic dataset of 100,000 transaction-level records, this dashboard enables executive leadership to quickly assess **overall business health, operational efficiency, revenue performance, customer growth, marketing impact, product and category performance, and fulfilment costs**.

The dashboard serves as a hub, providing **high-level KPIs, strategic visualizations, interactive slicers, operational gauges, and navigation buttons** to drill down into detailed dashboards across sales, customer intelligence, marketing, products, inventory, operations, financials, and forecasting.

This dashboard answers key executive-level questions:

- What is the overall revenue trajectory?  
- How profitable is the business across categories and channels?  
- Which regions, customer segments, and channels are performing best?  
- What is the status of fulfilment efficiency and order health?  
- Are revenue and customer growth aligned with strategic targets?  

Through KPI monitoring, big-picture charts, slicers, gauges, donut charts, and page navigation buttons, this dashboard provides an **actionable, executive-ready top-level view**.

---

## Business Storyline & Analytical Flow

### 1. Executive KPI Snapshot – KPI Cards

Eight KPI cards provide an immediate executive-level summary:

- **Total Revenue**  
- **Total Gross Profit**  
- **Gross Margin %**  
- **Total Orders**  
- **Total Quantity Sold**  
- **Average Order Value (AOV)**  
- **Fulfilment Cost**  
- **Prime Customer %**  

These KPIs deliver a **quick business health check** for decision-makers.

---

### 2. Big Strategic Visuals

Six key visuals provide a top-level perspective:

1. **REVENUE TREND OVER TIME** – Line Chart (Unit: $M)  
2. **REVENUE BY PRODUCT CATEGORY** – Clustered Column Chart (Unit: $M)  
3. **REVENUE BY REGION** – Filled Map or Clustered Bar Chart (Unit: $M)  
4. **SALES CHANNEL PERFORMANCE** – Clustered Column Chart (Unit: $M)  
5. **CUSTOMER GROWTH TREND** – Area Chart (Unit: K Customers)  
6. **CATEGORY PROFITABILITY ANALYSIS** – Scatter Chart (X: Revenue $M, Y: Gross Margin %, Size: Quantity K)  

---

### 3. Executive Slicers

Six interactive slicers allow high-level filtering:

- Year (`Dim_Date[Year]`)  
- Product Category (`Dim_Product[Product_Category]`)  
- Customer Segment (`Dim_Customer[Customer_Segment]`)  
- Sales Channel (`Fact_Orders[Sales_Channel]`)  
- Marketing Channel (`Fact_Orders[Marketing_Channel]`)  
- Country (`Dim_Customer[Customer_Country]`)  

---

### 4. Gauge

- **REVENUE VS TARGET** – Highlights current revenue against strategic target (Unit: $M)  

---

### 5. Donut Chart

- **ORDER STATUS DISTRIBUTION** – Shows Delivered, Shipped, Cancelled, Returned (%)  

---

### 6. Page Navigation Buttons

Eight buttons link to detailed dashboards:

- SALES PERFORMANCE ➡️  
- CUSTOMER INSIGHTS ➡️  
- MARKETING PERFORMANCE ➡️  
- PRODUCT PERFORMANCE ➡️  
- INVENTORY & SUPPLY ➡️  
- OPERATIONS OVERVIEW ➡️  
- FINANCIAL PERFORMANCE ➡️  
- FORECAST & SCENARIOS ➡️  

---

## Key Takeaways

This dashboard enables executives to:

- Monitor revenue and profitability trends  
- Assess customer growth and segment performance  
- Evaluate marketing and sales channel impact  
- Track product and category profitability  
- Review operational efficiency and order health  
- Quickly navigate to deeper analytics dashboards  

---

## Tools & Data

- **Visualization Tool:** Power BI  
- **Dataset:** Fully synthetic global e-commerce dataset  
- **Record Count:** 100,000 transaction-level records  
- **Time Period:** 2021–2024  
- **Model Design:** Star Schema (Fact_Orders with Dimension Tables for Date, Customer, Product, and Channel)  
- **Purpose:** Top-level executive dashboard for portfolio demonstration  

---

> **Note:** This project is not affiliated with Amazon. All data used in this dashboard is synthetic and created solely for learning, analysis, and portfolio demonstration purposes.

---

**Dashboard and Documentation by SOHAM S. AMBURLE**  
**05 March 2026**
