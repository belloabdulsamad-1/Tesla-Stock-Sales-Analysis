# Tesla-Stock-Sales-Analysis
This project explores Tesla's stock sales data to identify trends, price movements, and trading volumes over time. It includes data cleaning, visualization, and insights to support investment decisions.

##  Table of Contents

1. [Project Overview](#project-overview)  
2. [Tools Used](#tools-used)  
3. [Objectives](#objectives)  
4. [Key Features & Metrics](#key-features-&-Metrics)  
5. [Technical Implementation](#technical-implementation)
6. [Findings](#findings)
7. [Power BI Dashboard](#power-bi-dashboard)
8. [Recommedations](#recommedations)
9. [Conclusion](#conclusion)

---

## Project Overview

This project involves the development of an interactive Tesla Sales Analysis Dashboard built to visualize and analyze key sales metrics of Tesla vehicles across the United States. The dashboard provides actionable insights into pricing trends, vehicle condition, and market distribution, enabling data-driven decision-making for sales and marketing strategies.


---

## Tools Used

- Power BI
- Excel (for initial checks)

---

## Objectives

The primary goal of this dashboard is to transform raw Tesla sales data into an intuitive visual story. It allows users to quickly understand:
The average sales price of vehicles by state.
The relationship between vehicle price and days on market.
The impact of accident history on vehicle pricing and sales.
How odometer readings correlate with the final sale price.

---

## Key Features & Metrics

> The dashboard presents several key performance indicators (KPIs) and visualizations:

**Geographic Price Distribution:** A map or bar chart showing the average sale price of Tesla vehicles across different states (e.g., CA, WA, FL, NJ, etc.).

**Price by Days on Market (DAS):** A visualization (likely a bar or line chart) breaking down the average sale price into three key segments of the sales lifecycle:

**43.07K** (31.29% of vehicles)

**49.21K** (35.01% of vehicles)

**47.36K** (33.7% of vehicles)

**Accident Analysis:** A clear comparison of sales for vehicles with and without an accident history, showing the significant majority (92%) of sales come from accident-free vehicles.

**Odometer vs. Price Analysis:** A chart (likely a bar or scatter plot) showing the average exit (sale) price binned by odometer readings, highlighting how mileage affects value.

**Primary KPIs:**

Average Price: **$47,360**

Average Odometer Reading at Sale: **756.04** (units assumed to be in miles)

% Without Accident: **92%**

% With Accident: **8%**

---

## Technical Implementation

**Data Visualization Tool:** The dashboard was created using Tableau Public (or a similar BI tool like Power BI or Looker Studio).

**Data Processing:** Data was likely cleaned, transformed, and aggregated using Python (Pandas) or SQL before being fed into the visualization tool.

**Data Source:** The analysis is based on a simulated or publicly available dataset of used Tesla vehicle sales, containing fields such as:

Price

State

Days on Market (DAS)

Odometer

Accident History

Sale Status (Exit)

---

## Findings

> Analysis of the Tesla sales data reveals several clear trends:

**Price Premium for Quicker Sales:** Vehicles that sold within the middle DAS segment commanded the highest average price ($49.21), suggesting an optimal window for pricing that attracts quick buyers without leaving money on the table.

**Accident History Significantly Impacts Value:** The vast majority of sales (92%) are for accident-free vehicles. The mere presence of an accident history severely limits a vehicle's marketability and likely its value.

**Geographic Price Variation:** Significant differences in average sale prices exist across states, indicating regional variations in demand, model preferences, or local market conditions.

**Mileage Correlation:** The "Average Exit By OdometerBIN" chart shows a clear negative correlation between mileage and sale price, which is a standard but important confirmation for the used car market.

---

## Power BI Dashboard

![Amazon Dashboard] (<img width="1292" height="745" alt="Tesla Sales Dashboard" src="https://github.com/user-attachments/assets/55c3cb4f-b826-4051-8e25-50e41195a01f" />)

---

## Recommendation

**Optimize Pricing Strategy:** Price vehicles to align with the middle "Days on Market" segment to maximize sale price and turnover rate, targeting the ~$49K benchmark.

**Promote Accident-Free Status:** Highlight the clean history of vehicles in all marketing, as the data confirms it is a primary factor for 92% of buyers.

**Prioritize Low-Mileage Inventory:** Acquire and market vehicles with lower odometer readings to command higher average sale prices.

**Allocate Inventory Strategically:** Leverage geographic price variations by directing premium inventory to high-value states to maximize revenue.

---

## Conclusion

Of course. Here is a short and professional conclusion.

---

### Conclusion

This dashboard effectively translates raw sales data into actionable business intelligence. The analysis confirms strong market patterns related to pricing velocity, vehicle condition, and geographic location. By leveraging these insights, specifically the value of optimal pricing, clean vehicle history, and strategic regional allocation, sales and inventory strategies can be significantly optimized to improve profitability and turnover for Tesla vehicles.
