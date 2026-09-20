# Task 5 – KPI Reporting

## Overview

This project was completed as part of the CodeOrbit Tech Data Analyst Internship – Batch IND1.

The objective of this task was to create a KPI report that summarizes overall e-commerce sales performance using key business metrics.

## Objective

The main objectives of this task were to:

- Calculate important sales KPIs
- Present KPI values clearly in Excel
- Identify top-performing category, region, and product
- Validate KPI calculations against the original dataset
- Provide a concise interpretation of business performance

## Tools Used

- Neat Office Spreadsheet
- Excel-compatible `.xlsx` format
- E-commerce sales dataset from previous internship tasks

## Dataset

The KPI report was created using the cleaned e-commerce sales dataset prepared during Task 1.

The dataset contains:

- 19 orders
- 43 units sold
- Sales transactions across multiple products, categories, and regions
- Revenue calculated from quantity and unit price

## KPIs Reported

| KPI | Value |
|---|---:|
| Total Revenue | ₹395,700 |
| Total Orders | 19 |
| Total Quantity Sold | 43 |
| Average Order Value | ₹20,826.32 |

## Performance Metrics

| Metric | Result |
|---|---|
| Top Revenue Category | Electronics |
| Top Revenue Region | South |
| Top Revenue Product | Laptop |
| Uncategorized Revenue | ₹3,600 |

## KPI Calculations

### Total Revenue

Calculated by summing the revenue column:

`=SUM(cleaned_ecommerce_sales.I2:I20)`

### Total Orders

Calculated by counting the order IDs:

`=COUNTA(cleaned_ecommerce_sales.A2:A20)`

### Total Quantity Sold

Calculated by summing the quantity column:

`=SUM(cleaned_ecommerce_sales.E2:E20)`

### Average Order Value

Calculated using total revenue divided by total orders:

`=B5/B6`

## KPI Interpretation

- Total revenue generated from the dataset was ₹395,700.
- The dataset contains 19 orders.
- Total quantity sold was 43 units.
- Average revenue per order was approximately ₹20,826.32.
- Electronics was the highest-revenue category.
- South was the highest-revenue region.
- Laptop generated the highest product revenue.
- ₹3,600 of revenue was associated with Uncategorized products, indicating that some records may benefit from improved category classification.

## Validation

The KPI calculations were checked against the source dataset.

Validation checks confirmed that:

- Total revenue matches the dataset revenue total.
- Total orders match the number of order records.
- Total quantity matches the dataset quantity total.
- Average Order Value is calculated from the validated revenue and order count.
- Performance metrics are consistent with the sales and pivot-table analyses from previous tasks.

**Validation Status: All KPI calculations verified ✅**

## Project File

The completed workbook is:

`Task5_KPI_Report.xlsx`

The workbook contains the `KPI_Report` sheet with:

- KPI summary table
- Performance metrics
- KPI interpretation
- Validation status
- Conclusion

## Conclusion

The KPI report provides a concise summary of the e-commerce dataset's overall sales performance. It combines key numerical indicators with performance metrics to make the sales results easier to understand and communicate for business reporting.

## Internship Details

**Organization:** CodeOrbit Tech  
**Program:** Data Analyst Internship  
**Batch:** IND1  
**Task:** Task 5 – KPI Reporting  
**Author:** Kethana Sai Pranavi Atmuri
