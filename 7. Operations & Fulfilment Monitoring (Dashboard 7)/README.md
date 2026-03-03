# Operations & Fulfilment Monitoring Dashboard

**Organization:** Amazon (Simulated Enterprise E-Commerce Model)  
**Tool:** Power BI  
**Dataset:** Synthetic Global E-Commerce Dataset – 100,000 Transaction Records  
**Dashboard Focus:** Operational Efficiency, Fulfilment Performance, Delivery Tracking, Cost Monitoring, and Regional Analysis  
**Date:** 01 March 2026  
**Created by:** Soham S. Amburle  

---

## Overview

The **Operations & Fulfilment Monitoring Dashboard** provides an executive and operational view of logistics and fulfilment performance within a global e-commerce business model inspired by Amazon. Built using a synthetic dataset of 100,000 transaction-level records, this dashboard focuses on monitoring order volume, delivery performance, return and cancellation rates, fulfilment cost efficiency, and regional operational effectiveness.

The primary objective of this dashboard is to help executive leadership, operations managers, and supply chain teams answer key strategic questions:

- What is the total order volume and throughput over time?  
- How efficient are delivery operations and are orders delivered on time?  
- Which regions incur higher fulfilment costs?  
- What are the trends in returns and cancellations?  
- How does operational performance vary by customer segment, product category, or sales channel?  

By combining executive KPI monitoring, trend analysis, geographic mapping, interactive filtering, and narrative storytelling, the dashboard delivers a comprehensive and executive-ready operational view.

---

## Business Storyline & Analytical Flow

### 1. Executive Operations Snapshot – KPI Cards

Seven KPI cards provide a high-level summary of operational performance:

- **Total Orders**  
- **Total Fulfilment Cost**  
- **Fulfilment Cost per Order**  
- **Average Delivery Time (Days)**  
- **On-Time Delivery %**  
- **Return Rate %**  
- **Cancellation Rate %**

These KPIs establish immediate visibility into order scale, operational efficiency, cost effectiveness, and delivery performance.

---

### 2. Interactive Filtering Controls – Slicers

All visuals dynamically respond to the following slicers:

- **Order Date**  
- **Year**  
- **Month Name**  
- **Customer Segment (Prime / Non-Prime)**  
- **Customer Country**  
- **Product Category**  
- **Brand**  
- **Sales Channel (Web / Mobile App)**  
- **Marketing Channel (Google / Meta / Email / Organic)**  
- **Order Status**  

These controls allow dynamic operational analysis across geography, customer segment, product, channel, and time.

---

### 3. Delivery Time Trend – Line Chart

- **X-Axis:** Month Name  
- **Y-Axis:** Average Delivery Time (Days)  

This visual highlights operational efficiency trends and delivery bottlenecks over time.

---

### 4. Order Volume Trend – Area Chart

- **X-Axis:** Month Name  
- **Y-Axis:** Total Orders  

Illustrates seasonal peaks, order throughput, and capacity planning requirements.

---

### 5. On-Time Delivery Performance by Region – Clustered Bar Chart

- **Axis:** Customer Country  
- **Values:** On-Time Delivery %  
- **Optional Legend:** Customer State  

This visual identifies regional performance disparities, allowing targeted operational improvements.

---

### 6. Fulfilment Cost by Region – Map Visualization

- **Location:** Customer Country  
- **Size / Color Saturation:** Total Fulfilment Cost  
- **Tooltip:** Country/State + Fulfilment Cost  

Supports logistics cost optimization and regional resource allocation decisions.

---

### 7. Narrative — Operational Insights – Text / Narrative Visual

Provides a concise executive summary of:

- Total orders and throughput trends  
- Average delivery time and on-time delivery  
- Fulfilment cost distribution  
- Returns and cancellations trends  

This visual communicates actionable operational insights in plain language.

---

## Key Takeaways

This dashboard enables stakeholders to:

- Monitor operational and fulfilment KPIs in a consolidated executive view  
- Compare regional efficiency and cost distribution  
- Identify bottlenecks and inefficiencies in delivery and fulfilment processes  
- Track return and cancellation trends  
- Support data-driven supply chain and operational decision-making  

By integrating KPI cards, slicers, trend analytics, geographic mapping, and narrative storytelling, the dashboard delivers a professional, enterprise-grade operational intelligence solution.

---

## Tools & Data

- **Visualization Tool:** Power BI  
- **Dataset:** Fully synthetic global e-commerce dataset  
- **Record Count:** 100,000 transaction-level records  
- **Time Period:** 2021–2024  
- **Model Design:** Star Schema (Fact_Orders with Dimension Tables for Date, Customer, Product, and Channel)  
- **Purpose:** Operations & fulfilment analytics demonstration and enterprise BI portfolio development  

---

> **Note:** This project is not affiliated with Amazon. All data used in this dashboard is synthetic and created solely for learning, analysis, and portfolio demonstration purposes.

---

**Dashboard and Documentation by SOHAM S. AMBURLE**  
**01 March 2026**
