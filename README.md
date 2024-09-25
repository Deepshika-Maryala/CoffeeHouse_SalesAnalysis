# Coffee House Sales Trends and Insights
### Project Overview:
The goal of this Power BI project is to analyze the sales performance of a coffee shop, providing insights into customer preferences, sales trends, popular products, and operational efficiency. This analysis helps management optimize inventory, pricing, and marketing strategies to drive revenue and improve customer satisfaction.
### Purpose and Performance Targets:
- Design and develop an interactive sales overview dashboard and products overview dashboard.
- Provide real-time insights into total sales, sales trends, and revenue growth over time to help optimize sales strategies.
- Visualize key metrics such as total sales, total quantity and total orders.
### Data Source:
Sales data: The primary dataset used for analysis is the “ Coffee Shop Sales.xlsx” file, containing detail information of coffee sales, products, and transactions.
### Tools
- Excel spreadsheets – Data cleaning
- SQL – Data Analysis
- Power BI Desktop [version 2.126.927.0] – Creating reports
### Exploratory Data Analysis:
EDA involved exploring the sales data to answer the key questions such as:
- What are the sales trends over different periods (e.g., hourly, daily, monthly)?
- What are the peak sales hours or busiest times during the day or week?
- How does sales performance vary by store location?
### Data Analysis:
Analyzing Total sales , total quantity, and total orders using SQL
```sql
Select sum(sales) as Total Sales from transactions;
Select sum(transaction_qty) as Total Quantity from transactions;
Select count(transaction_id) as Total Orders from transactions;
```
### Analyzed Metrics:
- Total sales
- Total Quantity
- Total orders
### Visuals and Dashboards:
#### Overview Dashboard:
- KPI: Total sales, total transactions, total products and total product types.
#### Sales Dashboard:
- KPI: Total sales, total transactions, total products and total product types.
- Daily Sales Analysis: Analyzing the sales of the current month on daily basis.
- Hourly Sales Analysis: Analyzing the sales of the current month on hourly basis.
- Sales by Weekday/ Weekend: Analyzing sales of current month on weekly basis and comparing the sales on weekdays vs weekends.
- Sales by Store location: Analyzing the sales of the different stores.
#### Product Dashboard:
- KPI: Total sales, total transactions, total products and total product types.
- Sales by Product Type: Analyzing the sales of top 5 product type over a month.
- Total Sales and Quantity= category: Analyzing the sales of top 10 product category over a month.
- Displaying the best seller.
### User Interactive Features:
Slicer : Provide options for different time periods (months).
### Project phases and milestones:
- Data Collection and Preparation: December 2023
- Dashboard Design and Development: February 2024








