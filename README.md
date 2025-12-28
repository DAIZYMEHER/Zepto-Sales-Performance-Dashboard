📊 Zepto Sales Performance Dashboard – Looker Studio

Project Link: https://lookerstudio.google.com/s/lfg20UZkBfQ

📌 Project Overview:

This project delivers an interactive sales analytics dashboard for Zepto using Google Looker Studio. It transforms raw transactional data into actionable insights by applying data cleaning, modeling, KPI calculations, and advanced visualizations to evaluate sales, customer behavior, and delivery performance.

🎯 Business Objectives:

Measure sales and revenue performance across time dimensions

Analyze customer purchase behavior and order distribution

Identify top-performing cities and product categories

Monitor delivery status and operational efficiency

Enable dynamic exploration through interactive filters

🗂 Dataset & Data Model:

Source: Sample Zepto sales dataset (200 records)

Granularity: Order-level transactional data

Schema Highlights:

order_id (Primary Key)

order_date (Date dimension)

customer_id

city

product_category

quantity

order_value

payment_mode

delivery_status

Data Preparation:

Null value handling

Date formatting and parsing

Data type standardization

Derived calculated fields

🛠 Tech Stack:

BI Tool: Google Looker Studio

Data Source: Google Sheets / Excel

Data Transformation: Pre-processed in Sheets/Excel + Looker calculated fields

Version Control: GitHub

📈 KPIs & Calculated Metrics:

Total Orders – COUNT(order_id)

Total Revenue – SUM(order_value)

Total Quantity Sold – SUM(quanity

Average Price - AVG(price)

📊 Dashboard Components:

Scorecards for high-level KPIs

Time-series charts for order & revenue trends

Bar charts for city-wise and category-wise performance

Pie charts for payment mode and delivery status

Interactive filters: Date range, City, Product Category

🖼 Screenshots:

Zepto Sales Performance Dashboard:

![Zepto_Dashboard_page-0001](https://github.com/user-attachments/assets/8b23e1cc-66da-47de-afc9-088adace3613)

Example:

Overview Dashboard: High-level KPIs and filters

Sales Trends: Orders and revenue over time

Category & City Analysis: Performance comparison

🚀 Setup & Usage:

Upload the dataset to Google Sheets

Connect the sheet to Looker Studio

Configure calculated fields and metrics

Build visual components and apply filters

Publish or share the dashboard

📌 Insights Generated:

Identified revenue-driving cities and categories

Observed seasonal and daily order trends

Analyzed delivery success and failure patterns

Evaluated customer purchasing distribution

🔮 Future Enhancements:

Integration with real-time APIs

Advanced customer segmentation

Predictive sales forecasting

Performance optimization using blended data

👤 Author:

Daizy Meher

📊 Data Analytics & Business Intelligence

🔗 https://www.linkedin.com/in/daizy-m-3b6b2a346/
