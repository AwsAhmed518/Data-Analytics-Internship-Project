# 📊 Task 1 – Data Cleaning and Preprocessing

## Overview

This project focuses on preparing a raw sales dataset for analysis by identifying and resolving common data quality issues. The objective is to ensure the dataset is accurate, consistent, and ready for exploratory data analysis.

## Objectives

* Handle missing values
* Remove duplicate records
* Correct inconsistent data formats
* Validate data types
* Detect and address outliers
* Prepare a clean dataset for further analysis

## Files

```text
Task 1
│
├── Dataset for Data Analytics.xlsx
├── task1.ipynb
└── README.md
```

## Tools & Libraries

* Python
* Pandas
* NumPy
* OpenPyXL
* Jupyter Notebook

## Data Cleaning Process

### 1. Missing Value Treatment

* Identified missing values across columns.
* Applied appropriate imputation techniques such as mean or median replacement depending on the data distribution.

### 2. Duplicate Removal

* Checked for duplicate records.
* Removed duplicate entries to ensure data integrity.

### 3. Data Type Validation

* Converted columns to appropriate data types.
* Ensured date columns were stored as datetime objects.

### 4. Data Standardization

* Cleaned text fields by removing extra spaces.
* Standardized naming conventions and categorical values.

### 5. Outlier Detection

* Investigated unusual values in numerical columns.
* Evaluated their impact on analysis before treatment.

## Results

The final dataset is:

* Free from duplicate records
* Consistent in formatting
* Properly typed
* Ready for exploratory data analysis and visualization

## How to Run

```bash
jupyter notebook task1.ipynb
```

## Author

Aws Ahmed
