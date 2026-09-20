# Task 1 — E-Commerce Sales Data Cleaning Using Python

## 📌 Project Overview

This project is part of the **CodeOrbit Tech Data Analyst Internship**.

The objective of this task is to clean and prepare an e-commerce sales dataset using **Python and Pandas**. The raw dataset intentionally contains common data-quality issues that can occur in real-world business data.

The cleaning process identifies and resolves missing values, duplicate records, inconsistent formatting, invalid numeric values, and inconsistent date formats. A final validation process is performed to confirm that the cleaned dataset is ready for further analysis.

---

## 🎯 Objectives

The main objectives of this project are to:

- Inspect the raw dataset
- Identify missing values
- Detect duplicate records
- Remove duplicate records
- Standardize column names
- Remove unnecessary whitespace
- Standardize text formatting
- Handle missing customer and category information
- Identify and correct invalid quantities
- Identify and correct invalid product prices
- Standardize order dates
- Calculate revenue
- Perform automated data-quality validation
- Export the cleaned dataset as a CSV file

---

## 🛠️ Tools and Technologies

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Google Colab**
- **GitHub**

---

## 📊 Dataset

The project uses a small e-commerce sales dataset containing information about:

- Order ID
- Customer Name
- Product
- Category
- Quantity
- Unit Price
- Order Date
- Region

The sample dataset was designed to demonstrate common data-cleaning situations such as missing values, duplicate records, inconsistent formatting, invalid numeric values, and inconsistent date formats.

---

## 🔍 Data Quality Issues Identified

The raw dataset contains several intentional data-quality problems, including:

### 1. Missing Values

Missing values were identified in fields such as:

- Customer Name
- Category
- Quantity
- Unit Price
- Order Date

### 2. Duplicate Records

Duplicate order records were checked and removed from the dataset.

### 3. Inconsistent Text Formatting

Some text values contained:

- Leading or trailing spaces
- Different capitalization styles

These values were standardized to improve consistency.

### 4. Invalid Quantities

Non-positive quantities were treated as invalid.

Valid quantity values were used to calculate a median, which was then used to replace invalid or missing quantities.

### 5. Invalid Unit Prices

Non-positive unit prices were treated as invalid.

Missing or invalid prices were filled using the median price within the relevant product category where available. An overall valid-price median was used as a fallback.

### 6. Inconsistent Dates

Order dates were converted into a consistent datetime format. Invalid or missing dates were handled using the median of the valid dates.

---

## 🧹 Data Cleaning Process

The following workflow was implemented in Python:

1. Loaded the raw dataset into a Pandas DataFrame.
2. Inspected the dataset structure and data types.
3. Checked for missing values.
4. Visualized missing values using a heatmap.
5. Checked for duplicate records.
6. Removed duplicate records.
7. Standardized column names using lowercase and underscores.
8. Removed unnecessary whitespace from text fields.
9. Standardized text capitalization.
10. Replaced missing customer names with `Unknown`.
11. Replaced missing categories with `Uncategorized`.
12. Converted quantity and unit-price fields to numeric values.
13. Replaced invalid or missing quantities using the median valid quantity.
14. Replaced invalid or missing prices using category-level median values where possible.
15. Converted order dates to datetime format.
16. Filled missing dates using the median valid date.
17. Created a new `revenue` column.
18. Performed final data-quality validation.
19. Exported the cleaned dataset to CSV.

---

## 💰 Revenue Calculation

A new revenue column was created using:

```text
Revenue = Quantity × Unit Price
```

This prepares the dataset for future sales analysis and KPI calculations.

---

## ✅ Data Validation

After cleaning, automated validation tests were performed to verify that:

- Duplicate records were removed
- Customer names contain no missing values
- Categories contain no missing values
- Quantities contain no missing values
- Unit prices contain no missing values
- Order dates contain no missing values
- Quantities are greater than zero
- Unit prices are greater than zero
- Revenue values are available

The validation section uses Python assertions to automatically check these conditions.

When all checks pass, the notebook displays:

```text
✅ ALL DATA QUALITY TESTS PASSED!
```

---

## 📁 Project Files

```text
Task-1-Data-Cleaning/
│
├── task1_data_cleaning.ipynb
├── cleaned_ecommerce_sales.csv
└── README.md
```

### `task1_data_cleaning.ipynb`

Contains the complete Python data-cleaning workflow, including data inspection, cleaning, validation, and export.

### `cleaned_ecommerce_sales.csv`

Contains the final cleaned and analysis-ready dataset.

### `README.md`

Provides documentation about the project, methodology, and results.

---

## 📈 Outcome

The raw e-commerce dataset was transformed into a cleaner and more consistent dataset suitable for further analysis.

The cleaned dataset can be used as a foundation for subsequent internship tasks such as:

- Sales analysis
- KPI reporting
- Pivot table analysis
- Dashboard creation
- Business insights generation

---

## 💡 Key Learning Outcomes

Through this project, I practiced:

- Data cleaning with Pandas
- Missing-value handling
- Duplicate detection and removal
- Data standardization
- Numeric data validation
- Date conversion
- Feature creation
- Automated data-quality testing
- CSV data export
- Documenting an analytical workflow

---

## 👩‍💻 Author

**Kethana Sai Pranavi Atmuri**

Data Analyst Intern  
CodeOrbit Tech — Batch IND1

---

## 📌 Internship

This project was completed as **Task 1 — Data Cleaning** as part of the **CodeOrbit Tech Data Analyst Internship**.
