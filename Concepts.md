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


## Triggers in SQL

In SQL, a trigger is a set of instructions or a set of actions that are automatically executed  in response to certain events on a particular table or view. Triggers are used to enforce business rules, maintain referential integrity, or perform complex data validation and manipulation tasks when certain operations (such as INSERT, UPDATE, DELETE) occur on a specified table.

There are two main types of triggers:
- BEFORE Triggers
- AFTER Triggers



## Joins in SQL

Joins in SQL are used to combine rows from two or more tables based on a related column between them, allowing retrieval of data from multiple tables. There are several types of joins:

- **INNER JOIN:** Returns rows when there is a match in both tables.
- **LEFT JOIN (or LEFT OUTER JOIN):** Returns all rows from the left table and matching rows from the right table.
- **RIGHT JOIN (or RIGHT OUTER JOIN):** Returns all rows from the right table and matching rows from the left table.
- **FULL JOIN (or FULL OUTER JOIN):** Returns all rows when there is a match in one of the tables.
- **CROSS JOIN:** Returns the Cartesian product of the two tables.
- **SELF JOIN:** Joins a table to itself.



## Normalization in SQL

Normalization in SQL is the process of organizing and designing a relational database schema to reduce data redundancy and dependency, ensuring data integrity and eliminating anomalies. The main normal forms include:

- **First Normal Form (1NF):** Ensures that each column in a table contains atomic (indivisible) values, eliminating repeating groups.
- **Second Normal Form (2NF):** Ensures that each non-key column is fully functionally dependent on the entire primary key, eliminating partial dependencies.
- **Third Normal Form (3NF):** Ensures that no transitive dependencies exist, eliminating dependencies on non-key columns.
- **Boyce-Codd Normal Form (BCNF):** A stricter form of 3NF where every non-trivial functional dependency involves a superkey.
- **Fourth Normal Form (4NF):** Addresses certain types of multi-valued dependencies that can occur when there are composite keys.
- **Fifth Normal Form (5NF):** Focuses on addressing cases where certain types of join dependencies exist between multiple tables.



## Database Truncate, Delete, and Drop

- **TRUNCATE:** The TRUNCATE statement is used to remove all rows from a table quickly. It is a DDL (Data Definition Language) statement and is more efficient than the DELETE statement for removing all rows.
- **DELETE:** The DELETE statement is used to remove one or more rows from a table based on a specified condition. It is a DML (Data Manipulation Language) statement and generates individual row delete statements.
- **DROP:** The DROP statement is used to remove database objects, such as tables, indexes, or views. It is a DDL statement and is irreversible, removing both the structure and data of the specified object.



## Aggregate Functions and Scalar Functions

**Aggregate Functions:** Aggregate functions in SQL perform calculations on a set of values and return a single result. Common aggregate functions include COUNT(), SUM(), AVG(), MIN(), and MAX().

**Scalar Functions:** Scalar functions in SQL operate on a single value and return a single value. They can be used in SELECT statements, WHERE clauses, and other parts of a SQL query to manipulate or transform data. Common scalar functions include UPPER(), LOWER(), LENGTH(), CONCAT(), and ROUND().



## Window Functions

Window functions in SQL perform calculations across a specified range of rows related to the current row within the result set. They are used for analytical and reporting tasks and provide insights into the distribution of data within the result set. 

## Main Window Functions

- **ROW_NUMBER():** Assigns a unique number to each row within the partition, based on the specified order.
- **RANK():** Assigns a rank to each row within the partition, based on the specified order.
- **DENSE_RANK():** Assigns a dense rank to each row within the partition, based on the specified order.
- **LEAD():** Accesses data from subsequent rows within the partition.
- **LAG():** Accesses data from preceding rows within the partition.
- **SUM():** Calculates the sum of a specified column over a window.
- **AVG():** Calculates the average of a specified column over a window.
- **MAX():** Retrieves the maximum value of a specified column over a window.
- **MIN():** Retrieves the minimum value of a specified column over a window.


