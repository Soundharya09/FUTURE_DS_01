# Superstore Analytics Dashboard - Power BI Project
## Description
The Superstore Analytics Dashboard is a comprehensive data visualization and business intelligence project developed using Microsoft Power BI and Excel. This project is part of a 
real-world internship-style task that focuses on analyzing e-commerce sales data to uncover meaningful insights for business decision-making. The project involves cleaning raw data, performing exploratory analysis, and creating interactive dashboards that visualize trends across sales, customers, products, and regions.

The ultimate goal is to help business leaders answer key strategic questions like:

Q1. What are the top-performing products and most profitable categories?.
Q2. When do sales peak throughout the year?.
Q3. Which regions or states generate the most revenue?.

## Objective
The project is designed to:
- Analyze e-commerce sales and profit trends across different time periods.
- Identify the best and worst-performing products, regions, and customers.
- Understand customer purchase behavior and shipping preferences.
- Build an interactive, dynamic dashboard that provides actionable insights.
- Communicate results effectively using visuals and data storytelling.

## Dataset Overview
The dataset (superstore.xls) contains detailed information about orders, products, customers, and geographical regions.
It includes:
- Order ID, Order Date, Ship Date, Ship Mode
- Customer ID, Customer Name, Segment
- Product ID, Category, Sub-Category, Product Name
- Sales, Quantity, Discount, Profit
- Region, State, City, Postal Code
The data was cleaned, standardized, and modeled using Power Query and DAX within Power BI to support multi-dimensional analysis.

## Dashboard Overview
The Power BI report comprises three interactive dashboards, each focusing on a distinct aspect of the business's analytics.
1. Overview Dashboard
Purpose:
To provide a high-level summary of business performance — total sales, profit, quantity sold, and customer base.

Key Visuals and Insights:
- KPI Cards: Show total sales ($2.30M), total profit ($0.29M), quantity (37.87K), and total customers (793).
- Sales & Profit Trends: Visualizes changes over time to identify performance trends and seasonality.
- Top 5 States by Sales: California and New York lead, followed by Texas and Washington.
- Top 10 Best-Selling Products: Canon imageCLASS 2200 Advanced Copier ranks #1 in sales ($62K).

Regional Analysis:
- West region drives ~30% of total sales.
- West also leads in profitability, followed by Central.

2. Sales Dashboard
Purpose:
To perform a deeper analysis of sales and profit across time, categories, sub-categories, and regions.

Key Visuals and Insights:
- Yearly Sales & Profit Comparison: Tracks annual growth and fluctuations from 2011 to 2014.
- Monthly Trend Analysis: Identifies peak sales periods.
- Category & Subcategory Breakdown:
     - Technology and Office Supplies dominate in total sales.
     - Furniture shows higher variance in profit margins.
- Regional & State-level Sales: Highlights key markets and underperforming areas.
- Profitability by Category: Offers insight into product lines that yield the highest margins.

Business Insight:
While sales volume is high for Office Supplies, *Technology products* offer better profitability, suggesting an opportunity to promote tech-based upselling.

3. Product and Customer Dashboard
Purpose:
To explore detailed product-level and customer-level analytics, identifying who buys what and where profitability comes from.

Key Visuals and Insights:
- KPIs: 1,862 products, 296 returned orders, 531 cities, and 49 states.
- Top 5 Customers by Quantity: Jonathan, William, John, and Paul lead with the most orders.
- Top 5 Products by Profit: Canon imageCLASS 2200 tops with $25.2K profit.
- Bottom 5 Products by Loss: Bush Cubix and Cubify CubeX show consistent negative returns.
- Customer Distribution by Segment:
      - Consumer (51.94%)
      - Corporate (30.22%)
      - Home Office (17.84%)
  
- Ship Mode & Category Distribution:
      - Most customers choose Standard Class (59.72%) shipping.
      - Office Supplies make up 60% of total sales volume.
  
- Customer Distribution by Region:
      - West (32.05%) leads in customer base.

## Analytical Process
1. Data Cleaning:
- Removed missing and duplicate entries.
- Validated numerical and date fields.
- Renamed inconsistent categories.

2. Data Modeling:
- Established relationships between tables (Orders, Customers, Products, Regions).
- Created DAX measures for Total Sales, Profit, Quantity, and Profit Margin.

3. Visualization & Interactivity:
- Used slicers for Year, Region, Category, and Sub-Category.
- Incorporated bar charts, donut charts, and line graphs.
- Designed KPIs for quick performance tracking.

4. Insight Generation:
- Interpreted key visual trends to develop actionable recommendations.

## Outcome
The project successfully delivers an interactive analytical solution that enables stakeholders to:
- Monitor real-time KPIs on sales, profit, and customer metrics.
- Analyze performance by region, product category, and time period.
- Identify actionable opportunities for sales growth and cost optimization.
The dashboard bridges the gap between raw data and business intelligence, showcasing a complete analytics workflow from data acquisition to visualization.
