📊 E-Commerce Sales Performance Dashboard

Data Science & Analytics Internship – Future Interns (Task 1)

🔍 Project Overview

This project focuses on analyzing e-commerce sales data to build a professional, interactive Power BI dashboard.
The goal is to help business owners and decision-makers understand:

🏆 Best-selling products

📈 Sales trends and peak periods

💰 High-revenue categories, regions, and states

The dashboard is fully interactive, allowing users to filter data and explore insights dynamically.

📁 Dataset Used

Superstore Sales Dataset (Beginner-Friendly)
Download from Kaggle:
👉 https://www.kaggle.com/datasets/mohamed38/superstoredataset

Dataset contains:

Order details (Order ID, Order Date, Ship Date)

Product details (Category, Sub-Category)

Sales metrics (Sales, Profit, Quantity, Discount)

Geographic data (Region, State)

🛠️ Tools & Technologies

Power BI Desktop

Microsoft Excel

DAX (Data Analysis Expressions)

🚀 Step-by-Step Process (From Scratch)
🔹 Step 1: Download the Dataset

Open the Kaggle link provided above

Download the Superstore dataset (.xlsx)

Save it locally on your system

🔹 Step 2: Load Data into Power BI

Open Power BI Desktop

Click Home → Get Data → Excel

Select the downloaded Superstore file

Choose the main sheet (Orders / Superstore)

Click Load

🔹 Step 3: Data Cleaning (Power Query)

Click Home → Transform Data

Ensure correct data types:

Order Date → Date

Ship Date → Date

Sales → Decimal Number

Profit → Decimal Number

Quantity → Whole Number

Discount → Decimal Number

Remove unnecessary columns (optional): Row ID, Postal Code

Remove blank rows

Click Close & Apply

🔹 Step 4: Create DAX Measures (KPIs)

Go to Report View → Right-click table → New Measure and add:

Total Sales = SUM('Orders'[Sales])

Total Profit = SUM('Orders'[Profit])

Total Orders = DISTINCTCOUNT('Orders'[Order ID])

Total Quantity = SUM('Orders'[Quantity])

Average Order Value = DIVIDE([Total Sales], [Total Orders])


These measures automatically update when filters are applied.

🔹 Step 5: Build Dashboard Visuals
KPI Cards (Top Section)

Total Sales

Total Profit

Total Orders

Total Quantity

Average Order Value

Sales Trend Analysis

Line Chart

X-axis: Order Date (Month-Year)

Y-axis: Total Sales

Category Performance

Bar Chart

Category vs Total Sales

Best-Selling Products

Bar Chart

Sub-Category vs Total Sales (sorted descending)

Regional Analysis

Column Chart

Region vs Total Sales

Geographic Analysis

Map (Bubble Map)

Location: State

Size: Total Sales

Tooltip: Total Profit

🔹 Step 6: Add Interactivity (Slicers)

Added slicers for:

Order Date (Year)

Category

Region

These allow users to dynamically explore the dashboard.

🔹 Step 7: Business Insights

Added a text section summarizing insights such as:

Peak sales periods

Top-performing categories and sub-categories

High-revenue regions and states

Profit variability across categories

This converts visuals into actionable business understanding.

📐 Dashboard Design

Canvas Size: 1400 × 2000 px

Clean color theme

Logical layout (KPIs → Trends → Products → Geography → Insights)

🎯 Key Learnings

Data cleaning & preparation

DAX for KPI creation

Time-series trend analysis

Business storytelling with dashboards

Building interactive Power BI reports

📌 Final Outcome

An interactive, professional Power BI dashboard that enables data-driven decision-making and fulfills Future Interns – Task 1 requirements.

🔗 Internship

Organization: Future Interns
Track: Data Science & Analytics
Task: Business Sales Dashboard from E-commerce Data