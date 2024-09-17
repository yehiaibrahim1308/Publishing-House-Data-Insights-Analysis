# Publishing-House-Data-Insights-Analysis
a database management system that contains data related to a fictional publishing company, such as Title, authors, publishers, and sales. The database is designed to store and manage information about the books published by the company, the authors who write them, the publishers who distribute them, and the sales made to customers.

# dataset consist of these tables: 
1-Authors Table: This table contains information about the authors of books. 
2-Titles: The titles table contains information about each book title.
3-Publishers: The publishers table contains information about each publisher.
4-Publisher_info: contains extra information about the publisher
5-Title Authors: The title author table is a junction table that maps the relationship between books and authors
6-Sales: The sales table contains information about each book sale.
7-Stores: The stores table contains information about each store
8-Discounts: discounts a customer can have on his purchase
9-Employee: people who are employed by the business
10-Jobs: What type and level of work does each employee do?
11-Roysched : contains information about the royalty payments made to the authors


# The data model before transformation:

![image](https://github.com/user-attachments/assets/eb30c6e1-b241-4698-a895-a3246371a54a)

# The process of transforming the dataset into a star schema consists of five key stages, each subdivided into smaller steps, as outlined below

1.  creating the author dimension
2.  creating the title dimension
3.  creating the sales dimension
4.  creating the employee dimension
5.  connecting the fact table to all of the dimensions listed above


# Transformed Dataset Overview

![image](https://github.com/user-attachments/assets/02f9a538-b176-4875-8dc1-7758883c567e)



# Measures and Hierarchies Defined in the Fact Table: 

Hierarchies:
a hierarchy for author titles that includes both the title name and the authors' full names
City, store name, store ID, and title ID make up the hierarchy for store details.
Title, author name, publisher id, and the actual royalty make up the royalty hierarchy.

Measures:
Measure for the total number of stores
Measure for total advance payments by publisher to author
Measure for total number of distinct royalty
Measure for total number of orders
Measure for total number of years sales
Measure for total number of authors
Measure for total number of title-id


# Interactive Data Dashboard    

![image](https://github.com/user-attachments/assets/593c94ca-4b53-42a4-8baf-3a2869baf7a1)

![image](https://github.com/user-attachments/assets/d96cbf9d-0c55-4f51-a2e2-4ca052f22eba)

![image](https://github.com/user-attachments/assets/208a05cd-3956-4489-b5c1-73765e709c3a)

![image](https://github.com/user-attachments/assets/7d4e6258-221a-4ca1-9a47-55abbc9e1b91)

![image](https://github.com/user-attachments/assets/d7f4216c-f42a-4ed7-ba08-3c3817ee66dd)




