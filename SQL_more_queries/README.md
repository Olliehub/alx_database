A README.md report on SQL - More queries.

**Requirements:**

Recommended editors: Visual studio code
All your files will be executed on Ubuntu 20.04 LTS using MySQL 5.7 (version 5.7.8-rc)
All your files should end with a new line
All your SQL queries should have a comment just before (i.e. syntax above)
All your files should start by a comment describing the task
All SQL keywords should be in uppercase (SELECT, WHERE…)
A README.md file, at the root of the folder of the project, is mandatory
The length of your files will be tested using wc

Task 0: My privileges!
Write a script that lists all privileges of the MySQL users user_0d_1 and user_0d_2 on your server (in localhost).

Task 1: Root user
Write a script that creates the MySQL server user user_0d_1.

user_0d_1 should have all privileges on your MySQL server
The user_0d_1 password should be set to user_0d_1_pwd
If the user user_0d_1 already exists, your script should not fail

Task 2: Read user
Write a script that creates the database hbtn_0d_2 and the user user_0d_2.

user_0d_2 should have only SELECT privilege in the database hbtn_0d_2
The user_0d_2 password should be set to user_0d_2_pwd
If the database hbtn_0d_2 already exists, your script should not fail
If the user user_0d_2 already exists, your script should not fail

Task 3: Always a name
Write a script that creates the table force_name on your MySQL server.

force_name description:
id INT
name VARCHAR(256) can’t be null
The database name will be passed as an argument of the mysql command
If the table force_name already exists, your script should not fail

Task 4: ID can't be null
Write a script that creates the table id_not_null on your MySQL server.

id_not_null description:
id INT with the default value 1
name VARCHAR(256)
The database name will be passed as an argument of the mysql command
If the table id_not_null already exists, your script should not fail