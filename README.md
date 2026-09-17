**📊 Excel Sales Dashboard
An interactive Excel Sales Dashboard built to analyze sales performance, revenue, profit, products, regions, and other key business metrics.

The project uses Power Query, Power Pivot, DAX, Pivot Charts, Charts, Slicers, and Filters to transform raw data into an interactive business intelligence dashboard.

🎯 Project Objectives
Clean and transform raw sales data using Power Query

Build a structured data model using Power Pivot

Create calculated metrics using DAX measures

Analyze sales, revenue, profit, quantity, and other KPIs

Create interactive Pivot Charts and Excel Charts

Add Slicers and Filters for dynamic analysis

Identify important trends and business patterns

Present insights through an easy-to-understand dashboard

❓ Business Questions
The dashboard is designed to answer questions such as:

What is the total sales/revenue generated?

What is the total profit?

How many units were sold?

Which products generate the highest revenue?

Which products generate the highest profit?

Which regions contribute the most to sales?

How does sales performance change over time?

Which categories perform better?

What is the overall profit margin?

How does performance change when different filters are applied?

🔄 Workflow
Raw Excel Data
      ↓
Power Query
      ↓
Data Cleaning & Transformation
      ↓
Power Pivot
      ↓
Data Model
      ↓
DAX Measures
      ↓
Pivot Tables
      ↓
Pivot Charts & Charts
      ↓
Slicers & Filters
      ↓
Interactive Excel Dashboard
🧹 Data Preparation – Power Query
Power Query was used for:

Importing raw sales data

Removing unnecessary columns

Handling missing values

Correcting data types

Cleaning inconsistent data

Transforming columns

Preparing data for the data model

This creates a clean and structured dataset before analysis.

🗂️ Data Model – Power Pivot
The cleaned data was loaded into Power Pivot to create a reusable data model.

Main Data
The model contains important fields such as:

Order ID

Order Date

Ship Date

Customer

Segment

Region

Category

Sub-Category

Product

Sales

Quantity

Discount

Profit

The data model allows relationships and calculations to be used efficiently across PivotTables and dashboard visualizations.

🧮 DAX Measures
DAX measures were created in Power Pivot to calculate important business KPIs.

Total Sales
Total Sales = SUM(Sales[Sales])
Total Profit
Total Profit = SUM(Sales[Profit])
Total Quantity
Total Quantity = SUM(Sales[Quantity])
Total Orders
Total Orders = DISTINCTCOUNT(Sales[Order ID])
Profit Margin
Profit Margin = DIVIDE([Total Profit], [Total Sales], 0)
Average Sales
Average Sales = AVERAGE(Sales[Sales])
Note: Replace Sales with the actual table name used in the workbook if your Power Pivot table has a different name.

📊 Dashboard Features
The dashboard includes:

KPI Cards
💰 Total Sales

📈 Total Profit

📦 Total Quantity

🛒 Total Orders

📊 Profit Margin

Visualizations
Sales by Category

Sales by Region

Profit by Product

Sales Trend

Quantity Analysis

Category/Region comparisons

Interactive Controls
Slicers

Filters

PivotTable filters

Dynamic chart interaction

Users can select different categories, regions, products, dates, or other fields to dynamically analyze the dashboard.

📈 Charts & Pivot Charts
The dashboard uses multiple visualization types, including:

Column Charts

Bar Charts

Line Charts

Pivot Charts

These visualizations make it easier to identify sales trends, product performance, regional performance, and profitability patterns.

🎛️ Slicers & Filters
Slicers were added to make the dashboard interactive.

Example filters include:

Region

Category

Sub-Category

Segment

Product

Order Date

Selecting a slicer value automatically updates the connected PivotTables and charts.

🖼️ Dashboard Screenshot
Add your dashboard screenshot to the repository and update the filename below:

![Excel Sales Dashboard](images/dashboard.png)
Example:

Excel Sales Dashboard

Replace images/dashboard.png with the actual path and filename of your dashboard screenshot.

🔍 Key Findings
The dashboard can be used to identify findings such as:

High-performing products contribute significantly to overall sales.

Sales performance varies across different regions and categories.

Some products generate strong revenue but comparatively lower profit.

Profitability can vary significantly between product categories.

Time-based analysis helps identify changes in sales performance.

Interactive filters make it easier to investigate specific products, regions, and categories.

Update these findings with the exact results from your dashboard before publishing the project.

📁 Repository Structure
Excel-Sales-Dashboard/
│
├── README.md
│
├── Excel_Dashboard.xlsx
│
├── images/
│   └── dashboard.png
│
└── data/
    └── sales_data.xlsx
🛠️ Tools & Technologies
Tool	Purpose
Microsoft Excel	Dashboard development
Power Query	Data cleaning & transformation
Power Pivot	Data modeling
DAX	KPI and measure calculations
PivotTables	Data analysis
Pivot Charts	Interactive visualization
Charts	Data visualization
Slicers	Interactive filtering
Filters	Data exploration
🚀 How to Use
Download the Excel workbook.

Open Excel_Dashboard.xlsx in Microsoft Excel.

Navigate to the Dashboard sheet.

Use the slicers and filters to explore the data.

Select different categories, regions, products, or dates.

Review the KPI cards and charts.

Refresh the workbook if the underlying data is updated.

💡 Skills Demonstrated
This project demonstrates practical skills in:

Excel Data Analysis

Data Cleaning

Power Query

Power Pivot

Data Modeling

DAX

PivotTables

Pivot Charts

Data Visualization

Dashboard Development

Business Analysis

Interactive Reporting

📌 Project Summary
This project demonstrates how raw sales data can be transformed into an interactive business dashboard using Microsoft Excel. Power Query was used for data preparation, Power Pivot for data modeling, and DAX for creating analytical measures. Pivot Charts, charts, slicers, and filters were then used to create an interactive reporting experience

