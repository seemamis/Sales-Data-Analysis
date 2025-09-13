Case Study: Sales Performance Dashboard

**Project Title**
Sales Performance Dashboard for a Retail Company

**Business Problem Statement**
The retail company has been experiencing inconsistent sales growth across regions and product categories. Senior management needs a centralized sales dashboard to monitor revenue, profitability, and performance trends in real time. The goal is to identify high-performing products, declining regions, and seasonal patterns to guide sales strategy and promotional campaigns.

**Dataset**

Source: Microsoft AdventureWorks Sample Dataset (available from Power BI sample datasets).
Size: ~29,000 rows, 20+ columns.

Key Features:

Order Date (time dimension for trend analysis)
Product Category & Subcategory (hierarchy for drill-throughs)
Customer & Region (for segmentation analysis)
Sales Amount, Cost, Profit (financial metrics)

**Approach & Process**

🔹 Data Preparation
Imported multiple tables (Sales, Products, Customers, Territories) into Power BI.
Cleaned data using Power Query: removed duplicates, fixed date formats, standardized product names.

🔹 Data Modeling

Established relationships:
    Sales → Product (ProductID)
    Sales → Customer (CustomerID)
    Sales → Region (TerritoryID)
    Built calculated fields:
    Revenue = SUM(SalesAmount)
    Profit = SUM(SalesAmount - Cost)
    Profit Margin % = DIVIDE(Profit, Revenue)
    YoY Growth = (Current Year Sales – Previous Year Sales) / Previous Year Sales

🔹 Dashboard Design

KPIs Cards: Revenue, Profit, Profit Margin %, YoY Growth.
Bar Chart: Top 5 Products by Sales.
Map: Sales distribution by Region.
Line Chart: Monthly sales trend over 3 years.
Table with Conditional Formatting: Customer segmentation by revenue contribution.
Added time slicers (Year/Quarter/Month) + drill-through to product details.

**Key Insights**

📈 Revenue grew 12% YoY, but profit margin dropped by 4% due to higher discounts in Region East.
🏆 Product Category: Bikes accounted for 40% of total revenue, with Mountain Bikes being the top seller.
📍 Region West showed the highest profitability despite contributing only 25% of sales.
🔄 Seasonal analysis revealed a consistent Q4 sales spike due to holiday demand.

**Business Impact**

The sales team can prioritize promotions in high-margin regions (West) instead of focusing only on high-volume regions (East).
Inventory planning can allocate higher stock for Q4 to match seasonal demand.
Product-level insights allow management to focus marketing on fast-growing categories (e.g., Mountain Bikes).

**Deliverables**

📂 [Power BI File (.pbix) on GitHub]

🌐 [Live Dashboard (Power BI Service Link)]

📸 Dashboard Screenshots:

(Insert 2–3 images of your dashboard here in your portfolio site/LinkedIn post)
