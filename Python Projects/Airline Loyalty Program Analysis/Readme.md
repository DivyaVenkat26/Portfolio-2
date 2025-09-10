# Airline Loyalty Program Analysis
## Introduction

This project analyzes an airline’s loyalty program data to understand customer behavior, revenue contribution, and retention opportunities. By studying customer demographics, loyalty tiers, booking activity, and revenue patterns, the analysis helps airlines strengthen engagement and improve loyalty strategies.

The project uses:

SQL for data extraction and joining tables

Python (Pandas, Matplotlib, Seaborn) for data cleaning, transformation, and visualization

## Objectives

Connect SQL database and import airline loyalty data into Python

Clean and transform the dataset for consistency

Explore customer demographics, loyalty tiers, and booking behavior

Visualize revenue contribution and customer insights

Identify high-value segments and suggest strategies for retention

## Methodology

## Data Collection

Extracted data from a MySQL database using mysql.connector

Queried tables: calendar, customer_flight_activity, customer_loyalty_history

## Data Integration

Joined multiple SQL tables in Python using pd.read_sql()

Built a comprehensive dataset combining customer activity, loyalty, and calendar data

## Data Cleaning

Checked for consistency

Handled missing values and duplicates

Removed unnecessary spaces from column names

## Data Transformation

Created a calculated column:

Total Revenue = Miles Redeemed × Cost Per Mile

Converted data types using astype()

## Exploratory Data Analysis (EDA)

Customer distribution across loyalty tiers

Seasonal and monthly flight activity trends

Revenue contribution by loyalty tier

Top 10 customers by flights and revenue

Relationship between cancellations and points redeemed

## Key Insights

Peak Travel - Highest flight activity occurs in June, July, August, December, and May.

Revenue Contribution - Star tier generates the highest revenue, followed by Nova and Aurora.

Flight Frequency - Customers across all tiers take ~1.3 flights on average.

Cancellations - Aurora tier shows slightly higher cancellations, though differences are small.

Points Redemption - Active customers redeem more points per person, while cancelled customers redeem more overall.

Business Recommendation - Focus on retaining premium (Star) customers, as they are the biggest revenue drivers.

## Tools & Libraries

SQL (MySQL) - Data connection & queries

Python - Pandas, Matplotlib, Seaborn
