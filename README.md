# BankManagementData
In banking, personal loans serve as a significant revenue source, with a typical interest rate of 10% for a two-year loan in the UK. Mogul Bank, a UK-based bank, conducted a marketing campaign to encourage customers to take out personal loans. As part of this initiative, data was collected and needed to be cleaned, stored, and analyzed for insights.

This repository contains a solution to clean and store the collected data using Python, particularly utilizing the Pandas library for data manipulation and an RDBMS for storage. Additionally, SQL code is provided to create tables and populate them with data from CSV files.
# Tasks
1. Data Cleaning: The first task involves cleaning the data collected from the marketing campaign. This includes reformatting and splitting the data to save separate files based on the tables that will be created.

2. Database Implementation: The next task is to implement a robust RDBMS database capable of accommodating data from future campaigns. The schema comprises three tables: Client, Campaign, and Economics.

3. SQL Code Generation: SQL code is provided to create the necessary tables and populate them with data from CSV files. The SQL files are saved as multiline string variables for ease of use by the bank.

# Data and Tools
Data: The bank has supplied a CSV file named "bank_marketing.csv", which contains the data collected from the marketing campaign. This data will be cleaned, reformatted, and stored in the RDBMS.

Tools: Python will be used for data cleaning and manipulation, particularly leveraging the pandas library. An RDBMS will be utilized for database storage, and SQL will be used to create tables and populate them with data.

# Usage
Data Cleaning: The Jupyter Notebook DataCleaning.ipynb contains the code for cleaning and formatting the data.

Database Implementation: The Python script DatabaseImplementation.py includes the code to implement the RDBMS database with the specified schema.

SQL Code: The SQL code for table creation and data population is provided in the SQL_Code.sql file.
