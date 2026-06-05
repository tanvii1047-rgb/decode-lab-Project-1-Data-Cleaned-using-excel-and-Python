# Data Cleaning & Preparation Project 1

## Project Overview
This project is part of Data Analytics Project 1. The goal of this project is to clean a raw dataset by handling missing values, duplicate records, incorrect date formats, numeric formatting issues, and text inconsistencies.

## Objective
The main objective of this project is to prepare a clean and reliable dataset for further analysis.

## Dataset
The dataset contains order-related data such as Order ID, Customer ID, Product, Date, Quantity, Unit Price, Coupon Code, Payment Method, Order Status, and Total Price.

## Tools Used
- Python
- Pandas
- NumPy
- OpenPyXL
- Microsoft Excel

## Data Cleaning Steps Performed
1. Loaded the raw Excel dataset.
2. Checked missing/null values.
3. Replaced missing CouponCode values with `NO_COUPON`.
4. Checked duplicate OrderID values.
5. Removed duplicate records if present.
6. Converted Date column into `yyyy-mm-dd` format.
7. Converted numeric columns into proper number format.
8. Verified TotalPrice using Quantity × UnitPrice.
9. Created Audit Report.
10. Created Change Log.

## Final Output
The final cleaned Excel file contains:
- Raw_Data
- Cleaned_Data
- Audit_Report
- Change_Log

## Files Included
- `Dataset for Data Analytics.xlsx` - Original dataset
- `Data_Cleaning_Project_1_Final.xlsx` - Cleaned final dataset
- `data_cleaning_project.py` - Python cleaning code
- `requirements.txt` - Required

## Conclusion
This project helped in understanding the importance of data cleaning and preparation before performing analysis or building dashboards. The final dataset has zero duplicate OrderID values, corrected date format, handled missing values, and verified numeric calculations.
