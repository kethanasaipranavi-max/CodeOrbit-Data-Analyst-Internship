# Task 4 – Pivot Table Analysis

## Overview

This project was completed as part of the CodeOrbit Tech Data Analyst Internship (Batch IND1).

The objective of this task was to analyze e-commerce sales data using Pivot Tables and summarize important business findings.

## Objective

- Analyze revenue by category
- Analyze revenue by region
- Analyze quantity sold by category
- Analyze revenue by product
- Validate Pivot Table totals against the source dataset
- Document key business insights

## Tools Used

- Neat Office Calc
- Pivot Tables
- E-commerce sales dataset

## Dataset

The dataset contains 19 e-commerce sales transactions with information including:

- Order ID
- Customer Name
- Product
- Category
- Quantity
- Unit Price
- Order Date
- Region
- Revenue

## Pivot Tables Created

### 1. Revenue by Category

| Category | Revenue |
|---|---:|
| Electronics | ₹358,100 |
| Furniture | ₹34,000 |
| Uncategorized | ₹3,600 |
| **Total** | **₹395,700** |

### 2. Revenue by Region

| Region | Revenue |
|---|---:|
| East | ₹21,000 |
| North | ₹82,000 |
| South | ₹258,700 |
| West | ₹34,000 |
| **Total** | **₹395,700** |

### 3. Quantity Sold by Category

| Category | Quantity |
|---|---:|
| Electronics | 34 |
| Furniture | 7 |
| Uncategorized | 2 |
| **Total** | **43** |

### 4. Revenue by Product

| Product | Revenue |
|---|---:|
| Laptop | ₹227,000 |
| Monitor | ₹75,000 |
| Office Chair | ₹34,000 |
| Headphones | ₹31,500 |
| Keyboard | ₹16,200 |
| Wireless Mouse | ₹12,000 |
| **Total** | **₹395,700** |

## Key Business Insights

1. Total revenue was ₹395,700 from 19 orders and 43 units sold.

2. Electronics generated ₹358,100 in revenue, making it the largest category by revenue in this dataset.

3. South generated ₹258,700 in revenue, followed by North with ₹82,000.

4. Laptop generated the highest product revenue at ₹227,000.

5. Keyboard generated ₹16,200 in revenue, while Wireless Mouse generated ₹12,000.

6. Uncategorized products contributed ₹3,600 in revenue. Improving category classification could make future analysis more consistent.

## Validation

The Pivot Tables were checked against the source dataset.

- Category revenue total = ₹395,700
- Region revenue total = ₹395,700
- Product revenue total = ₹395,700
- Category quantity total = 43
- Number of orders = 19

All Pivot Table revenue totals reconcile with the overall dataset revenue.

## Workbook Structure

The Excel workbook contains:

- `cleaned_ecommerce_sales` – source data
- `Pivot_Category` – revenue by category
- `Pivot_Region` – revenue by region
- `Pivot_Quantity_Category` – quantity by category
- `Pivot_Product_Revenue` – revenue by product
- `Dashboard` – previous dashboard from Task 3
- `Task4_Insights` – Task 4 business insights and validation

## Project File

`Task4_Pivot_Table_Analysis.xlsx`

## Conclusion

The Pivot Table analysis provides a structured view of sales performance across categories, regions, products, and quantities. The analysis also validates that the summarized Pivot Table values reconcile with the source dataset totals.

## Author

Kethana Sai Pranavi Atmuri

**CodeOrbit Tech Data Analyst Internship – Batch IND1**
