<img width="764" height="408" alt="image" src="https://github.com/user-attachments/assets/8b012652-e251-45c5-8339-b446072dbc44" />

## Project Background ##
A global grocery retail client requires a direct comparative analysis to measure the growth, volume trends, and operational efficiency between the current fiscal period and the prior year. The primary goal is to determine the effectiveness of sales strategies by quantifying the Year-over-Year (YoY) variance across all critical performance indicators.

This project delivers a focused Excel dashboard that highlights revenue drivers, pricing stability, and regional market performance between the two fiscal periods.

Insights and recommendations are provided on the following key areas:

* **YoY Growth and Volume**: Quantifying the percentage change in Revenue ($105M, +16.12% vs PY), Quantity Sold (6.0M, +16.12% vs PY), and Avg. Unit Price ($17.6, -0.01% vs PY) versus the prior year.

* **Monthly Volatility**: Detailed tracking of the Monthly Sales Trend to pinpoint exactly when demand fluctuations occurred throughout the fiscal year.

* **Regional Performance**: Benchmarking sales performance across different international markets (Germany, Poland, Lithuania, India, Bangladesh).

* **Product Packaging Shifts**: Identifying which specific unit categories (Ct, Cans, Bottles) are contributing the most to the volume changes.

### Technical Deliverables
* **Interactive Dashboard**: The full Grocery Business Insights dashboard can be accessed [here](https://drive.google.com/drive/folders/1jZGXgdYFYSnEV24nSzLoA4lfQoY6MoTg)

* **Time Intelligence Focus**: The project features Advanced Excel Functions and Pivot Table calculations to derive complex Year-over-Year (YoY) variances and dynamic trend comparisons without the use of external BI tools.

## Data Structure & Initial Checks

### Data Overview

The analysis was built entirely within a **single Excel workbook**, using a standard Excel Data Table as the source for all PivotTables and calculations. No data was loaded into the Power Pivot Data Model — all work was completed using native **Excel functionality** to demonstrate core spreadsheet competency.

<img width="1365" height="699" alt="image" src="https://github.com/user-attachments/assets/b750bce9-2174-4104-97f3-0bfce3b6357c" />

### Data Cleaning and Preparation 
The data cleaning and preparation process utilized native Excel tools, Pivot Tables, and Standard Excel Formulas to derive the core dashboard insights.

* **Data Quality**: The raw transactional data was audited for duplicates and missing values before being converted into a structured Excel Table.

* **Field Engineering**: Helper columns were created using text and date functions to standardize geographical names and extract fiscal periods (Year/Month) for the timeline slicers.

* **Aggregation**: Pivot Tables were used exclusively to aggregate the 6 million quantity units and $105M revenue figures across various dimensions.
* **Time Intelligence (Calculated Measures)**:All core KPIs, including 16.12% VS PY Revenue, 16.12% VS PY Quantity, and -0.01% VS PY Avg Unit Price, were derived using Calculated Fields and formula-based helper tables within the Excel workbook. This approach allowed for dynamic period comparisons without relying on the Power Pivot Data Model.
  <img width="1362" height="714" alt="image" src="https://github.com/user-attachments/assets/8206c070-4c0d-495a-841e-daac1c01eb0b" />
### Executive Summary (Grocery Business Performance)

The business is delivering consistent, volume-driven expansion, with **Revenue up 16.12%** and **Quantity up 16.12%** versus the prior year (PY). **Total Revenue reached $105M** while **total volume hit 6.0M units**. Unlike scenarios where growth is driven by inflation or price hikes, this performance is organic; the Avg. Unit Price remained **flat (-0.01% vs PY) at $17.6**. This indicates that the revenue surge is solely the result of increased consumer demand and successful market penetration in key regions like **Germany and India**, rather than pricing adjustments.

### YOY Growth and Financial Efficiency

* **Strong Revenue Growth**: Revenue is **up 16.12% ($105M)** versus the prior year, driven directly by increased demand.

* **Volume Expansion**: Quantity sold matches the revenue trend, also **up 16.12% (6.0M units)**, confirming a healthy volume-based expansion.

* **Price Stability**: The Average Unit Price **($17.6)** remained virtually flat at **-0.01% VS PY**, indicating that growth was achieved without inflationary price hikes.

* **Customer Consistency**: The total customer base (9.2K) remained stable at **0.00% VS PY**, suggesting retention of existing clients rather than new customer acquisition.
  
  <img width="759" height="311" alt="image" src="https://github.com/user-attachments/assets/6b6a3417-b3d9-4ea9-bd69-c6d020fb9cce" />


### Regional Sales Distribution

* **Global Market Reliance**: **Germany** is the standout primary driver of sales volume, followed closely by **Poland and Lithuania**, confirming that the European market currently contains the most optimized sales channels and strongest consumer demand.

* **Developing Markets**: **India and Bangladesh** are contributing significantly lower volumes compared to their European counterparts, indicating a potential need for strategic intervention and resource allocation to capture the full market potential of these high-population regions.

<img width="330" height="402" alt="image" src="https://github.com/user-attachments/assets/2bdd3a5e-e05c-4209-8672-a9603400afb6" />

### Product-Wise Breakdown

* **Growth Drivers**: The **Ct (Cartons/Count) and Cans** packaging units represent the highest volume contributors **(over 2M+ and 1M+ units respectively)**, confirming they are the most effective packaging formats for driving the current year's quantity surge.

* **Lower Volume Categories**: Packaging units like **Bags and Oz** show significantly lower volume compared to the leaders, suggesting the need for revised marketing or bundling strategies to lift these formats to the level of the top performers.

  <img width="512" height="261" alt="image" src="https://github.com/user-attachments/assets/3f55239a-0537-41d9-926d-aa8715a96d3c" />

  ### Business Recommendations
Based on the analysis of high YOY volume growth, stagnant pricing power, and sharp regional disparities, the following five strategic actions are critical to sustaining profitable growth:

* **Review Pricing Strategy (-0.01% VS PY)**: While volume has surged, the Avg. Unit Price has remained flat at **$17.6**. Identify opportunities to implement marginal price increases on high-demand units to boost revenue without sacrificing the strong **16.12%** Quantity growth.

* **Replicate European Success Model**: Analyze the operational and sales strategies of the top-performing **Germany and Poland** markets and mandate their adoption in the underperforming **India and Bangladesh** regions to balance the global sales distribution.

* **Prioritize High-Volume Packaging**: Focus inventory stocking, logistics, and production capacity on the **"Ct" (Carton) and "Cans"** packaging units to maximize returns from the most effective product lines currently driving **50%+** of total volume.

* **Relaunch Low-Volume Formats**: Develop targeted promotional strategies or bundle deals for **"Bags" and "Oz"** packaging units to boost their YOY sales performance and prevent them from becoming dead stock.

* **Optimize Inventory Against Monthly Volatility**: Use the Monthly Sales Trend to refine procurement timing, ensuring that inventory is fully stocked ahead of historical peak months and scaled back during known trough periods.

---
Thank you for reading! Leave a comment if you have any questions about the analysis.
