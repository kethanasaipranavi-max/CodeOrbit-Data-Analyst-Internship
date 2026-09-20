# Task 2 — Sales Data Analysis with Pandas

## 📌 Project Overview

This project is part of the **CodeOrbit Tech Data Analyst Internship**.

The objective of this task is to analyze cleaned e-commerce sales data using **Python and Pandas** and generate meaningful sales metrics, category-level analysis, regional analysis, product performance analysis, and monthly sales trends.

The cleaned dataset from **Task 1 — Data Cleaning** is used as the input for this analysis.

---

## 🎯 Objectives

The main objectives of this project are to:

- Calculate key sales metrics
- Analyze revenue by category
- Analyze revenue by region
- Analyze product performance
- Identify the top-performing products by revenue
- Analyze monthly sales trends
- Create visualizations to communicate sales performance
- Export analytical summary tables for further use

---

## 🛠️ Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- GitHub

---

## 📊 Dataset

The analysis uses the cleaned e-commerce sales dataset generated during Task 1.

The dataset contains information including:

- Order ID
- Customer Name
- Product
- Category
- Quantity
- Unit Price
- Order Date
- Region
- Revenue

Revenue was calculated during Task 1 using:

```text
Revenue = Quantity × Unit Price
```

---

## 📈 Key Sales Metrics

The analysis calculates the following metrics:

- Total Revenue
- Total Quantity Sold
- Total Number of Orders
- Average Order Value

Average Order Value is calculated as:

```text
Average Order Value = Total Revenue ÷ Number of Orders
```

---

## 🔎 Analysis Performed

### 1. Category Analysis

Sales data is grouped by category to calculate:

- Total Revenue
- Total Quantity
- Number of Orders

Categories are then sorted by total revenue.

### 2. Regional Analysis

Sales data is grouped by region to identify differences in:

- Revenue
- Quantity Sold
- Number of Orders

### 3. Product Analysis

Products are analyzed based on:

- Total Revenue
- Total Quantity
- Number of Orders

The top five products by revenue are also identified.

### 4. Monthly Sales Analysis

Order dates are converted to monthly periods and used to calculate:

- Monthly Revenue
- Monthly Quantity
- Monthly Number of Orders

This provides a basic view of sales trends over time.

---

## 📊 Visualizations

The project includes visualizations for:

- Monthly Revenue
- Revenue by Category
- Revenue by Region
- Top 5 Products by Revenue

These visualizations help communicate sales performance in a simple and understandable way.

---

## 📁 Project Files

```text
Task-2-Sales-Analysis/
│
├── task2_sales_analysis.ipynb
├── category_sales_analysis.csv
├── region_sales_analysis.csv
├── product_sales_analysis.csv
├── monthly_sales_analysis.csv
├── sales_analysis_summary.csv
└── README.md
```

### `task2_sales_analysis.ipynb`

Contains the complete Python analysis workflow.

### `category_sales_analysis.csv`

Contains sales metrics grouped by category.

### `region_sales_analysis.csv`

Contains sales metrics grouped by region.

### `product_sales_analysis.csv`

Contains sales metrics grouped by product.

### `monthly_sales_analysis.csv`

Contains monthly sales metrics.

### `sales_analysis_summary.csv`

Contains the main sales KPI summary.

---

## ✅ Validation

Automated checks were performed to verify that:

- Revenue values are available
- Revenue values are positive
- Total revenue is positive
- Total quantity sold is positive
- At least one order exists

The notebook displays:

```text
✅ ALL SALES ANALYSIS VALIDATION TESTS PASSED!
```

when the validation conditions are satisfied.

---

## 💡 Business Analysis

The analysis provides a foundation for understanding:

- Overall sales performance
- Product-level revenue contribution
- Category-level performance
- Regional sales distribution
- Monthly sales patterns

These results can be used as inputs for future KPI reporting, dashboard development, and business-insight analysis.

---

## 👩‍💻 Author

**Kethana Sai Pranavi Atmuri**

Data Analyst Intern  
CodeOrbit Tech — Batch IND1

---

## 📌 Internship

This project was completed as **Task 2 — Sales Data Analysis with Pandas** as part of the **CodeOrbit Tech Data Analyst Internship**.
