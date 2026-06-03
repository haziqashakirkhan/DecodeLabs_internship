# 🛒 Online Store Orders Dataset – Data Science Internship Project

## 📌 Project Overview
This project is part of a Data Science internship task focused on analyzing an **Online Store Orders Dataset** using Python.  
The main goal is to perform **data cleaning, exploratory data analysis (EDA), and data visualization** to extract meaningful business insights from the dataset.

No machine learning model was trained due to low performance caused by limited feature quality and dataset constraints. Instead, the focus was kept on **strong EDA and business insights**.

---

## 📂 Dataset Information

The dataset contains online store transaction records.

### 🔑 Key Features:
- **OrderID** → Unique identifier for each order  
- **Date** → Date of purchase  
- **CustomerID** → Unique customer identifier  
- **Product** → Name of purchased product  
- **Quantity** → Number of units ordered  
- **UnitPrice** → Price per unit  
- **TotalPrice** → Total order value (calculated feature)

---

## 🎯 Project Objectives

- Load and understand the dataset  
- Clean and preprocess raw data  
- Handle missing values and duplicates  
- Perform exploratory data analysis (EDA)  
- Identify sales patterns and customer behavior  
- Discover top-performing products  
- Visualize key business insights  

---

## 🧹 Data Cleaning & Preprocessing

The following steps were performed:

- Checked and handled missing values using `isnull().sum()`  
- Removed duplicate entries  
- Converted **Date** column to datetime format  
- Created a new feature: **TotalPrice = Quantity × UnitPrice**  
- Ensured correct data types for analysis  
- Prepared data for visualization  

---

## 📊 Exploratory Data Analysis (EDA)

The dataset was analyzed to answer important business questions:

- Which products generate the highest revenue?  
- What are the top-selling products?  
- How do sales vary over time?  
- Which customers contribute the most revenue?  
- What is the relationship between quantity and total sales?  

---

## 📈 Data Visualizations

The following visualizations were used:

- 📊 Bar charts → Top-selling products  
- 📈 Line plots → Sales trends over time  
- 📦 Histograms → Distribution of quantity and price  
- 🔥 Heatmaps → Correlation between numerical features  
- 🥧 Pie charts → Product distribution  

These visualizations helped in understanding customer behavior and sales performance.

---

## 🛠️ Technologies Used

- Python 🐍  
- Pandas – Data manipulation  
- NumPy – Numerical operations  
- Matplotlib – Data visualization  
- Seaborn – Statistical visualization  

---

## 📁 Project Structure

