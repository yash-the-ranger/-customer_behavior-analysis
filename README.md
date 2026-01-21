# -customer_behavior-analysis
customer behavior analysis project using python , sql , power bi 
Customer Shopping Behavior Analysis
Overview

This project analyzes customer shopping behavior using transactional retail data to uncover insights into spending patterns, customer segments, product performance, and subscription behavior. The objective is to transform raw transaction data into actionable business insights that support strategic decision-making in areas such as marketing, pricing, customer retention, and product positioning.

The analysis follows an end-to-end data analytics workflow, covering data preparation in Python, structured analysis using SQL, and interactive visualization through Power BI.

Business Objectives

Understand customer spending behavior across demographics and product categories

Evaluate the impact of subscriptions, discounts, and shipping types on revenue

Identify high-value customer segments and repeat buyers

Support data-driven recommendations for improving revenue and customer retention

Dataset Description

Total Records: 3,900 transactions

Total Features: 18 columns

Key Feature Groups

Customer Demographics: Age, Gender, Location, Subscription Status

Purchase Details: Item Purchased, Category, Purchase Amount, Season, Size, Color

Shopping Behavior: Discount Applied, Promo Code Used, Previous Purchases, Purchase Frequency, Review Rating, Shipping Type

Data Quality Notes

37 missing values identified in the Review Rating column

Missing values were imputed using category-wise median ratings

Redundant columns were identified and removed to ensure consistency

Tools & Technologies

Python: Data cleaning, preprocessing, feature engineering

SQL (PostgreSQL): Business-driven analytical queries

Power BI: Interactive dashboards and data visualization

Data Preparation & Feature Engineering

The dataset was prepared using Python with the following steps:

Data loading and structural validation

Missing value analysis and imputation

Column standardization for readability

Feature engineering:

age_group derived from customer age

purchase_frequency_days derived from purchase behavior

Removal of redundant features (promo_code_used)

Integration with PostgreSQL for SQL-based analysis

Analytical Approach (SQL)

Key business questions were addressed using SQL queries, including:

Revenue contribution by gender

Spending behavior of discount users

Subscription vs. non-subscription revenue comparison

Identification of top-rated and most-purchased products

Discount-dependent product analysis

Customer segmentation into New, Returning, and Loyal groups

Revenue contribution by age group

Analysis of repeat buyers and subscription likelihood

Dashboard & Visualization

An interactive Power BI dashboard was developed to present insights in a business-friendly format, including:

KPI cards for customer count, average purchase value, and ratings

Revenue breakdown by product category and age group

Subscription distribution and customer segmentation views

Filters for dynamic exploration of customer behavior

Key Insights

Male customers generated significantly higher total revenue than female customers

Non-subscribers contributed the majority of total revenue despite similar average spend

Certain products showed strong dependency on discounts for sales volume

Express shipping users spent more on average than standard shipping users

A large portion of customers belonged to the loyal segment, indicating strong repeat behavior

Business Recommendations

Promote subscription benefits to convert high-value non-subscribers

Strengthen loyalty programs for repeat buyers

Optimize discount strategies to balance revenue growth and margins

Highlight top-rated and high-performing products in marketing campaigns

Focus targeted marketing on high-revenue age groups and premium shipping users

Project Structure
Customer-Shopping-Behavior-Analysis/

│
├── data/                 # Raw and cleaned datasets
├── notebooks/            # Python data preparation and analysis
├── sql/                  # SQL queries used for analysis
├── dashboard/            # Power BI dashboard file
├── reports/              # Project summary and insights
└── README.md             # Project documentation

Future Enhancements

Add time-series analysis for seasonal and monthly trends

Introduce predictive modeling for subscription or churn likelihood

Enhance Power BI dashboard with drill-through and tooltip insights

Quantify business impact of recommendations through scenario analysis

Author

Yash
Aspiring Data Analyst | Python | SQL | Power BI
