# Data-analysis-project
📊 Customer Shopping Behavior Analysis
🔍 Project Overview

This project analyzes customer shopping behavior using a transactional dataset of 3,900 records across 18 features. The goal is to extract actionable business insights related to customer segmentation, purchasing patterns, product performance, and revenue drivers.

The analysis combines Python (EDA & preprocessing), MySQL (business queries), and Power BI (dashboarding) to simulate a real-world end-to-end data analytics workflow.

🎯 Objectives
Identify key revenue drivers across customer segments
Understand the impact of discounts, subscriptions, and shipping types
Analyze product performance and customer preferences
Detect gaps in customer acquisition, retention, and seasonal sales
Provide actionable, data-driven business recommendations

🧰 Tech Stack
Python – Data cleaning, preprocessing, feature engineering
Pandas, NumPy – Data manipulation
MySQL – Business query analysis
Power BI – Dashboard visualization

📁 Dataset Summary
Rows: 3,900
Columns: 18
Key Features:
Demographics: Age, Gender, Location
Purchase Data: Item, Category, Amount, Season
Behavioral Data: Discounts, Ratings, Frequency, Shipping Type
⚙️ Data Processing & Feature Engineering

Key transformations:

Standardized column names (snake_case)
Handled missing values (imputed review ratings using category averages)
Created:
age_group (quartile segmentation)
purchase_frequency_days (mapped categorical → numeric)
Removed redundant columns

📊 Key Insights
💰 Revenue Distribution
Male customers contribute ~68% of total revenue
Strong skew in dataset → indicates acquisition imbalance, not necessarily behavior difference
🎯 Discounts ≠ Low Value
High-spending customers still use discounts
Discounts act as conversion triggers, not just for low spenders
🧍 Customer Segmentation
~80% customers are “Loyal”
Only ~2% are new → serious acquisition problem

📦 Subscription Gap
73% users are not subscribed
Subscribers and non-subscribers spend almost the same
➡️ Subscription strategy is weak and poorly positioned

📉 Seasonal Failure
Summer revenue drops by ~91%
➡️ This is not “seasonality” — this is a strategy failure
🛍️ Product Insights
High discount dependency (~50%) for some products → margin leakage
Top-rated products still < 4 rating → quality perception issue
📈 Dashboard (Power BI)

The interactive dashboard highlights:

Customer segmentation & subscription breakdown
Category-wise revenue distribution
Seasonal sales trends
Shipping preferences
Age group contribution

🚨 Key Business Problems Identified
.Weak customer acquisition funnel
.Poor subscription conversion strategy
.Over-reliance on discounts
.Massive seasonal revenue drop
.Underperforming product categories despite demand

💡 Strategic Recommendations
.Fix summer sales with targeted product & campaign strategy
.Convert repeat buyers into subscribers (low-hanging fruit)
.Introduce minimum threshold for free shipping
.Reduce discount dependency via pricing optimization
.Invest in customer acquisition campaigns
