# customer_behavior_analysis
Data analytics project showcasing customer behavior analysis using Python, SQL, and PowerBI.

Customer Shopping Behavior Analysis
This project analyzes customer shopping behavior using a dataset of 3,900 purchases. The goal is to understand spending patterns, product preferences, customer segments, and subscription behavior. I used Python for data cleaning and feature engineering, PostgreSQL for deeper analysis, and Power BI to build an interactive dashboard.

Project Summary
The dataset includes customer demographics, purchase details, review ratings, shipping types, and shopping behavior. After loading the data in Python, I cleaned missing values, standardized column names, created new features like age groups, and checked for redundant fields. The cleaned data was then loaded into PostgreSQL for SQL analysis.

Python Work
I explored the dataset using pandas, handled missing review ratings by filling them with the median rating per product category, and created new columns to help with segmentation. I also connected Python to PostgreSQL using SQLAlchemy to store the cleaned data for further analysis.

SQL Analysis
I used SQL to answer business questions such as:

Revenue differences between male and female customers

High‑spending customers who still used discounts

Top‑rated products

Average spending by shipping type

Subscriber vs. non‑subscriber spending

Products most often bought with discounts

Customer segmentation into new, returning, and loyal groups

Top products in each category

Whether repeat buyers are more likely to subscribe

Revenue contribution by age group

These queries helped reveal patterns in customer behavior and product performance.

Power BI Dashboard
I built a dashboard to visualize the insights. It includes:

Subscription status breakdown

Revenue and sales by category

Customer demographics

Shipping type preferences

Revenue and sales by age group

Product category performance

The dashboard ties together the Python and SQL work into a clear visual summary.

Key Insights
Non‑subscribers generate more total revenue because they make up most of the customer base

Young adults contribute the highest revenue

Certain products rely heavily on discounts

Express shipping users spend slightly more

Loyal customers make up the largest segment

Recommendations
Promote subscription benefits to increase conversions

Strengthen loyalty programs

Adjust discount strategies for margin‑heavy products

Highlight top‑rated products in marketing

Target high‑value age groups with personalized offers

Tools Used
Python (pandas), PostgreSQL, SQLAlchemy, Jupyter Notebook, Power BI.
