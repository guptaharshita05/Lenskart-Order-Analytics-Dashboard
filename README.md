# Lenskart Order Analytics Dashboard using Power BI & Excel

## Project Overview

This dashboard project explores customer order data from Lenskart to generate actionable insights around revenue, feedback, product performance, and payment success. It simulates a real-world analytics case for a D2C brand.

Using Power BI for dashboarding and Excel for data cleaning, this project demonstrates full-cycle BI development from raw data to insights.

## Objective

To extract business-critical insights from structured and unstructured order data, including:

* Revenue performance across categories and cities
* Customer sentiment analysis from feedback
* Order trend analysis by month
* Payment success and failure distribution

## Tools & Technologies

* **Microsoft Power BI** – Dashboard creation, KPIs, and data visualization
* **Microsoft Excel** – Data cleaning and preprocessing
* **DAX** – Used for sentiment tagging, AOV, total revenue, and feedback %

## Dataset Summary

* `unstructured_order_data_lenskart.xlsx`: Raw file with inconsistent formatting
* `lenskart_order_data_cleaned.xlsx`: Final cleaned dataset used for dashboard
* 50 records across 10+ columns: City, Product Category, Quantity Sold, Price, Payment Status, Customer Feedback, etc.

## Key Metrics & Calculations

DAX was used to derive key metrics:

* **Revenue** = Quantity Sold × Price
* **AOV (Average Order Value)** = Total Revenue / Total Orders
* **Feedback %** = % of customers who submitted feedback
* **Sentiment Tagging** = Classified feedback as Positive, Negative, or No Feedback using text-based rules

## Dashboard (Power BI-Based)

The dashboard was created in Power BI and includes the following elements:

* **KPI Cards**: Total Revenue, AOV, Total Orders, Feedback %
* **Revenue by Product Category** (Bar Chart)
* **Orders by Month** (Line Chart)
* **Revenue by City** (Donut Chart)
* **Feedback Sentiment Split** (Pie Chart)
* **Payment Status Distribution** (Pie Chart)
* **Filters** for City, Category, Payment Status, and Sentiment

🔗 Live Dashboard: [View on Power BI Web](https://app.powerbi.com/groups/me/reports/b409fa88-bfba-4c7b-a355-0d9525ba14bf/dd78254f7542a0dcbee3?experience=power-bi)

## Core Insights

* 🛍 **Revenue Leaders:** Glasses & Sunglasses = 75%+ of total revenue
* 💬 **Customer Voice:** 96% gave feedback — sentiment is 50% positive, 50% negative
* 💳 **Payment Success:** 76% successful; 10% failed (needs UX improvement)
* 🌐 **Top Cities:** Mumbai leads, followed by Delhi & Bangalore
* 📈 **Order Trends:** High in Jan & May, dip in March — possibly seasonal

## Applications

This dashboard can be used to:

* Identify high-performing product lines
* Optimize customer feedback loops
* Prioritize payment and delivery improvements
* Present category-level strategy to internal stakeholders

## Author
**Harshita Gupta**  
Aspiring Business Analyst | SQL & Data-Driven Insights  
Email: harshita.work50@gmail.com  
LinkedIn: https://www.linkedin.com/in/harshita-gupta-383123256/
