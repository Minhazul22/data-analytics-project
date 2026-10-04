# Retail Orders Data Analysis

## Project Overview

This project analyzes retail order data to understand sales, profitability, and product performance.

The project covers the complete data analytics workflow:

- Data loading
- Data exploration
- Data cleaning and transformation
- PostgreSQL database integration
- SQL business analysis
- Business insights

## Dataset

The project uses a retail orders dataset containing information about:

- Orders
- Customers and segments
- Shipping modes
- Locations
- Product categories and sub-categories
- Product IDs
- Quantity
- Pricing
- Discounts
- Profit

The dataset contains **9,994 orders**.

## Tools & Technologies

- Python
- Pandas
- PostgreSQL
- SQLAlchemy
- Jupyter Notebook
- Git & GitHub

## Project Workflow

### 1. Data Exploration

The raw dataset was inspected to understand:

- Dataset structure
- Data types
- Missing values
- Shipping modes
- Summary statistics

### 2. Data Cleaning

The data was cleaned and transformed by:

- Standardizing column names
- Handling missing shipping mode values
- Converting order dates to datetime
- Calculating discount amounts
- Calculating sale price
- Calculating profit
- Removing unused source pricing columns

### 3. PostgreSQL Integration

The cleaned dataset was loaded into PostgreSQL in the `retail_orders` database.

The resulting table is:

```text
df_orders