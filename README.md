📊 Customer Shopping Behavior Analysis

A Complete End-to-End Data Analytics Project

📝 1. Overview

This project analyzes 3,900 customer transactions to understand shopping behavior, product preferences, subscription trends, and revenue patterns.
It covers the full analytics pipeline:
✔ Python (EDA + Cleaning)
✔ SQL (Business Analysis Queries)
✔ Power BI (Interactive Dashboard)
✔ Final Report + Presentation

The insights aim to support business decision-making, improve customer segmentation, optimize discount strategy, and guide targeted marketing.

📂 2. Dataset Summary

Rows: 3,900

Columns: 18

Key Categories:

Demographics: age, gender, location, subscription status

Purchase Data: item purchased, category, purchase amount

Shopping Behavior: discount applied, review rating, previous purchases, shipping type

Missing Values: 37 (Review Rating)

🧪 3. Exploratory Data Analysis (Python)
✔ Data Loading & Inspection

Imported dataset using pandas

Viewed structure using .info(), .describe()

✔ Data Cleaning

Imputed missing review ratings using median rating per category

Standardized column names to snake_case

Removed redundant columns (promo_code_used)

Checked consistency of discount-related fields

✔ Feature Engineering

Created age_group using age bins

Created purchase_frequency_days

Loaded cleaned data into PostgreSQL for SQL analysis

🧮 4. SQL-Based Analysis (PostgreSQL / MySQL / SQL Server)

Key business questions answered through SQL:

Revenue by Gender – Total revenue contribution across male and female shoppers

High-Spending Discount Users – Discount users spending above the average

Top 5 Products by Review Rating

Shipping Type Comparison – Avg purchase amount: Standard vs. Express

Subscribers vs Non-Subscribers – Revenue & spend comparison

Discount-Dependent Products – Products purchased mostly using discounts

Customer Segmentation: New vs Returning vs Loyal

Top 3 Products per Category

Repeat Buyers & Subscription Link

Revenue by Age Group

📊 5. Power BI Dashboard

Built an interactive dashboard showing:

Revenue trends

Customer segments

Product category performance

Review ratings

Age group analysis

Discount impact

Shipping type comparison

Includes slicers for: Gender, Subscription, Category, Shipping Type, Season.

💡 6. Key Insights

Subscribers generate significantly higher revenue per customer

Loyal customers drive the majority of repeat purchases

Express shipping users spend more on average

Certain product categories depend heavily on discount usage

Best-rated products can be positioned as premium recommendations

🏢 7. Business Recommendations

Boost Subscriptions: Promote exclusive perks to increase subscriber base

Strengthen Loyalty Programs: Reward returning and loyal customers

Optimize Discount Strategy: Reduce over-discounting on high-demand products

Highlight Top Products: Use best-rated items in campaigns

Target High-Value Segments: Age groups & customers who prefer express shipping


👤 Author

Ajit Kumar – Data Analyst (BCA Final Year)
Location: Bhopal
Tools: Python | SQL | Power BI | Data Analysis
