# Athletic Sales Analysis

## Overview

This project analyzes sales data to gain insights into which cities in the U.S. have sold the most athletic wear over two years. It also determines which retailers had the greatest total sales for athletic wear and which retailers sold the most women's athletic footwear. Finally, it identifies the days and weeks with the highest sales for women's athletic footwear.

## Data
The analysis is based on sales data from two CSV files:
- `athletic_sales_2020.csv`
- `athletic_sales_2021.csv`

## Steps

1. **Combine and Clean the Data**
    - Imported the two CSV files and read them into DataFrames.
    - Checked for similar column names and data types.
    - Combined the DataFrames by rows and reset the index.
    - Checked for null values and converted the `invoice_date` column to datetime.

2. **Analysis**
    - Determined which regions, states, and cities sold the most products using groupby and pivot_table.
    - Determined which regions, states, and cities generated the most sales.
    - Identified the top retailers by sales and those selling the most women's athletic footwear.
    - Analyzed sales data to find the days and weeks with the highest sales for women's athletic footwear.

## Results

- **Top Regions by Products Sold:** A table showing the top 5 regions, states, and cities with the highest number of products sold.
- **Top Regions by Sales:** A table showing the top 5 regions, states, and cities with the highest sales.
- **Top Retailers by Sales:** A table showing the top 5 retailers along with their regions, states, and cities with the highest sales.
- **Top Retailers for Women's Athletic Footwear:** A table showing the top 5 retailers for women's athletic footwear.
- **Top Days for Women's Athletic Footwear Sales:** A table showing the top 10 days with the highest sales.
- **Top Weeks for Women's Athletic Footwear Sales:** A table showing the top 10 weeks with the highest sales.# athletic_sales_analysis
