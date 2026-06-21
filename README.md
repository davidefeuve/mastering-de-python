# Mastering Data Engineering with Python

Hands-on Data Engineering exercises completed while working through practical Python and data engineering concepts.

## Project Overview

This repository contains a collection of exercises focused on developing Data Engineering skills using Python, SQL, PostgreSQL and related tools.

The exercises cover topics such as:

* Data format conversion (CSV, JSON and Parquet)
* Data validation and quality checks
* PostgreSQL database integration
* Data loading and ETL processes
* SQL querying and data verification
* Environment variable management for secure database connections

## Technologies Used

* Python
* Pandas
* PostgreSQL
* psycopg2
* SQLAlchemy
* Jupyter Notebook
* Git & GitHub

## Exercises Completed

### Exercise 1 – File Format Conversion

* Converted `sales.csv` to JSON format
* Converted JSON data to Parquet format
* Verified successful file generation using pandas

### Exercise 2 – PostgreSQL Data Loading and Validation

* Connected securely to PostgreSQL using environment variables
* Loaded CSV data into a PostgreSQL table using Python and psycopg2
* Performed post-load data integrity checks using SQLAlchemy
* Verified record counts, missing values and invalid data conditions

### Exercise 3 – Data Validation

* Created a reusable CSV validation function
* Validated schema compliance against expected columns and data types
* Checked for missing values
* Reported validation issues for further investigation

### Exercise 4 – Data Aggregation and Grouping

* Performed aggregations using pandas
* Calculated total salary by department
* Calculated average salary by department
* Aggregated salary and bonus metrics
* Grouped data by category and counted records

### Exercise 5 – Data Transformation Using Pandas

* Created derived columns from existing data
* Calculated employee experience from joining dates
* Filtered records based on multiple conditions
* Demonstrated common data transformation techniques

### Exercise 6 – CSV to JSON Converter

* Converted `employees.csv` into JSON format
* Exported JSON records to a file
* Demonstrated file handling and data serialization using pandas

### Exercise 7 – Advanced File Format Handling

* Processed nested JSON data
* Flattened hierarchical customer and order information using `json_normalize`
* Validated required fields
* Logged data quality issues using Python logging
* Exported processed data to CSV and Parquet formats
* Demonstrated handling of semi-structured data commonly used in data engineering workflows

## Repository Structure

```text
## Repository Structure

```text
mastering-de-python/
│
├── datasets/
│   ├── sales.csv
│   ├── sales.parquet
│   ├── employees.csv
│   ├── employees.json
│   └── orders_nested.json
│
├── screenshots/
│   ├── PostgreSQL_db_creation.png
│   └── PostgreSQL_db_table.png
│
├── .env.example
├── .gitignore
├── README.md
└── hands_on_exercises.ipynb
```

## Author

David Fernandez

## Project Status

In progress