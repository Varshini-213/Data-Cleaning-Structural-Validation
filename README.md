# Data Cleaning & Structural Validation

## Project Overview

This project demonstrates the process of transforming raw, unstructured data into a clean and reliable dataset suitable for analysis. The dataset contained duplicate records, missing values, inconsistent formatting, and invalid email entries.

## Objective

To design and implement a data cleaning pipeline that ensures data accuracy, consistency, and integrity while preserving valuable information.

## Dataset Issues Identified

* Missing values in Age and Email columns
* Duplicate records
* Inconsistent city name formatting
* Invalid email formats

## Data Cleaning Process

### 1. Missing Value Handling

* Filled missing Age values using the mean of the Age column.
* Replaced missing Email values with a placeholder email.

### 2. Data Standardization

* Standardized city names using title case formatting.
* Removed unnecessary spaces from text fields.

### 3. Duplicate Removal

* Removed duplicate records based on Name, Age, Email, and City columns.

### 4. Structural Validation

* Checked for remaining null values.
* Validated email formats using Regular Expressions (Regex).

## Results

| Metric                    | Value |
| ------------------------- | ----- |
| Original Records          | 10    |
| Cleaned Records           | 8     |
| Missing Values Handled    | Yes   |
| Duplicate Records Removed | Yes   |
| Invalid Emails Detected   | 1     |

## Technologies Used

* Python
* Pandas
* Regular Expressions (Regex)
* Google Colab

## Files Included

* raw_data.csv
* cleaned_data.csv
* data_cleaning.py
* Data_Cleaning_&_Structural_Validation.ipynb

## Learning Outcomes

* Data preprocessing techniques
* Missing value treatment
* Duplicate detection and removal
* Data validation
* Data quality assessment

## Author

Varshini
B.Tech Student | Aspiring Software Developer & Data Science Enthusiast
