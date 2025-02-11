# Data-Models-and-Databases
Creating and understanding a data model, how to use it and creating  database using the data model.



Building Data Models and Databases
Data Models – an abstract model that organizes elements of data and standardizes how they relate to one another and to properties of real-world entities.
It organizes tables about a particular topic/entity. In each table we have primary keys and foreign keys which are primary keys of other tables. The relationship between tables is represented by these keys.

Data Modelling is important because:
•	Organizes Data
•	Organized data determines later data use
•	Begin prior to building out applications, business logic and analytical models
Relational Data Model
Organizes data into one or more tables of columns and rows, with a primary key identifying each row.
 
Students, Subjects and Marks tables.
Relational Database
It is a digital database based on relational data model; a software system used to maintain relational databases is a RDBMS.
Common types of RDBMS:

•	MySQL
•	PostgreSQL
•	Oracle
•	MSSSQL
The basics
Database/Schema
•	Collections of Tables
Tables/Relations
A group of rows sharing the same labelled elements.
•	Students, Subjects and Marks.
Advantages of using Relational Databases
•	Ease of use - SQL
•	 Ability to do JOINS between tables
•	Ability to do aggregations and analytics
•	Smaller data volumes
•	Flexibility of queries
•	ACID transactions – data integrity.
ACID Properties
Atomicity – either if it will complete a query or abort the whole process in any situation.
Consistency – data being consistent across all networks
Isolation – each transaction should be independent and not be affected by other transactions.
Durability – recoverability to recover from errors.
When not to use Relational Database
•	Large amounts of Data
•	Need to be able to store different data type formats
•	Need a flexible schema
•	Need high availability
•	Need horizontal scalability
PostgreSQL
•	Open-source object-relational database system
•	Uses and builds on SQL language
`psycopg2` is a PostgreSQL adapter for the Python programming language. It is used to connect to a PostgreSQL database and perform database operations such as executing SQL queries, retrieving data, and managing transactions. It provides a Python DB-API 2.0 compliant interface to interact with PostgreSQL databases.

Key features of `psycopg2` include:
-	Connection pooling
-	Support for asynchronous communication
-	Server-side cursors
-	Large object support
-	Copy command support

In summary, `psycopg2` is a powerful and efficient library for interacting with PostgreSQL databases from Python applications.
 



