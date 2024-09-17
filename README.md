# Publishing-House-Data-Insights-Analysis
This project presents a comprehensive Database Management System (DBMS) for a fictional publishing company. The database manages crucial information such as book titles, authors, publishers, and sales performance. It is specifically designed to store and organize data related to the company’s published books, authorship, distribution through various publishers, and sales transactions with customers.

# Key Dataset Components

The dataset is structured across multiple tables that represent various aspects of the publishing business:

1. Authors Table: Contains information about the authors of books.
2. Titles Table: Stores data for each book title published.
3. Publishers Table: Holds information about all publishing companies involved in the distribution of the books.
4. Publisher_Info Table: Provides additional details on each publisher.
5. Title Authors Table: Acts as a junction table that links books to their respective authors.
6. Sales Table: Records sales transactions for each book.
7. Stores Table: Contains data for all stores selling the published books.
8. Discounts Table: Specifies discounts applicable to customer purchases.
9. Employee Table: Captures details about the employees of the publishing company.
10. Jobs Table: Describes the job types and levels of work for each employee.
11. Roysched Table: Tracks royalty payments made to authors.

#Initial Data Model Overview
Here’s the data model before the transformation process:

![image](https://github.com/user-attachments/assets/eb30c6e1-b241-4698-a895-a3246371a54a)

# Data Transformation Process

The dataset transformation follows a structured process to convert the original data model into a Star Schema. The transformation consists of five major stages, with each stage containing specific steps:

1.  creating the author dimension
2.  creating the title dimension
3.  creating the sales dimension
4.  creating the employee dimension
5.  connecting the fact table to all of the dimensions listed above


# Transformed Dataset Overview

After transformation, the dataset is organized as follows:

![image](https://github.com/user-attachments/assets/02f9a538-b176-4875-8dc1-7758883c567e)



# Fact Table: Measures and Hierarchies

Defined Hierarchies:
  Author Hierarchy: Includes both the book title and the author's full name.
  Store Hierarchy: Structured by city, store name, store ID, and title ID.
  Royalty Hierarchy: Consists of the title, author name, publisher ID, and the actual     
   royalty amount.

Key Measures:

  Total number of stores
  Total advance payments by publishers to authors
  Total number of distinct royalty payments
  Total number of orders
  Total number of sales by year
  Total number of authors
  Total number of book titles (Title-ID)



# Interactive Data Dashboard    

The dataset is complemented by an interactive data dashboard, allowing dynamic exploration of the data:

![image](https://github.com/user-attachments/assets/2f162e11-1afb-4e1f-926a-bce8d25fcc96)






# data source code 

The source code for this database is derived from the Northwind and Pubs sample databases. For detailed information and access to the source code, please refer to the [Microsoft SQL Server Samples repository](https://github.com/microsoft/sql-server-samples/tree/master/samples/databases/northwind-pubs).

