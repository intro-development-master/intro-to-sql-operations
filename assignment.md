# Assignment

For today's assignment, you will need to create a Database script and move the commands from the previous lesson into them.

This includes:

* Creating the `Library` database
* Creating the `Book` table
* Inserting all 5 records into table

## Addtional Criteria

You will need to create a `Checkout Record` table to represent someone checking out a book.  

| Column          | Constraint              |
|-----------------|-------------------------|
| First Name      | 18 chars                |
| Last Name       | 44 chars                |
| Email Address   | 50 chars                |
| Expiration Date | Two weeks from checkout |

Borrowers:

* Jon Snow
* Marty McFly
* Malcom Reynolds
* Randy Savage

You can store these changes within the DDL/SQL script.

**NOTE:** You will need to tie this table to the `Book` table.