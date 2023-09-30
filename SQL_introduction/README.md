A README.md report on SQL - Introduction...

**Requirements**

General
Recommended editors: Visual studio code
All your files will be executed on Ubuntu 20.04 LTS using MySQL 5.7 (version 5.7.8-rc)
All your files should end with a new line
All your SQL queries should have a comment just before (i.e. syntax above)
All your files should start by a comment describing the task
All SQL keywords should be in uppercase (SELECT, WHERE…)
A README.md file, at the root of the folder of the project, is mandatory
The length of your files will be tested using wc

Task 0: List databases
Write a script that lists all databases of your MySQL server.

Task 1: Create a database
Write a script that creates the database hbtn_0c_0 in your MySQL server.

Task 2: Delete a database
Write a script that deletes the database hbtn_0c_0 in your MySQL server.

Task 3: List tables
Write a script that lists all the tables of a database in your MySQL server.

The database name will be passed as argument of mysql command (in the following example: mysql is the name of the database)

Task 4: First table
Write a script that creates a table called first_table in the current database in your MySQL server.

first_table description:
id INT
name VARCHAR(256)
The database name will be passed as an argument of the mysql command
If the table first_table already exists, your script should not fail
You are not allowed to use the SELECT or SHOW statements

Task 5: Full description
Write a script that prints the full description of the table first_table from the database hbtn_0c_0 in your MySQL server.

The database name will be passed as an argument of the mysql command
You are not allowed to use the DESCRIBE or EXPLAIN statements

Task 6: List all in table
Write a script that lists all rows of the table first_table from the database hbtn_0c_0 in your MySQL server.

All fields should be printed
The database name will be passed as an argument of the mysql command

Task 7: First add
Write a script that inserts a new row in the table first_table (database hbtn_0c_0) in your MySQL server.

New row:
id = 89
name = Holberton School
The database name will be passed as an argument of the mysql command