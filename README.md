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
Select sum(sales) as Total_Sales from transactions;
```
![Screenshot 2024-09-25 232852](https://github.com/user-attachments/assets/b51d42d7-99a4-4452-acf9-6039110df2d3)

```sql
Select sum(transaction_qty) as Total_Quantity_Sold from transactions;
```
![Screenshot 2024-09-25 232921](https://github.com/user-attachments/assets/1835015d-3066-474c-91aa-df63297d75e3)

```sql
Select count(transaction_id) as Total_Orders from transactions;
```

![Screenshot 2024-09-25 232906](https://github.com/user-attachments/assets/1d4db0dc-f183-4414-a756-b46d3d6635a8)

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
## Report Snapshot (Power BI Desktop)


![Screenshot 2024-09-25 230413](https://github.com/user-attachments/assets/014bc45e-4aba-40f1-9fd1-eb93cb142e1c)



![Screenshot 2024-09-25 230501](https://github.com/user-attachments/assets/0feca734-ff57-42b3-b7d1-f270a666e64c)



![Screenshot 2024-09-25 232542](https://github.com/user-attachments/assets/92586947-9823-4d60-9c74-53197643c87c)

