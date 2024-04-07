## Basic Definations

**SQL :** 
- stands for Structured Query Language, is a domain-specific programming language designed for managing and manipulating relational databases

**Database :** 
- is a structured collection of data that is organized and stored in a way that allows for efficient retrieval, updating, and management of that data. 

**DBMS :** -
- is a software suite that provides an interface for interacting with databases and managing the storage, retrieval, and manipulation of data.

## Subsets of SQL

SQL can be divided into various subsets or categories based on the functionality they provide:

- Data Definition Language (DDL)
- Data Manipulation Language (DML)
- Data Query Language (DQL)
- Data Control Language (DCL)
- Transaction Control Language (TCL)

## Advantages & Disadvantages of SQL

**Advantages:**
- Standardized language for managing relational databases.
- Provides powerful querying capabilities for retrieving and manipulating data.
- Supports data integrity constraints to ensure data consistency.
- Facilitates data security through user authentication and access control mechanisms.

**Disadvantages:**
- Complexity: SQL can be complex to learn and master, especially for complex queries and database designs.
- Performance: Poorly optimized SQL queries can lead to performance issues, especially in large databases.
- Vendor-specific features: Different database management systems (DBMS) may implement SQL features differently, leading to vendor lock-in.
- Scalability: Scaling relational databases to handle large volumes of data can be challenging compared to NoSQL databases.

## Tables and Fields

- **Tables:** A table is a collection of data organized in rows and columns. Each table in a database is designed to store data related to a specific entity or concept, such as customers, products, or orders. 

- **Fields (Columns):** Fields, also known as columns, are the individual data elements within a table. Each column represents a specific attribute or property of the data stored in the table. Columns have a defined data type that specifies the kind of data they can hold, such as integers, strings, dates, or floating-point numbers.

## Constraints in SQL

In SQL, constraints are rules or conditions applied to columns or tables to enforce data integrity and maintain the accuracy, consistency, and reliability of the data stored in a database.

- Primary Key Constraint
- Unique Constraint
- Foreign Key Constraint
- Check Constraint
- Not Null Constraint
- Default Constraint

## Primary Key and Foreign Key

**Primary Key:**
- A primary key is a special type of constraint in a relational database that uniquely identifies each record (or row) in a table. It serves as a unique identifier for the records and ensures that there are no duplicate or null values in the column or combination of columns defined as the primary key. Each table in a database can have only one primary key.

**Foreign Key:**
- A foreign key is another type of constraint in a relational database that establishes a link between two tables. It is used to ensure referential integrity by creating a relationship between the column(s) in one table, known as the foreign key, and the primary key in another table.





