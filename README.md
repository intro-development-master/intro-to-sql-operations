# Intro to SQL Operations

SQL stands for Structured Query Language. This is the database language most developers use to interact wtih a database.

The basic of Databases are CRUD operations:

* Create
* Read
* Update
* Delete

However, there are many other operations a developer or DBA might use to manipulate data.  These SQL commands are broken up into four categories:

1. DDL (Data Definition Language)
1. DML (Data Manipulation Language)
1. DCL (Data Control Language)
1. TCL (Transaction Control Language)

## DDL - Data Definition Language

DDLs consist of SQL commands that can be used to define a database schema, or structure.

They deal with descriptions of the database schema and is used to create and modify the structure of database objects in database.

Operations:

* **CREATE** – Creates the database or its objects
  * Like table, index, function, views, store procedure and triggers
* **DROP** – Delete objects from the database
* **ALTER** - Alters the structure of the database
* **TRUNCATE** – Remove all records from a table
  * Includes all spaces allocated for the records are removed
* **COMMENT** – Add comments to the data dictionary
* **RENAME** – Renames an object existing in the database

## DML - Data Manipulation Language

DMLs consist of SQL commands that deals with the manipulation of data present in database. This includes most of the SQL statements.

Operations:

* **SELECT** – Retrieves data from the a database
* **INSERT** – Inserts data into a table
* **UPDATE** – Updates existing data within a table
* **DELETE** – Deletes records from a database table

## DCL - Data Control Language

DCLs consist of SQL commands such as GRANT and REVOKE which mainly deals with the rights, permissions and other controls of the database system.

Operations:

* **GRANT** - gives user’s access privileges to database
* **REVOKE** - withdraw user’s access privileges given by using the GRANT command

## TCL - Transaction Control Language

TCLs consist of SQL commands that deal with the transaction within the database

* **COMMIT** – commits a Transaction
* **ROLLBACK** – rollbacks a transaction in case of any error occurs
* **SAVEPOINT** – sets a savepoint within a transaction
* **SET TRANSACTION** – specify characteristics for the transaction