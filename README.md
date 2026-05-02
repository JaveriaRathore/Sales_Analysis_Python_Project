# Sales Analysis Python Project

This project focuses on analyzing 12 months of sales data using Python and Jupyter Notebook to discover important business insights and improve decision-making.

The dataset contains customer orders, product details, purchase addresses, quantities, prices, and order dates. The project includes data cleaning, data transformation, visualization, and sales performance analysis using Pandas and Matplotlib.

---

## Tools & Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib

---

## Project Workflow

### 1. Merging 12 Months of Sales Data

Combined 12 separate monthly CSV files into one complete dataset for full-year analysis.

### 2. Data Cleaning

Performed data preprocessing by:

- Removing missing (NaN) rows
- Deleting invalid rows containing text errors like "Or"
- Converting columns into correct numeric data types

### 3. Feature Engineering

Created new useful columns such as:

- Month
- Sales (Quantity Ordered × Price Each)
- City
- Hour
- Minute

These columns helped in deeper business analysis.

---

## Business Questions Solved

### Question 1: What was the best month for sales?

Analyzed monthly sales performance to identify which month generated the highest revenue.

### Question 2: Which city had the highest sales?

Compared city-wise sales to determine the top-performing sales location.

### Question 3: What time should advertisements be displayed?

Used hourly order trends to find the best time for running advertisements to increase customer purchases.

### Question 4: Which products are most often sold together?

Identified product combinations frequently bought together using Order ID duplication analysis.

### Question 5: Which product sold the most?

Analyzed product-wise quantity sold and compared it with product prices to understand customer buying behavior.

---

## Key Insights

- Highest revenue-generating month identified
- Best-performing city discovered
- Peak customer buying hours found
- Most commonly purchased product combinations extracted
- Top-selling products analyzed with pricing comparison

---

## Project Files

- `sales_analysis.ipynb` → Main Jupyter Notebook
- `all_data.csv` → Combined dataset
- `Sales_Data/` → Original monthly sales CSV files
- `README.md` → Project documentation

---

## Conclusion

This project demonstrates practical data analysis skills including data cleaning, exploratory data analysis (EDA), visualization, and business insight generation using real-world sales data.

It is a strong beginner-to-intermediate level data analytics project suitable for GitHub portfolio, resume, internships, and job applications.
