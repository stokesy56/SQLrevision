#SQL
##What is a Database?
- A structured set of data held in a computer
- Types of database:
  - Flat-file: everything stored in one table
  - Relational: can seperate masses of data in numerous tables and linked through keys
  - Big Data: Extremely large datasets requiring newer softwares such as MongoDB

##Data Definition Language (DDL)
- DDL changes the structure of the table like creating a table, deleting a table, altering a table, etc.

*check for other commands*
CREATE - is used to create a new table in the database.
DROP -  is used to delete both the structure and record stored in the table
ALTER - is used to alter the structure of the database. This change could be either to modify the characteristics of an existing attribute or probably to add a new attribute.
TRUNCATE - is used to delete all the rows from the table and free the space containing the table.
JOIN - is used to combine rows from two or more tables, based on a related column between them.

##Data Manipulation Language (DML)
- DML commands are used to modify the database. It is responsible for all form of changes in the database.

- INSERT INTO - is used to insert new records in a table.
- UPDATE - is used to update or modify the value of a column in the table.
- DELETE - is used to remove one or more row from a table.
- IDENTITY - allows a unique number to be generated automatically when a new record is inserted into a table.

##Data Query Language (DQL)
- DQL is used to fetch the data from the database.

- SELECT - is used to select the attribute based on the condition described by WHERE clause.
- CASE - goes through conditions and returns a value when the first condition is met. So, once a condition is true, it will stop reading and return the result. If no conditions are true, it returns the value in the ELSE clause.
- WHERE - is used to filter records.
- Group BY - groups rows that have the same values into summary rows.
- TOP - is used to specify the number of records to return.
- DISTINCT - is used to return only different values. 
