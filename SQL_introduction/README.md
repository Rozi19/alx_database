<h1>SQL - Introduction</h1>
<br>
<h2>0. List databases</h2>
<br>
Write a script that lists all databases of your MySQL server.
<br>
<h2>1. Create a database</h2>
<br>
Write a script that creates the database hbtn_0c_0 in your MySQL server.
<br>
If the database hbtn_0c_0 already exists, your script should not fail
<br>You are not allowed to use the SELECT or SHOW statements
<br>
<h2>2. Delete a database</h2>
<br>
Write a script that deletes the database hbtn_0c_0 in your MySQL server.
<br>
If the database hbtn_0c_0 doesn’t exist, your script should not fail
<br>
You are not allowed to use the SELECT or SHOW statements
<br>
<h2>3. List tables</h2>
<br>
Write a script that lists all the tables of a database in your MySQL server.
<br>
The database name will be passed as argument of mysql command (in the following example: mysql is the name of the database)<br>
<h2>4. First table</h2>
<br>
Write a script that creates a table called first_table in the current database in your MySQL server.
<br>
first_table description:<br>
id INT<br>
name VARCHAR(256)<br>
The database name will be passed as an argument of the mysql command<br>
If the table first_table already exists, your script should not fail<br>
You are not allowed to use the SELECT or SHOW statements<br>
<h2>5. Full description</h2>
<br>
Write a script that prints the full description of the table first_table from the database hbtn_0c_0 in your MySQL server.
<br>
The database name will be passed as an argument of the mysql command<br>
You are not allowed to use the DESCRIBE or EXPLAIN statements<br>
<h2>6. List all in table</h2>
<br>
Write a script that lists all rows of the table first_table from the database hbtn_0c_0 in your MySQL server.
<br>
All fields should be printed<br>
The database name will be passed as an argument of the mysql command<br>
<h2>7. First add</h2>
<br>
Write a script that inserts a new row in the table first_table (database hbtn_0c_0) in your MySQL server.
<br>
New row:<br>
id = 89<br>
name = Holberton School<br>
The database name will be passed as an argument of the mysql command<br>
<h2>8. Count 89</h2>
<br>
Write a script that displays the number of records with id = 89 in the table first_table of the database hbtn_0c_0 in your MySQL server.
<br>
The database name will be passed as an argument of the mysql command<br>
<h2>9. Full creation</h2>
<br>
Write a script that creates a table second_table in the database hbtn_0c_0 in your MySQL server and add multiples rows.
<br>
second_table description:<br>
id INT<br>
name VARCHAR(256)<br>
score INT<br>
The database name will be passed as an argument to the mysql command<br>
If the table second_table already exists, your script should not fail<br>
You are not allowed to use the SELECT and SHOW statements<br>
Your script should create these records:<br>
id = 1, name = “John”, score = 10<br>
id = 2, name = “Alex”, score = 3<br>
id = 3, name = “Bob”, score = 14<br>
id = 4, name = “George”, score = 8<br>
