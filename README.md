
What is Data?
Data, in the context of databases, refers to all the single items that are stored in a database.
For example your name, age, height, weight, etc are some data related to you.
What is a Database?
A database is a collection of data that is organized in such a way that it can be easily accessed, managed and updated.
E.g: Facebook have database to store all user’s data and their friend’s data into tables.

What is a Database Management System (DBMS)?
Database Management System (DBMS) is a collection of programs that enables its users to create, read, update and delete data in a database. It also helps to control access to the  database.

The DBMS serves as an interface between the database and end users or application programs, ensuring that data is consistently organized and remains easily accessible.



Popular types of DBMS

Relational database management system (RDMS)
A relational database management system (RDBMS) stores the data in tabular form with additional condition of data that enforces relationships among the tables.
RDBMS defines the integrity constraint for the purpose of holding ACID PROPERTY
In RDBMS, normalization process will be present to check the database table consistency.
E.g: Mysql,Oralce, Ms SQL Server, Sybase
NoSQL DBMS

What is SQL?
SQL stands for Structured Query language is  a standard language for accessing and manipulating relational databases.
SQL can be used to insert, search, update, delete records relational database.

What is MySQL?
MySQL is an open source relational database. MySQL is cross platform which means it runs on a number of different platforms such as Windows, Linux, and Mac OS etc.

Why use MySQL?
There are number of factor I choose Mysql over other relational database management system.

MySQL can be run on Windows, UNIX and Mac OS.
It is developed by Oracle and freely available for personal use via ‘MySQL Community Server’ 
MySQL has high performance compared to other relation database systems. This is due to its simplicity in design and support for multiple-storage engines.

SQL Commands:
SQL commands are divided into four subgroups, DDL, DML, DCL, and TCL.


	
DDL: DDL stands for Data Definition Language. DDL statements are used to define the database structure or schema and  how the data should reside in the database.

DDL commands in Mysql

CREATE - create database and its objects like table, index, views, stored procedure, function, and triggers.
ALTER - alters the structure of the database
DROP - delete objects from the database
TRUNCATE - remove all records from a table, including all spaces allocated for the records are removed
COMMENT - add comments to the data dictionary
RENAME - rename an object

DML:
Data Manipulation Language (DML) statements are used for managing data in database, and therefore includes most common SQL statements such SELECT, INSERT,UPDATE,DELETE etc.

DCL:
DCL is short name of Data Control Language mostly concerned with rights, permissions and other controls of the database system.
GRANT - allow users access privileges to the database
REVOKE - withdraw users access privileges given by using the GRANT command
 
TCL:
TCL is short name of Transaction Control Language which deals with a transaction within a database.
COMMIT - commits a Transaction
ROLLBACK - rollback a transaction in case of any error occurs
SAVEPOINT - to rollback the transaction making points within groups
SET TRANSACTION - specify characteristics of the transaction
 
