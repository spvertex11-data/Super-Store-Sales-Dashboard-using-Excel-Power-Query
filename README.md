📊 Super Store Sales Dashboard using Excel & Power Query
📌 Project Overview
Project Title

Super Store Sales Dashboard | Data Cleaning, ETL & Interactive Excel Dashboard

Project Description

This project demonstrates an end-to-end Business Intelligence workflow using Microsoft Excel and Power Query. Raw sales data was imported, cleaned, transformed, and analyzed using Power Query before creating Pivot Tables, Pivot Charts, KPIs, and an interactive dashboard.

The dashboard enables users to analyze sales performance by Region, City, Ship Mode, Customer Segment, Category, and Year through interactive slicers and visualizations.

🎯 Project Objective

The objective of this project is to transform raw sales transaction data into meaningful business insights by automating the data preparation process and creating an interactive dashboard for decision-making.

🔄 Project Workflow

Raw Sales Dataset
        │
        ▼
Import into Excel
        │
        ▼
Power Query
(Data Cleaning & Transformation)
        │
        ▼
Cleaned Data Table
        │
        ▼
Pivot Tables
        │
        ▼
Pivot Charts
        │
        ▼
Interactive Dashboard

📁 Step 1 – Import Raw Data

The project begins with an unstructured Super Store sales dataset containing customer, product, shipping, and sales information.

Dataset Includes
Row ID
Order ID
Order Date
Ship Date
Ship Mode
Customer ID
Customer Name
Segment
Country
City
State
Postal Code
Region
Product ID
Category
Sub-Category
Product Name
Sales
Quantity
Discount
Profit


🧹 Step 2 – Data Cleaning using Power Query

The dataset was imported into Power Query Editor for ETL processing.

Cleaning Activities
Promoted first row as headers.
Corrected data types.
Converted Order Date to Date format.
Converted Ship Date to Date format.
Applied locale-specific date conversion.
Removed incorrect formatting.
Validated numeric fields.
Removed unnecessary rows and columns.
Ensured data consistency.


🔧 Step 3 – Data Transformation

The cleaned data was transformed into an analysis-ready dataset.

Transformations Performed
Converted text to proper data types.
Formatted date columns.
Structured the dataset for Pivot Tables.
Loaded the transformed data into Excel as an Excel Table.


📋 Step 4 – Load Clean Data

The processed data was loaded into Excel.

Final Dataset

The cleaned table contains:

Order ID
Customer Name
Region
City
Category
Ship Mode
Sales
Quantity
Profit
Order Date
Ship Date

This serves as the master data source for analysis.

📊 Step 5 – Create Pivot Tables

Multiple Pivot Tables were created to summarize business performance.

KPI Summary
Total Sales
Total Quantity
Total Orders
Average Sales
Ship Mode Analysis
First Class
Second Class
Same Day
Standard Class
Regional Analysis
East
West
South
Central
Monthly Analysis
January
February
March
…
December
Category Analysis
Furniture
Office Supplies
Technology
Customer Segment Analysis
Consumer
Corporate
Home Office
City Analysis

Top-performing cities based on sales.

📈 Step 6 – Create Dashboard Visualizations

The Pivot Tables were converted into interactive charts.

Charts Included
KPI Cards
Pie Chart – Ship Mode Sales %
Doughnut Chart – Region-wise Transactions
Line Chart – Monthly Quantity Ordered
Column Chart – Top 5 Cities by Sales
Horizontal Bar Chart – Category-wise Transactions
Horizontal Bar Chart – Customer Segment Quantity


🎛️ Step 7 – Add Interactive Slicers

Slicers were added for dynamic filtering.

Filters
Region
Year

Users can instantly filter the dashboard to analyze specific regions or years.

📌 Dashboard KPIs

The dashboard displays the following key performance indicators:

Total Sales
Average Sales
Total Transactions
Total Quantity Ordered


📊 Dashboard Insights

The dashboard enables analysis of:

Sales Performance
Overall sales
Average sales
Transaction volume
Shipping Analysis
Sales by shipping mode
Distribution of shipping methods
Regional Performance
Transactions by region
Regional contribution
Monthly Trends
Monthly quantity ordered
Seasonal sales trends
Product Performance
Sales by category
Category contribution
Customer Analysis
Quantity by customer segment
Consumer behavior
Geographic Analysis
Top-performing cities
Regional sales comparison


🛠️ Technologies Used
Microsoft Excel
Power Query
Pivot Tables
Pivot Charts
Excel Dashboard
Slicers
Data Cleaning
ETL
Data Transformation
Business Intelligence
Data Visualization


💼 Skills Demonstrated
Microsoft Excel
Power Query (M)
ETL (Extract, Transform, Load)
Data Cleaning
Data Transformation
Data Validation
Pivot Tables
Pivot Charts
Interactive Dashboard Design
KPI Reporting
Business Intelligence
Data Visualization
Slicers & Filtering
Excel Table Management






