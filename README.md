# -sql-challenge
## Module 9 Challenge - Employee Database

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
![Query_1](https://user-images.githubusercontent.com/120350694/221732982-b44352cb-2f0e-4d7f-a84e-476a0d32b95d.png)

![Query_2](https://user-images.githubusercontent.com/120350694/221732995-434ea76b-76ab-4a07-8bab-700bc588dd2f.png)

![Query_3](https://user-images.githubusercontent.com/120350694/221733023-8d25d7e7-7b5b-4985-881b-d124ceebcf79.png)

![Query_4](https://user-images.githubusercontent.com/120350694/221733045-2f02aead-ad3e-4ea0-b5dd-97915a8d2cde.png)

![Query_5](https://user-images.githubusercontent.com/120350694/221733090-90aa6012-502f-4087-8267-3d5988adc6fc.png)

![Query_6](https://user-images.githubusercontent.com/120350694/221733117-ac24d5a3-2a71-43e1-a760-4f5fce52b78a.png)

![Query_7](https://user-images.githubusercontent.com/120350694/221733143-b090e67e-19fa-456e-8592-f47f259b3c53.png)

![Query_8](https://user-images.githubusercontent.com/120350694/221733168-f9ca357a-0454-4c69-bf8c-f91b50a7c4c1.png)


