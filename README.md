![image](https://github.com/itnatepena/SQL-DB-Intro/assets/147539410/c3f66eb5-314a-4f9c-b3d9-c7b2a768f6a3)

# SQL Database Interaction Project

## Introduction

This project serves as an introduction to creating and interacting with SQL databases using Microsoft Azure and Azure Data Studio. We'll cover the creation of a SQL database on Azure, setting up Azure Data Studio, and performing basic database operations.

## Prerequisites

- [Microsoft Azure](https://azure.microsoft.com/)
- [Azure Data Studio](https://docs.microsoft.com/en-us/sql/azure-data-studio/download)

## Step 1: Create an Azure SQL Database
![image](https://github.com/itnatepena/SQL-DB-Intro/assets/147539410/e2adc24d-bbfb-493b-8d11-5f8bca17e968)

1. Log in to your Azure portal.
2. Create a new Azure SQL Database.
3. Configure the database settings, including server, resource group, and pricing tier.
4. Make sure to allow public access and include your local machines IP in the firewall settings.

![image](https://github.com/itnatepena/SQL-DB-Intro/assets/147539410/010c2153-450c-43a9-a0c6-49eded1d1258)


## Step 2: Set Up Azure Data Studio

1. Download and install Azure Data Studio.
2. Launch Azure Data Studio on your local machine.

## Step 3: Connect to Azure SQL Database

1. In Azure Data Studio, click "Connections" on the sidebar.
2. Click "New Connection" and select "Azure" as the data source.
3. Enter your Azure SQL Database connection details, including server name, authentication type, and credentials.
4. Click "Connect" to establish a connection.

Using the connection string found in the Azure Portal we replace the portion (your_password) with our own credentials and hit connect.
![image](https://github.com/itnatepena/SQL-DB-Intro/assets/147539410/e430f205-37f9-45fc-a287-a29e282f8f45)

## Step 4: Create Tables

1. In Azure Data Studio, open a new query window.

![image](https://github.com/itnatepena/SQL-DB-Intro/assets/147539410/085aa592-1ee3-4253-aabd-9c2a563398bb)

2. Use SQL scripts to create tables for your database (e.g., "Authors," "Books," "Categories").
![image](https://github.com/itnatepena/SQL-DB-Intro/assets/147539410/9d1e687b-c053-49a3-b76d-59e73f2904c4)
Here I show the script to add the authors table. I went ahead and added Books and Categories as well.

## Step 5: Insert Data

In this step, we'll populate our database with sample data by inserting authors, books, and categories.

**Insert Authors:**

1. In a query window in Azure Data Studio, use SQL scripts to insert author records into the "Authors" table. For example, insert authors "John Jacob," "Kimmy Karen," and "Nate Pena."
![image](https://github.com/itnatepena/SQL-DB-Intro/assets/147539410/94548352-5e3a-467a-bab4-a81cd6377e26)

**Insert Categories:**

1. Next, insert category records into the "Categories" table. In our example, we'll add "Fiction" and "Non-Fiction" categories.
![image](https://github.com/itnatepena/SQL-DB-Intro/assets/147539410/6cb04aeb-3c82-47fd-898e-19d98d49f286)


**Insert Books:**

1. Finally, insert book records into the "Books" table. Assign each book to an author and a category.

Heres the Books we added:

![image](https://github.com/itnatepena/SQL-DB-Intro/assets/147539410/883f1942-8d5b-43b7-a138-2f017660e614)


These SQL scripts will insert sample data into your tables. Customize the data as needed for your project. After executing these scripts, your database will be populated with authors, categories, and books.

## Step 6: Retrieve All Books

1. Write and execute a SQL query to retrieve all books from the "Books" table.
2. Observe the results to ensure all books are displayed.

![image](https://github.com/itnatepena/SQL-DB-Intro/assets/147539410/9b2fbd3c-3c68-4d78-81a5-d8f34484532e)


## Step 7: Retrieve Books by Author

1. Create and run a SQL query to retrieve books by a specific author (e.g., author with ID 3, which is Nate Pena).
2. Review the results to verify that only books by the selected author are shown.

![image](https://github.com/itnatepena/SQL-DB-Intro/assets/147539410/4049a38b-5a0e-4c6e-adfe-ac8900899510)


## Step 8: Calculate Average Book Price

1. Write an SQL query to calculate the average price of all books in the "Books" table.
2. Record the calculated average price and note the prices of other books in the database.

![image](https://github.com/itnatepena/SQL-DB-Intro/assets/147539410/758382c6-9841-46f0-b21b-45bbf76b8c86)


## Step 9: Adjust Book Price

1. Modify the price of one of the books (e.g., "The Great Grumblebums of Zoggleton") by executing an SQL `UPDATE` query.
2. Increase the price to your desired value.

![image](https://github.com/itnatepena/SQL-DB-Intro/assets/147539410/f2de1811-d7ff-4710-9142-4299fcca19e3)


## Step 10: Recheck Average Price

1. Recalculate the average price of all books in the "Books" table using an SQL query.
2. Compare the new average price to the previous calculation to confirm the price adjustment.
![image](https://github.com/itnatepena/SQL-DB-Intro/assets/147539410/b9dbe4ba-5996-46e9-8c43-10a9f8c7eeeb)
![image](https://github.com/itnatepena/SQL-DB-Intro/assets/147539410/b8005c64-f1d7-421a-bc70-dd1741beb59c)



## What We Learned

In this project, we learned how to:

- Create an Azure SQL Database.
- Set up Azure Data Studio.
- Connect to an Azure SQL Database using Azure Data Studio.
- Create tables in a SQL database.
- Insert data into tables.
- Retrieve data using SQL queries.
- Calculate and adjust values in the database.

This project serves as an introduction to working with SQL databases, and it showcases the basics of creating, populating, and interacting with a database using Microsoft Azure and Azure Data Studio.
