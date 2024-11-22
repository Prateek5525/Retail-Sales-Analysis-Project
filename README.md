# Retail Sales Analysis Project

## Project Overview

This project involves analyzing retail sales data using SQL to uncover insights into sales patterns, customer behavior, and product performance. It serves as an introductory exercise to develop foundational SQL skills in data exploration, cleaning, and analysis.

- **Title:** Retail Sales Analysis
- **Database:** `p1_retail_db`

The project includes setting up a retail sales database, performing data cleaning, and conducting exploratory data analysis (EDA) to answer key business questions through SQL queries.

## Objectives

1. **Database Setup:** Create and populate a retail sales database.
2. **Data Cleaning:** Identify and eliminate records with missing values.
3. **Exploratory Data Analysis:** Summarize data to understand key characteristics.
4. **Business Analysis:** Use SQL to derive insights and answer business-related questions.

## Project Structure

### Database Setup

- Created the database `p1_retail_db` and a table `retail_sales` with relevant columns, including:
  - Transaction ID
  - Sale Date
  - Customer ID
  - Gender
  - Age
  - Product Category
  - Quantity
  - Price per Unit
  - COGS (Cost of Goods Sold)
  - Total Sale Amount

### Data Exploration & Cleaning

- Counted total records and unique customers.
- Identified unique product categories and checked for missing values.

### Data Analysis & Findings

- Analyzed sales by date, high-quantity transactions, total sales per category, customer demographics, monthly sales trends, and top customers based on spending.

## Key Findings

- **Diverse Customer Demographics:** The dataset includes a wide range of age groups, with significant purchases in categories like Clothing and Beauty.
- **High-Value Transactions:** Notable transactions exceeding $1000 highlight premium sales.
- **Sales Trends:** Analysis reveals peak sales periods by month and time.
- **Customer Insights:** Identification of top-spending customers and popular product categories.

## Conclusion

This project demonstrates essential SQL skills for data analysis, including database setup, data cleaning, EDA, and deriving insights from data. The findings can inform business decisions by enhancing understanding of customer behavior and sales dynamics.

## How to Use

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Prateek5525/Retail-Sales-Analysis-Project.git
   cd retail-sales-analysis-project

2. **Set Up the Database:**
    Follow the SQL commands in the README or setup script to create and populate the database.
   
4. **Run the Queries:**
    Execute the SQL queries provided to explore the data.
   
5. **Explore and Modify:**
    Feel free to adjust the SQL queries to investigate specific aspects of the dataset or address additional questions.
