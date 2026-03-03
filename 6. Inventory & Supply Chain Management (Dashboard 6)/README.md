# Inventory & Supply Chain Management Dashboard

**Organization:** Amazon (Simulated Enterprise E-Commerce Model)  
**Tool:** Power BI  
**Dataset:** Synthetic Global E-Commerce Dataset – 100,000 Transaction Records  
**Dashboard Focus:** Inventory Management, Supply Chain Efficiency, Fulfilment Cost Analysis, Delivery Performance, and Return Monitoring  
**Date:** 26 – 28 February 2026  
**Created by:** Soham S. Amburle

---

## Overview

The **Inventory & Supply Chain Management Dashboard** provides an executive and operational view of inventory movement, fulfilment efficiency, delivery reliability, and cost management within a global e-commerce business model inspired by Amazon. Built using a synthetic dataset of 100,000 transaction-level records, this dashboard focuses on monitoring inventory trends, product category distribution, delivery performance across countries, fulfilment cost allocation, and order status distribution.

The primary objective of this dashboard is to help executive leadership, supply chain managers, and operations teams answer strategic questions:

- What is the total order volume and quantity sold over time?  
- How efficient are fulfilment operations and what is the cost per order?  
- Which product categories incur higher fulfilment costs?  
- What are the delivery performance trends across countries?  
- What is the trend of returns and reverse logistics issues?  
- How does operational performance vary by product, region, or sales channel?

By combining executive KPI monitoring, trend analysis, cost distribution, and interactive filtering, the dashboard delivers a comprehensive and executive-ready operational view.

---

## Business Storyline & Analytical Flow

### 1. Executive Supply Chain Snapshot – KPI Cards

Seven KPI cards provide a high-level summary of operational performance:

- **Total Orders**  
- **Total Quantity Sold**  
- **Total Fulfilment Cost**  
- **Fulfilment Cost per Order**  
- **Average Delivery Time (Days)**  
- **On-Time Delivery %**  
- **Return Rate %**

These KPIs establish immediate visibility into order scale, inventory efficiency, cost control, and delivery reliability.

---

### 2. Interactive Filtering Controls – Slicers

All visuals dynamically respond to the following slicers:

- **DATE (Month)**  
- **DATE (Year)**  
- **Product Category**  
- **Sub-Category**  
- **Brand**  
- **Customer Country**  
- **Sales Channel (Web / Mobile App)**  
- **Order Status**

These slicers allow multi-dimensional operational analysis across geography, product, channel, and time.

---

### 3. Inventory Movement Trend – Line Chart

- **X-Axis:** Order_Date (Month)  
- **Y-Axis:** Total Quantity Sold  
- **Unit:** Units

Shows inventory movement trends and operational demand patterns over time.

---

### 4. Inventory Movement by Product Category – Clustered Column Chart

- **X-Axis:** Product_Category  
- **Y-Axis:** Total Quantity Sold  
- **Unit:** Units  
- **Optional Legend:** Sub-Category

Highlights product category movement volumes.

---

### 5. Delivery Performance by Country – Clustered Bar Chart

- **X-Axis:** Avg Delivery Time (Days)  
- **Y-Axis:** Customer_Country  
- **Color:** On-Time Delivery %  
- **Unit:** Days / %  

Identifies regional delivery performance disparities.

---

### 6. Fulfilment Cost Distribution by Product Category – Tree Map

- **Group:** Product_Category  
- **Values:** Total Fulfilment Cost  
- **Unit:** Currency ($, display units in Millions)  

Highlights cost concentration across product categories.

---

### 7. Order Status Distribution – Pie Chart

- **Values:** Count of Orders  
- **Legend:** Order_Status  
- **Unit:** Count of Orders  

Provides visibility into delivered, returned, and cancelled orders.

---

## Key Takeaways

This dashboard enables stakeholders to:

- Monitor inventory and supply chain KPIs in a consolidated executive view  
- Compare product categories and regional performance  
- Identify high-cost categories and delivery bottlenecks  
- Track returns and operational efficiency over time  
- Support data-driven supply chain, inventory, and fulfilment decisions

By integrating KPI cards, slicers, trend analytics, and category/geographic-level visuals, the dashboard delivers a professional, enterprise-grade operational intelligence solution.

---

## Tools & Data

- **Visualization Tool:** Power BI  
- **Dataset:** Fully synthetic global e-commerce dataset  
- **Record Count:** 100,000 transaction-level records  
- **Time Period:** 2021–2024  
- **Model Design:** Star Schema (Fact_Orders with Dimension Tables for Date, Customer, Product, and Channel)  
- **Purpose:** Inventory & supply chain analytics demonstration and enterprise BI portfolio development

---

> **Note:** This project is not affiliated with Amazon. All data used in this dashboard is synthetic and created solely for learning, analysis, and portfolio demonstration purposes.

---

**Dashboard and Documentation by Soham S. Amburle**  
**26 – 28 February 2026**
