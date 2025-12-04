# Walmart Data Analysis — End-to-End SQL + Python Project

## Overview

This project delivers a complete data analysis workflow using Python for preprocessing and SQL (MySQL & PostgreSQL) for business analytics. The goal is to extract actionable insights from the Walmart sales dataset while demonstrating real-world data engineering and analytics skills.

## Project Workflow:

-Set up the development environment
-Configure and use the Kaggle API
-Download the Walmart sales dataset
-Install required Python libraries
-Explore and clean the dataset
-Perform feature engineering
-Load the processed data into MySQL and PostgreSQL
-Execute SQL queries for business insights
-Document and publish results

## Key Steps
1. Environment Setup
Tools used: VS Code, Python, MySQL, PostgreSQL
Organized project folder structure for smooth development

2. Kaggle API Setup
Download kaggle.json from Kaggle Account Settings
Place it in the .kaggle/ directory
Use the Kaggle CLI to download datasets

3. Data Loading & Cleaning
Load data using Pandas
Inspect via info(), describe(), head()
Remove duplicates, fix data types, handle missing values
Clean currency fields

4. Feature Engineering
Add computed fields such as:
Total_Amount = unit_price * quantity

6. SQL Integration
Connect to MySQL/PostgreSQL using SQLAlchemy
Create tables and insert processed data
Validate data loading through SQL queries

6. Business Analysis with SQL
Executed advanced SQL to analyze:
Revenue trends
Best-selling categories
Payment method distribution
Branch performance
Customer rating patterns


## Project Structure
```
project/
│-- data/ # Raw & processed datasets
│-- sql_queries/ # SQL scripts
│-- notebooks/ # Jupyter notebooks
│-- main.py # ETL script
│-- requirements.txt # Dependencies
│-- README.md # Documentation
```

## Technology Stack

1. Python 3.8+
  -pandas
  -numpy
  -sqlalchemy
  -mysql-connector-python
  -psycopg2

2. Databases: MySQL, PostgreSQL

3. Kaggle API for dataset retrieval


## Results & Insights

The project highlights key findings related to:
1. Branch- and category-level sales performance
2. Top revenue-generating products
3. Profitability patterns across locations
4. Customer behavior trends and peak sales windows


## Future Enhancements

1. Add interactive dashboards (Power BI / Tableau)
2. Integrate more datasets for deeper analysis
3. Automate the ETL pipeline for scheduled updates


Peak sales hours
