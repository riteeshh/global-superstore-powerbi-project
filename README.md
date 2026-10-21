# Global Superstore – Power BI Sales Dashboard

An interactive Power BI report that analyses sales, profit and customers for Global Superstore. It tracks sales performance over time, shows which categories, countries and sub-categories drive profit, and ends with business insights and recommendations.

## Dataset

**Global Superstore** – 51,290 rows and 24 columns, covering orders from **January 2011 to December 2014**.

Key columns: Order ID, Order Date, Ship Date, Ship Mode, Customer Name, Segment, Country, Market, Region, Category, Sub-Category, Product Name, Sales, Quantity, Discount, Profit, Shipping Cost, Order Priority.

The file is included as `Global_Superstore2.csv.zip`. Unzip it before loading it into Power BI.

## Dashboard Pages

### 1. Executive Overview
- **KPI cards:** Total Sales, Total Profit, Total Orders, Total Customers, Profit Margin %
- **Year-wise sales** line chart (with Year → Quarter → Month → Day drill-down)
- **Category-wise sales** bar chart
- **Slicers:** Region, Category

### 2. Detailed Analysis
- **Category summary table:** sales, quantity, profit and customers by category
- **Top 10 countries by sales** bar chart
- **Customer table:** sales and profit by customer
- **Scatter chart:** average discount, total profit and total sales by sub-category
- **Slicers:** Segment, Region, Category

### 3. Insights & Recommendations
- Key insights from the data
- Business recommendations
- Problems and opportunities
- CEO takeaway
- **Slicers:** Region, Category, Segment

## DAX Measures
`Total_Sales` · `Total_Profit` · `Total_Orders` · `Total_Customer` · `Total_Quantity` · `Average_Discount` · `Profit_Margin`

## Skills Demonstrated
Data modelling · DAX measures · KPI cards · drill-down charts · slicers and interactivity · scatter-chart analysis · data storytelling

## How to Open
1. Download `Project.pbix`.
2. Open it in **Power BI Desktop**.
3. If Power BI asks for the data source, point it to the unzipped `Global_Superstore2.csv`.

## Project Structure
```
├── README.md
├── Project.pbix
└── Global_Superstore2.csv.zip
