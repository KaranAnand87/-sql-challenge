# -sql-challenge
Module 9 Challenge

Employee Database

In this repository, the data is of employees of a corrporation in the form of six CSV files.

I will design the tables to hold data in the CSVs, import the CSVs into a SQL database (Postgres), and answer questions about the data. The major tasks are:

1. Data Modeling

2. Data Engineering

3. Data Analysis


## Data Modelling
I inspected the CSVs and sketched out an ERD of the tables, using Quick Database Diagrams.


![Module 9_employees_ERD](https://user-images.githubusercontent.com/120350694/221731212-ef6cbb7f-6498-4beb-b707-9c8f6230a13f.png)


## Data Engineering

I created a table schema for each of the six CSV files. For the primary keys check to see if the column is unique, otherwise created a composite key, which takes to primary keys in order to uniquely identify a row.

I created tables in the correct order to handle foreign keys.

I imported each CSV file into the corresponding SQL table. Note be sure to import the data in the same order that the tables were created and account for the headers when importing to avoid errors.

## Data Analysis

