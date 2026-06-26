# Online Retail Sales Data Analysis Assignment

## 📌 Assignment Overview

This project performs **data cleaning, preprocessing, analysis, feature engineering, aggregation, customer behavior analysis, anomaly detection, and data merging** using **Python, Pandas, and Matplotlib**.

---

# Assignment Tasks

## 1️⃣ Data Exploration and Cleaning

- Load the dataset into a Pandas DataFrame and display the first 5 rows.
- Check the dataset shape, column names, data types, and summary statistics.
- Identify missing values in each column.
- Handle missing values appropriately:
  - Numerical columns: Fill with Mean or Median.
  - Categorical columns: Fill with Mode or Drop missing values.
- Convert `Order_Date` into Datetime format.
- Extract:
  - Year
  - Month
  - Day
  into new columns.

---

## 2️⃣ Data Selection and Filtering

Retrieve:

- Orders placed in **March 2024**
- Orders where:
  - Total_Amount > 1000
  - Category = Electronics
- Completed Orders only
- Orders placed from:
  - Mumbai
  - Delhi

---

## 3️⃣ Data Manipulation and Feature Engineering

Create a new column:

### Discounted_Amount

- Apply **10% discount** where:
  - Total_Amount > 800

Create another column:

### Price_Level

| Total Amount | Price Level |
|--------------|-------------|
| Below 200 | Low |
| 200–800 | Medium |
| Above 800 | High |

Create:

### Revenue_Per_Item

Revenue_Per_Item = Total_Amount / Quantity

Drop the **Product** column if more than **40%** values are missing.

---

## 4️⃣ Aggregation and Business Insights

Find:

- Total Revenue per Category
- Average Order Value per Payment Method
- Top 5 Cities by Total Sales
- Number of Cancelled and Returned Orders per Category
- Monthly Sales Trend

---

## 5️⃣ Customer Behavior Analysis

Identify:

- Customers who placed more than **5 orders** in a single month
- Customers whose Average Order Value exceeds **1500**
- Customers who placed orders from **multiple cities**
- Repeat customers with more than one order

---

## 6️⃣ Anomaly and Risk Indicators

Identify:

- Orders where:
  - Quantity > 20
  - Total_Amount < 100
- Returned Orders where Total_Amount > 2000
- Customers who placed multiple orders on the same day

---

## 7️⃣ Data Merging and Joining

### Customer Details Dataset

Merge **online_retail_sales.csv** with **customer_details.csv** using **Customer_ID**.

### Customer Details Columns

| Column Name | Description |
|--------------|-------------|
| Customer_ID | Unique Customer Identifier |
| Age | Customer Age |
| Gender | Male or Female |
| Membership_Level | Silver, Gold, Platinum |

### Tasks

- Merge both datasets using Customer_ID.
- Find Average Order Value by Membership Level.
- Identify the Membership Group generating the Highest Revenue.
- Analyze Purchasing Behavior by Age Group.

---

#  Bonus Tasks

- Visualize Monthly Revenue using a Line Chart.
- Create a Bar Chart for Revenue by Category.
- Plot Top 10 Customers by Total Spending.

---

#  Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib

---

#  Dataset Files

- online_retail_sales.csv
- customer_details.csv

---

# 🚀 Learning Outcomes

By completing this assignment, you will learn:

- Data Cleaning
- Data Filtering
- Feature Engineering
- Aggregation
- Customer Analysis
- Data Merging
- Business Insights
- Data Visualization using Matplotlib

---
