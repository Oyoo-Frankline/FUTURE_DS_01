Business Sales Performance Dashboard
Project Overview

This project was completed as part of the Future Interns Data Science & Analytics Internship (Task 1: Business Sales Performance Analytics).

The objective was to analyze retail sales transaction data to identify:

Revenue trends over time
Top-selling products
High-value product categories
Regional sales performance
Key business insights and recommendations

The project combines Python-based data cleaning and analysis with Power BI dashboard development to transform raw sales data into actionable business intelligence.

Business Problem

Businesses generate large volumes of sales data every day. However, without proper analysis, it becomes difficult to understand:

Which products generate the most revenue
Which markets perform best
How revenue changes over time
Where growth opportunities exist

This project aims to answer these questions through data-driven analysis and interactive visualizations.

Dataset

Dataset: Online Retail Dataset

The dataset contains transactional sales records including:

Invoice Number
Product Description
Quantity Sold
Unit Price
Invoice Date
Customer ID
Country

The data covers online retail transactions between December 2010 and December 2011.

Tools and Technologies
Python
Jupyter Notebook
Pandas
NumPy
Matplotlib
Seaborn
Power BI
GitHub
Data Cleaning Process

Several preprocessing steps were performed to ensure data quality:

Handling Missing Values
Removed records with missing product descriptions
Removed records with missing customer IDs
Removing Invalid Transactions
Removed returned items with negative quantities
Removed transactions with invalid prices
Feature Engineering

Created additional fields including:

Revenue = Quantity × Unit Price
Month
Year

These fields enabled trend analysis and dashboard reporting.

Exploratory Data Analysis

The analysis focused on four key business areas:

1. Revenue Trends

Monthly revenue was analyzed to identify:

Growth patterns
Seasonal fluctuations
Peak sales periods
2. Product Performance

Products were ranked based on:

Revenue generated
Quantity sold
3. Category Analysis

Products were grouped into business categories to identify:

High-value segments
Revenue contribution by category
4. Regional Performance

Sales performance was analyzed across countries to determine:

Top-performing markets
Geographic revenue distribution
Key Findings
Revenue Performance
Total Revenue: Approximately £10.67 Million
Strong growth observed during the final quarter of 2011
November recorded the highest monthly revenue
Product Insights

Top-performing products included:

REGENCY CAKESTAND 3 TIER
WHITE HANGING HEART T-LIGHT HOLDER
PARTY BUNTING
Geographic Insights

The majority of revenue originated from:

United Kingdom
Netherlands
Ireland
Germany
France
Customer Insights

A small group of customers contributed a significant share of total revenue, indicating opportunities for customer retention strategies.

Power BI Dashboard

The dashboard was designed to provide an executive-level overview of business performance.

Dashboard Features
KPI Cards
Total Revenue
Total Orders
Total Customers
Countries Served
Visualizations
Monthly Revenue Trend
Top Products by Revenue
Top Products by Quantity Sold
Revenue by Country
Country Filter (Slicer)
Business Recommendations

Based on the analysis:

Increase inventory levels before peak seasonal periods.
Expand marketing efforts in high-performing European markets.
Focus promotional campaigns on top-selling products.
Reduce over-reliance on the United Kingdom market by diversifying internationally.
Strengthen customer retention initiatives for high-value customers.

Dashboard Preview

images/<img width="670" height="368" alt="image" src="https://github.com/user-attachments/assets/3a38ab4a-a32c-4bd3-8310-cbb5a96e70c5" />


Conclusion

This project demonstrates the complete data analytics workflow, including data cleaning, exploratory data analysis, business insight generation, and dashboard development.

The analysis transformed raw transactional data into actionable business intelligence, enabling informed decision-making regarding product strategy, regional expansion, and revenue growth opportunities.

