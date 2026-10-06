
# MySQL Data Cleaning - Layoffs Dataset

## Overview

This project focuses on cleaning and preparing a layoffs dataset using MySQL.

The dataset contains 2,361 records across 9 columns and was used to practise
SQL data-cleaning techniques on a realistic dataset.

## Tools

- MySQL
- MySQL Workbench
- Excel/CSV

## Data Cleaning Process

The project involved:

- Identifying duplicate records
- Using CTEs
- Using window functions such as `ROW_NUMBER()`
- Using `PARTITION BY`
- Handling missing values
- Using self-joins
- Using `UPDATE ... JOIN`
- Standardising missing values to `NULL`
- Working with staging tables
- Modifying table structure using `ALTER TABLE`

## Before

The original dataset was imported into MySQL and reviewed for duplicates,
missing values and inconsistencies.

![Raw Dataset](screenshots/raw_data.png)

## After

The dataset was cleaned and prepared for future analysis.

![Cleaned Dataset](screenshots/cleaned_data.png)

## Key Learning

One of the main lessons from this project was that data cleaning isn't just
about writing SQL queries. It also requires understanding the dataset and
making decisions about how duplicates and missing information should be
handled.

## SQL

The complete SQL cleaning script can be found here:

`sql/data_cleaning.sql`
