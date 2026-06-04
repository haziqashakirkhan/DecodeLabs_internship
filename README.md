#  Online Store Orders Dataset – Data Science Internship Project

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-EDA-orange?logo=pandas)
![Status](https://img.shields.io/badge/Project-Completed-green)
![Type](https://img.shields.io/badge/Analysis-Data%20Science-purple)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

## Overview

This project presents a comprehensive analysis of an Online Store Orders dataset as part of a Data Science Internship. The objective was to transform raw transactional data into actionable business insights through data cleaning, exploratory data analysis (EDA), and visualization techniques.

The project demonstrates practical skills in data preprocessing, statistical analysis, and data storytelling using Python and industry-standard data science libraries.

---

## Project Objectives

- Understand the structure and quality of the dataset.
- Clean and preprocess raw transactional data.
- Perform exploratory data analysis (EDA).
- Identify sales trends and customer purchasing patterns.
- Analyze product performance and revenue contribution.
- Create informative visualizations to support business decision-making.

---

## Dataset Description

The dataset contains records of customer purchases made through an online store.

### Features

| Feature | Description |
|----------|------------|
| OrderID | Unique identifier for each order |
| Date | Date of transaction |
| CustomerID | Unique customer identifier |
| Product | Product purchased |
| Quantity | Number of units ordered |
| UnitPrice | Price per unit |
| TotalPrice | Total revenue generated from an order |

---

## Data Preprocessing

To ensure data quality and reliability, the following preprocessing steps were performed:

- Inspected dataset structure and data types
- Checked for missing values and inconsistencies
- Removed duplicate records
- Converted date columns into appropriate datetime formats
- Created derived features such as Total Revenue
- Validated numerical and categorical data for analysis

---

## Exploratory Data Analysis

The analysis focused on answering key business questions:

### Sales Performance
- What products generate the highest revenue?
- Which products are purchased most frequently?

### Customer Insights
- Who are the highest-value customers?
- How do purchasing patterns vary among customers?

### Revenue Analysis
- How is revenue distributed across products?
- What factors contribute most to total sales?

### Trend Analysis
- How do sales fluctuate over time?
- Are there observable growth or decline patterns?

---

## Visualizations

The project includes various visualizations to communicate findings effectively:

- Product Sales Analysis
- Revenue Distribution
- Sales Trends Over Time
- Quantity Distribution
- Correlation Heatmap
- Customer Purchase Analysis

### Top Selling Products
![Top Products](visuals/top_products.png)

### Sales Trend Analysis
![Sales Trend](visuals/sales_trend.png)

### Revenue Distribution
![Revenue Distribution](visuals/revenue_distribution.png)

### Correlation Heatmap
![Heatmap](visuals/heatmap.png)

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Structure

```text
online-store-orders-analysis/
│
├── data/
│   └── Online-Store-Orders.xlsx
│
├── notebooks/
│   └── Online_Store_Analysis.ipynb
│
├── visuals/
│   ├── sales_trend.png
│   ├── top_products.png
│   ├── revenue_distribution.png
│   └── heatmap.png
│
├── README.md
└── requirements.txt
```

---

## Key Findings

- A small number of products contribute significantly to overall revenue.
- Customer purchasing behavior varies considerably across the dataset.
- Revenue is strongly influenced by both product pricing and order quantity.
- Visual analysis reveals meaningful sales patterns that can support business decisions.
- Certain products consistently outperform others in terms of sales and revenue generation.

---

## Skills Demonstrated

- Data Cleaning and Preparation
- Exploratory Data Analysis (EDA)
- Data Visualization
- Business Insight Generation
- Statistical Interpretation
- Python Programming

---

## Future Enhancements

Potential improvements for this project include:

- Customer Segmentation using Clustering Techniques
- Sales Forecasting and Time-Series Analysis
- Interactive Dashboard Development using Power BI or Tableau
- Deployment of Insights through Web Applications

---

## Conclusion

This project highlights the importance of data analysis in understanding customer behavior and business performance. Through structured data exploration and visualization, valuable insights were extracted from raw transactional data, demonstrating practical data science skills applicable to real-world business scenarios.

---

## Author

**Haziqa Shakir**  
Data Science Student | Python & Data Analytics Enthusiast

This project was completed as part of a Data Science Internship to strengthen practical skills in data analysis, visualization, and business intelligence.
