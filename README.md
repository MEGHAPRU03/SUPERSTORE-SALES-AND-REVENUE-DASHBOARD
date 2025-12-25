# SUPERSTORE-SALES-AND-REVENUE-DASHBOARD
I built an interactive Superstore Sales Dashboard using Excel to analyze sales performance, profitability, customer behavior, and delivery efficiency.
The dashboard is designed for business & Sales managers and to other decision-makers to quickly track KPIs, identify profit drivers and spot potential risk areas.

**Data Preparation & Modeling**

Data was cleaned and transformed using Excel Power Query with the following steps:
1)Removed blank and invalid records (missing Order ID, Sales)
2)Handled duplicates carefully using Order ID + Product ID
3)Standardized text fields (Category, Ship Mode, Segment)
4)Created derived columns:
Order Year, Month,Month name, Quarter from order date column
Delivery Days : ship date- order date
Profit Margin
Profit Status (Good / Loss / Low Margin – Red Flag)
5)Loaded cleaned data into the Excel Data Model for advanced analysis

**Key KPIs**

The dashboard highlights four critical KPIs:
1)Total Sales – Overall revenue generated
2)Profit % – Net profitability indicator
3)Repeat Rate – Percentage of customers placing repeat orders
4)Average Delivery Time – Operational efficiency metric (days)

All KPIs dynamically respond to slicers and timeline filters.

**Dashboard Insights**

The dashboard provides insights across multiple business dimensions:

1)Time-Based Analysis
Year-wise, month-wise, and quarter-wise sales trends
Interactive timeline enables quick historical comparisons

2)Shipping Performance
Average delivery time by Ship Mode
Helps evaluate logistics efficiency and customer experience

3) Geographic/Region-wise Performance
Top states and cities by Sales and Profit
Identifies high-performing and underperforming regions

4)Product & Category Analysis
Sales and profit comparison across Categories and Sub-Categories
Identifies high-revenue but low-margin products (risk indicators)

5)Customer Segmentation
Contribution of Consumer, Corporate, and Home Office segments
Visualized using a Sales vs Profit donut chart

6)Profitability Health Check
Profit Status classification:
  Good
  Loss
  Low Margin 

This helps management identify where discounts or costs are impacting profits

**Business Value**
--> This dashboard helps stakeholders:
         Track revenue and profit at a glance
         Understand customer repeat behavior
         Identify delivery and logistics bottlenecks
         Detect discount-driven profit erosion
         Make data-driven decisions on pricing, shipping, and product strategy
