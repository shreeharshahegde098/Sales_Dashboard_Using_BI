Sales BI Report
📊 Overview

This project demonstrates a Sales Analysis Dashboard created using Power BI.
The workflow starts with a raw dataset in Excel, followed by data transformation in Power Query, and finally dashboard design in Power BI Desktop.

🗂 Dataset

Source File: Sales_BI_dataset.xlsx

Key Features of Dataset:

Contains raw sales data.

Includes fields such as product, region, sales values, and customer details.

One additional calculated field: Revenue (derived during Power BI data transformation).

Added a Month column in Power Query Editor for time-based analysis.

🔄 Data Transformation (Power Query Editor)

Steps performed in Power Query Editor:

Loaded raw data from Excel.

Calculated Revenue using formula (e.g., Revenue = Quantity × Price).

Added a new Month column from date field for monthly aggregation.

Cleaned and shaped data for dashboard visualization.

📈 Dashboard Design

The Power BI Dashboard (Sales_bev_report.pbix) consists of the following elements:

Cards (3 total):

Total Sales / Revenue

Total Quantity Sold

Total Customers / Regions (depending on dataset fields)

Map Visual:

Shows sales distribution by geographic location.

Stacked Column Chart:

Compares sales performance across categories (e.g., months, products, or regions).

Slicer:

Allows filtering the dashboard by Month (and possibly other dimensions).

🚀 Usage Instructions

Open the Power BI file: Sales_bev_report.pbix.

Explore the dashboard interactively using slicers.

Modify visuals or add more KPIs as needed.

📌 Key Learnings

How to import and clean data using Power Query Editor.

Creating calculated columns (e.g., Revenue).

Designing a dashboard with KPIs, maps, and charts.

Using slicers for interactivity.
