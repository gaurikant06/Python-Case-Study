# Online Retail Sales Analysis

## Dataset
Online retail sales dataset.

## Tools
- Python
- Pandas
- NumPy

## Assignment Tasks
## 1. Data Exploration and Cleaning
- Load the dataset into a Pandas DataFrame and display the first 5 rows.
- Check the dataset shape, column names, data types, and summary statistics.
- Identify missing values in each column.
- Handle missing values appropriately:
    - Numerical columns: fill with mean or median.
    - Categorical columns: fill with mode or drop.
- Convert Order_Date into datetime format.
- Extract Year, Month, and Day from Order_Date into new columns.

## 2. Data Selection and Filtering
- Retrieve all orders placed in March 2024.
- Find all orders where:
    - Total_Amount > 1000
    -.Category is Electronics.
- Select only Completed orders.
- Retrieve orders placed from Mumbai or Delhi.
