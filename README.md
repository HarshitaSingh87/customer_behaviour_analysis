# customer_behaviour_analysis
Data Analytics Project showcasing customer behaviour analysis using Python, SQL, Power Bi
🛒 Customer Shopping Behavior Analysis

A compact end-to-end data analytics project using Python, PostgreSQL, and Power BI to analyze customer purchasing patterns and generate business insights.

📌 Project Summary

This project explores shopping behavior using a dataset of 3,900 records containing details such as gender, age, item purchased, category, discounts, subscription status, and spending patterns.

Key Objectives:

Understand customer segments

Analyze purchase trends

Identify high-value customers

Study revenue patterns across groups

Measure impact of discounts & subscriptions

🔧 Tools & Technologies

Python (Pandas, NumPy) → Cleaning & preprocessing

PostgreSQL + pgAdmin → SQL analytics

Power BI → Dashboard & visualization

SQLAlchemy → Database connection

🧹 Data Preparation (Python)

Cleaned missing values

Standardized column names

Imputed review ratings using median by category

Created new features like:

age_group

purchase_frequency_days

Removed redundant columns

Loaded processed data into PostgreSQL

🗄️ SQL Analysis (PostgreSQL)

Key insights extracted using SQL:

Revenue by gender

Product performance

Subscriber vs non-subscriber spending

Discount effect on spending

New vs returning vs loyal customers

Top products by category

All queries are included in customer_behaviour_analysis.sql.

📊 Power BI Dashboard

The Power BI report highlights:

Sales trends

Customer segmentation

Category performance

Review rating distribution

Discount usage patterns

Age & gender-based insights

💡 Insights (Short)

Subscribers spend significantly more.

Loyal customers generate highest revenue.

Apparel & footwear rely heavily on discounts.

Middle-aged group contributes most to revenue.

Express shipping users buy higher-ticket items.
