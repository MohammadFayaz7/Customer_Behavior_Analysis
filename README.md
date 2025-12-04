🛍️ Customer Shopping Behavior Analysis
📊 Project Overview

This project analyzes customer shopping behavior using real-world retail transaction data to uncover insights into spending patterns, customer segmentation, product performance, discounts, and subscription behavior.

The ultimate goal is to provide data-driven recommendations that help the company:

Improve customer engagement

Optimize marketing strategies

Boost sales and loyalty

Enhance product positioning

The dataset includes 3,900 purchase records across multiple product categories, providing a comprehensive view of consumer shopping trends.

🎯 Business Problem

A leading retail company observed changing customer purchasing patterns across:

Demographics

Product categories

Shopping channels (Online vs Offline)

Discount usage

Reviews and ratings

Payment and shipping preferences

The business wanted answers to the key question:

“How can consumer shopping data be leveraged to identify trends, improve customer engagement, and optimize marketing and product strategies?”

To address this, the project delivered:

Python-based Data Cleaning & Feature Engineering

SQL-based Business Analysis using PostgreSQL

Interactive Power BI Dashboard

Actionable Business Recommendations

Structured GitHub Repository with all assets

Business Problem Document

📁 Dataset Summary

Total Records: 3,900

Columns: 18

Key Features

Demographics

Age

Gender

Location

Subscription Status

Purchase Details

Item Purchased

Product Category

Purchase Amount

Season

Size

Color

Shopping Behavior

Discount Applied

Promo Code Used (removed due to redundancy)

Previous Purchases

Purchase Frequency

Review Rating

Shipping Type

Missing Data

37 missing values in the Review Rating column

Customer Shopping Behavior Anal…

🐍 Exploratory Data Analysis (Python)
Steps Performed

✅ Data Loading

Imported dataset using pandas

✅ Initial Exploration

Inspected structure (.info())

Generated summary statistics (.describe())

✅ Missing Value Handling

Imputed missing Review Rating values using median by product category

✅ Column Standardization

Converted column names to snake_case format

✅ Feature Engineering

Created age_group bands

Generated purchase_frequency_days feature from purchase history

✅ Data Consistency Checks

Verified redundancy between discount_applied and promo_code_used

Removed the duplicate column

✅ Database Integration

Loaded cleaned dataset into PostgreSQL for SQL-based analysis

Customer Shopping Behavior Anal…

🗄️ Business Analysis (SQL)

Structured business questions were answered using PostgreSQL:

Revenue Analysis by Gender

High-Spending Discount Users – Customers who used discounts but spent above average

Top 5 Products by Review Rating

Shipping Impact Analysis – Compare order value for Standard vs Express shipping

Subscribers vs Non-Subscribers – Total revenue and average purchase comparison

Discount-Dependent Products – Top products with highest discounted purchases

Customer Segmentation

New

Returning

Loyal (based on purchase history)

Top 3 Products per Category

Repeat Buyers vs Subscription Likelihood – Customers with >5 purchases

Revenue Contribution by Age Group

Customer Shopping Behavior Anal…

📈 Power BI Dashboard

Interactive visualizations were created to allow business stakeholders to explore key insights:

Dashboard Includes

Revenue by customer segment & demographic slices

Product category performance

Subscription comparisons

Purchase trends across seasons

Discount & shipping analysis

Age group contributions to revenue

📄 File:

customer_behavior_dashboard.pbix

Customer Shopping Behavior Anal…

💡 Business Recommendations

Based on combined Python, SQL, and Power BI insights:

✅ Boost Subscriptions
Promote exclusive subscriber benefits and targeted campaigns to improve conversion.

✅ Enhance Loyalty Programs
Offer rewards to frequent buyers to move customers into the “Loyal” segment.

✅ Optimize Discount Strategy
Avoid over-discounting high-demand products to protect profit margins.

✅ Product Positioning
Highlight top-rated and best-selling products more prominently in marketing.

✅ Targeted Marketing
Focus advertising on:

High-revenue age groups

Express-shipping customers

Repeat buyers showing strong spending behavior
