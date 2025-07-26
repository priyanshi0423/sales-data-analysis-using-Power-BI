# sales-data-analysis-using-Power-BI
This Power BI report presents a comprehensive sales data analysis, including key metrics like Total Sales, Profit, Quantity Sold, and Average Order Value. It features interactive dashboards with visualizations such as bar charts, line graphs, and KPIs to show sales performance over time, by region, product category, and customer segments. Time intelligence functions enable Month-over-Month and Year-over-Year comparisons. Slicers allow dynamic filtering by date, region, product, and salesperson. The report supports data-driven decision-making with detailed insights into sales trends and business growth.
1. Data Sources
Usually includes:

Sales transactions data

Product details

Customer information

Date/dimensions table

Geographic data (region, city, etc.)

You can check this by opening:
Home > Transform data > Power Query Editor in Power BI.

2. Common Visualizations
These are usually placed on report pages:

Total Sales (line or bar chart)

Sales by Product Category

Sales by Region/State/City (Map or bar chart)

Monthly Trends (Line chart by date)

Top 10 Customers/Products (Bar chart or table)

Profit Margin (Gauge or KPI card)

Salesperson Performance (Donut, table, or treemap)

3. KPIs / Measures (DAX)
Some common DAX measures used:

Total Sales = SUM(Sales[Amount])

Total Quantity = SUM(Sales[Quantity])

Average Order Value = [Total Sales] / COUNT(Sales[Order ID])
Profit = SUM(Sales[Profit])
Sales Growth = ([This Year Sales] - [Last Year Sales]) / [Last Year Sales]
4. Time Intelligence
The file may include:

Year-over-Year (YoY) or Month-over-Month (MoM) comparisons

Date hierarchy (Year, Quarter, Month)

Slicers for selecting date ranges

5. Slicers and Filters
Report pages usually have filters like:
Region / Country

Date Range

Product Category

Salesperson

<img width="1367" height="743" alt="p1" src="https://github.com/user-attachments/assets/ac6fb245-42f6-41ec-a254-5f0a605ed2d7" />
<img width="1365" height="737" alt="p2" src="https://github.com/user-attachments/assets/027154d5-91e2-4d6b-8219-e9332a2dbf73" />


