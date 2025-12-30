# Customer_Behaviour_Analysis
Customer Shopping Behavior Analysis

Overview

This project focuses on analyzing customer shopping behavior using transactional retail data. It demonstrates an end-to-end data analytics workflow, starting from data loading and cleaning in Python, moving through SQL-based business analysis, and ending with insights presented via Power BI dashboards and PowerPoint reports.

The goal is to extract actionable insights related to customer behavior, product performance, discounts, subscriptions, and revenue trends to support data-driven decision making.

Note: This project was tutored and presented step-by-step by @amlanmohanty1 using his YouTube tutorial:
https://youtu.be/5PrZvPeUw60?si=bgiyiMJKlE_yos_4

Dataset

Records: 3,900 transactions

Features: 18 columns

Data includes:
Customer demographics (Age, Gender, Location, Subscription Status)
Purchase details (Product, Category, Amount, Season, Size, Color)
Shopping behavior (Discount usage, Purchase frequency, Review rating, Shipping type)
Data Quality: Minor missing values handled during preprocessing
Tools & Technologies
Python (Pandas, NumPy, Matplotlib/Seaborn)
SQL (PostgreSQL / MySQL / SQL Server)
Power BI
PowerPoint
Git & GitHub
Project Workflow / Steps
Data Loading
Imported dataset into Python using Pandas
Exploratory Data Analysis (EDA)
Summary statistics
Distribution analysis
Customer and product trends
Data Cleaning & Preparation
Handled missing values
Standardized column names
Removed redundant features
Feature engineering (age groups, purchase frequency, customer segments)
SQL Analysis
Loaded cleaned data into relational databases
Ran SQL queries to analyze:
Revenue by demographics
Subscription vs non-subscription behavior
Discount impact
Top products and categories
Customer segmentation
Dashboard Development
Built an interactive Power BI dashboard for business insights
Reporting & Presentation
Created a structured analytics report
Designed a PowerPoint presentation summarizing insights and recommendations
Dashboard
The Power BI dashboard provides:
Revenue and sales trends
Customer segmentation analysis
Product and category performance
Subscription and discount insights
It allows interactive filtering by demographics, category, and behavior metrics.
Key Results & Insights
Subscribers generate higher average revenue than non-subscribers
Loyal customers are more likely to subscribe
Some high-value customers still purchase despite discounts
Certain products are highly discount-dependent
Specific age groups contribute most to total revenue
How to Run This Project
Clone the repository:
git clone https://github.com/Kegoikantse-Nthathe/Customer_Behaviour_Analysis
Open and run the Python notebook/script for:
Data loading
EDA
Data cleaning
Load the cleaned dataset into:
PostgreSQL / MySQL / SQL Server
Execute the provided SQL queries for analysis
Open the Power BI file (.pbix) to explore the dashboard
Review the PowerPoint presentation and report for summarized insights
Acknowledgment
This project was guided, tutored, and presented step-by-step by @amlanmohanty1 through his YouTube tutorial. The project structure and learning approach closely follow his instructional content.
