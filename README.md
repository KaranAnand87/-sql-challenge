# -sql-challenge
Module 9 Challenge

Employee Database

In this repository, the major task is a research project on employees of a corporation from the 1980s and 1990s. All that remain of the database of employees from that period are six CSV files.

We will design the tables to hold data in the CSVs, import the CSVs into a SQL database (Postgres), and answer questions about the data. The major tasks are:

1. Data Modeling

2. Data Engineering

3. Data Analysis


We inspected the CSVs and sketched out an ERD of the tables. We using Quick Database Diagrams.


![Module 9_employees_ERD](https://user-images.githubusercontent.com/120350694/221731212-ef6cbb7f-6498-4beb-b707-9c8f6230a13f.png)


## Data Engineering

Create a table schema for each of the six CSV files.

For the primary keys check to see if the column is unique, otherwise create a composite key. Which takes to primary keys in order to uniquely identify a row.

Create tables in the correct order to handle foreign keys.

Import each CSV file into the corresponding SQL table. Note be sure to import the data in the same order that the tables were created and account for the headers when importing to avoid errors.

