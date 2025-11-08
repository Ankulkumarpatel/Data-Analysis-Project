🛍️ Customer Shopping Behavior Analysis
📄 Overview

This project analyzes customer shopping behavior to uncover insights into purchasing patterns, preferences, and revenue trends. It demonstrates a complete analytics workflow — from data extraction and cleaning in Python, SQL-based analysis in PostgreSQL, interactive visualization in Power BI, and final business presentation using GMMA (Generative Microsoft Assistant).

The objective is to support data-driven decision-making by identifying the most profitable segments, high-performing categories, and customer engagement trends.

📊 Dataset

Name: Customer Shopping Data

Source: Public / Sample e-commerce dataset (replace with actual source if available)

Format: CSV file

Key Columns:

Customer_ID

Gender

Age_Group

Product_Category

Subscription_Status

Purchase_Amount

Review_Rating

Payment_Method

Order_Date

🧰 Tools & Technologies
Tool / Technology	Purpose
Python (Pandas, NumPy, Matplotlib, Seaborn)	Data loading, cleaning, and EDA
PostgreSQL	SQL queries and data aggregation
Power BI	Dashboard and visualization
GMMA / PowerPoint	Report and presentation creation
Jupyter Notebook	Development and documentation
⚙️ Steps Followed
1. Data Loading & Preparation

Imported the dataset using Pandas.

Checked for null values, duplicates, and inconsistent data types.

Handled missing data and standardized column names.

2. Exploratory Data Analysis (EDA)

Generated descriptive statistics.

Visualized key relationships like sales by category, gender, and subscription status.

Identified customer behavior patterns and revenue contributions.

3. Data Cleaning

Removed duplicates and outliers.

Fixed inconsistent category names.

Converted dates into proper formats for time-series analysis.

4. SQL Analysis (PostgreSQL)

Imported cleaned data into PostgreSQL.

Executed SQL queries to extract key insights:

Top-selling product categories

Average purchase per customer segment

Revenue trends over time

Subscription-based purchase comparison

5. Power BI Dashboard

Connected Power BI to PostgreSQL for live data analysis.

Designed an interactive dashboard to display customer insights and performance metrics.

Dashboard Features:

KPIs:

3.9K Total Customers

$59.76 Average Purchase Amount

3.75 Average Review Rating

Visuals:

Revenue by Category

Sales by Category

% Customers by Subscription Status

Revenue by Age Group

Filters for Subscription Status, Gender, Category, and Delivery Type.

(Refer to the Power BI dashboard image above for layout and visuals.)

6. Report & Presentation

Summarized findings in a structured report.

Created an executive presentation using GMMA / PowerPoint with clear visuals and recommendations.

📈 Results & Insights

Clothing generated the highest revenue (~104K) and most sales (1.7K+).

73% of customers were non-subscribers, showing a large untapped segment.

Young Adults contributed the highest revenue (62K).

Subscription customers had higher average purchase amounts.

Suggested focusing marketing campaigns on high-performing age groups and promoting subscription benefits.
