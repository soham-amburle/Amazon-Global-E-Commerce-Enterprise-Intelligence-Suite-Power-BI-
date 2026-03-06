# Amazon | Global E-Commerce Enterprise Intelligence Suite (Power BI)
 
## Project Overview
This project simulates an **enterprise-grade Business Intelligence solution** for a global e-commerce leader like Amazon, built using **Power BI** and a large-scale **synthetic retail dataset**.

The objective is to demonstrate how executive leadership, commercial teams, marketing departments, supply chain operations, and finance teams can use data-driven dashboards to monitor **sales performance, customer growth, marketing ROI, inventory efficiency, operational excellence, and profitability**.

The solution is designed as a **9-dashboard executive analytics suite**, similar to real-world BI platforms used in global e-commerce organizations.

---

## Dashboard Suite Structure

1. Executive Overview  
2. Sales Performance Analytics  
3. Customer Intelligence & Segmentation  
4. Marketing & Acquisition Performance  
5. Product Performance Analytics  
6. Inventory & Supply Chain Management  
7. Operations & Fulfilment Monitoring  
8. Financial & Profitability Analysis  
9. Forecasting & Scenario Modelling  

---

## Key Business Areas Covered
- Executive KPI monitoring & strategic performance  
- Revenue growth & channel analysis  
- Customer lifetime value and churn analytics  
- Marketing ROI and acquisition cost analysis  
- SKU-level product performance  
- Inventory turnover & stockout risk  
- Logistics and fulfilment efficiency  
- Margin & contribution analysis  
- Demand forecasting & what-if modelling  

---

## Dataset

- **File:** `amazon_ecommerce_synthetic_dataset.csv`  
- **Records:** 100,000 (1 lakh synthetic records)  
- **Grain:** Order–Product–Customer (transaction-level)  
- **Time Period:** 2021–2024  

The dataset is fully synthetic and does **not** contain any real Amazon data. It is intended strictly for **analytics, visualization, and portfolio demonstration purposes**.

---

## Dataset Columns (25 Total)

### Order & Transaction Information
1. Order_ID  
2. Order_Date  
3. Ship_Date  
4. Delivery_Date  
5. Order_Status  
6. Sales_Channel (Web / Mobile App)  
7. Payment_Method  

### Customer Information
8. Customer_ID  
9. Customer_Segment (Prime / Non-Prime)  
10. Customer_City  
11. Customer_State  
12. Customer_Country  

### Product Information
13. Product_ID  
14. Product_Name  
15. Product_Category  
16. Sub_Category  
17. Brand  

### Sales & Financial Metrics
18. Quantity  
19. Unit_Price  
20. Discount_Percentage  
21. Revenue  
22. Cost_of_Goods_Sold (COGS)  
23. Gross_Profit  

### Marketing & Operations Metrics
24. Marketing_Channel (Google / Meta / Email / Organic)  
25. Fulfilment_Cost  

---

## Data Model Design
- Star schema architecture  
- Fact table: Orders  
- Dimension tables: Customers, Products, Date, Region, Channel  
- Advanced DAX measures for KPI calculations  
- Drill-through & cross-filtering enabled  

---

## Tools & Technologies
- Power BI Desktop  
- DAX (KPIs, time intelligence, what-if parameters)  
- Data modelling (star schema design)  
- Synthetic data generation (Python)  

---

## Project Goals
- Demonstrate enterprise-level BI solution architecture  
- Showcase commercial and operational analytics expertise  
- Build executive-ready dashboards aligned with C-suite decision-making  
- Implement advanced Power BI features (forecasting, scenario analysis, drill-through)  

---

## Disclaimer
This project is **not affiliated with Amazon**.  
All data is synthetic and created solely for educational and portfolio use.
