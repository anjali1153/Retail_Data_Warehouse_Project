# Retail_Data_Warehouse_Project

## Project Overview
This project demonstrates the end-to-end implementation of a Retail Sales Data Warehouse and Business Intelligence solution using Python, MySQL, SQL, and Power BI.
The project focuses on transforming raw retail sales data into meaningful business insights through ETL processes, dimensional data modeling, SQL-based analytics, and interactive dashboards.The dataset used is the Sample Superstore dataset containing sales transactions, customer information, product details, regional data, profits, discounts, and order information.

## Business Problem
- Retail organizations generate large amounts of sales data every day. Decision-makers require accurate reports and dashboards to understand:
1. Revenue performance
2. Profitability trends
3. Customer behavior
4. Product performance
5. Regional sales performance
6. Business KPIs
- The objective of this project is to build a scalable reporting solution that converts raw sales data into actionable business intelligence.

## Project Architecture :
CSV Dataset
->
Python ETL Pipeline
->
MySQL Staging Layer
->
Data Warehouse
(Fact & Dimension Tables)
->
SQL Analytics & Views
->
Power BI Dashboard
->
Business Insights

## Technology Stack :
- Programming
1. Python
- Pandas
- NumPy
2. Database
- MySQL
- SQL
3. Business Intelligence
- Power BI
4. Development Tools
- Jupyter Notebook
- MySQL Workbench
- Git
- GitHub

## Dataset Information
- Dataset: Sample Superstore
- Records: 9,994+
- Features: 21 Columns
= Key Fields:
1. Order ID
2. Order Date
3. Ship Date
4. Customer ID
5. Customer Name
6. Segment
7. Region
8. State
9. Category
10. Sub-Category
11. Product Name
12. Sales
13. Quantity
14. Discount
15. Profit

## ETL Process :
1. Extract
- The retail sales dataset was loaded from CSV files using Pandas.

2. Transform
- Data cleaning and preprocessing activities included:

- Column standardization
- Date conversion
- Duplicate removal
- Data validation
- Feature engineering
- Year extraction
- Month extraction
- Quarter extraction

3. Load
- The transformed data was loaded into MySQL for further analysis and reporting.

## Data Warehouse Design
- Fact Table
1. fact_sales
- Contains transactional sales data.

Fields:
1. order_id
2. customer_id
3. product_id
4. order_date
5. region
6. sales
7. quantity
8. discount
9. profit

2. Dimension Tables
   
1. dim_customer
- customer_id
- customer_name
- segment

2. dim_product
- product_id
- product_name
- category
- sub_category

3. dim_region
- region
- state
- city

4. dim_date
- order_date
- year
- month
- quarter

## Power BI Dashboard
- KPI Cards
1. Total Revenue
2. Total Profit
3. Total Orders
4. Total suctomers

- Visualizations
1. Revenue by Region
- Analyzes sales performance across geographical regions.

2. Revenue by Category
- Shows category contribution to overall revenue.

3. Monthly Sales Trend
- Tracks sales growth over time.

4. Key Performance indicator
- Tracking perfomance of total revenue.

## Key Business Insights
- Identified top-performing sales regions.
- Evaluated profitability across product categories.
- Analyzed customer purchasing behavior.
- Tracked monthly sales growth trends.
- Identified products contributing the highest revenue.
- Supported data-driven business decision-making through interactive dashboards.

## Project Outcomes
- Built an end-to-end ETL pipeline using Python.
- Implemented a dimensional data warehouse model.
- Created fact and dimension tables for analytical reporting.
- Developed SQL-based business analytics.
- Designed interactive Power BI dashboards.
- Generated actionable insights from retail sales data.

## Future Enhancements
- Automated ETL scheduling
- Incremental data loading
- Cloud deployment using Azure/AWS
- Advanced Power BI reporting
- Real-time dashboard integration
- Data quality monitoring

## Author

- Anjali Wable
 : Data Analytics | Business Intelligence | Data Engineering

- GitHub:
: https://github.com/anjali1153
