# Crowdfunding ETL Project

This project involves building an ETL pipeline to extract, transform, and load data related to crowdfunding campaigns into a PostgreSQL database. The pipeline is implemented using Python, Pandas, and various methods for data extraction and transformation, including dictionary methods and regular expressions. The final output consists of CSV files that represent categories, subcategories, campaigns, and contacts, which are then imported into a PostgreSQL database.

## Project Overview

The goal of this project is to process and clean crowdfunding data from the `crowdfunding.xlsx` and `contacts.xlsx` files, and load the resulting data into a PostgreSQL database. The steps of the project include the following:

1. **Extract and Transform Data:**
   - Extract data from the `crowdfunding.xlsx` and `contacts.xlsx` files.
   - Clean and transform the data into a structured format.
   - Create DataFrames for categories, subcategories, campaigns, and contacts.

2. **Export Data:**
   - Export the transformed data into CSV files.
   - Create the following CSV files:
     - `category.csv`
     - `subcategory.csv`
     - `campaign.csv`
     - `contacts.csv`

3. **Database Design:**
   - Design an Entity-Relationship Diagram (ERD) based on the data.
   - Create a SQL schema for the PostgreSQL database.
   - Define tables with appropriate primary and foreign keys.

4. **Load Data into PostgreSQL:**
   - Create a PostgreSQL database (`crowdfunding_db`).
   - Create tables based on the schema.
   - Import the CSV data into the corresponding tables.

5. **Verify Data Integrity:**
   - Use SQL queries to ensure the data has been correctly imported into the PostgreSQL database.

## Project Files

1. `ETL_Mini_Project_NDelgado_NBola.ipynb`: Jupyter notebook containing the ETL pipeline code.
2. `crowdfunding.xlsx`: Source data for crowdfunding campaigns.
3. `contacts.xlsx`: Source data for contact information.
4. `category.csv`: Exported CSV file containing category data.
5. `subcategory.csv`: Exported CSV file containing subcategory data.
6. `campaign.csv`: Exported CSV file containing campaign data.
7. `contacts.csv`: Exported CSV file containing contact data.
8. `crowdfunding_db_schema.sql`: SQL file containing the schema for the PostgreSQL database.
