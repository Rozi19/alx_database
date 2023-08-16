<h1>SQL - More queries</h2>
<br>
<h2>0. My privileges!</h2>
<br>
Write a script that lists all privileges of the MySQL users user_0d_1 and user_0d_2 on your server (in localhost).

<br>

<h2>1. Root user</h2>
<br>
Write a script that creates the MySQL server user user_0d_1.
<br>
user_0d_1 should have all privileges on your MySQL server<br>
The user_0d_1 password should be set to user_0d_1_pwd<br>
If the user user_0d_1 already exists, your script should not fail<br>
<h2>2. Read user</h2>
<br>
Write a script that creates the database hbtn_0d_2 and the user user_0d_2.
<br>
user_0d_2 should have only SELECT privilege in the database hbtn_0d_2<br>
The user_0d_2 password should be set to user_0d_2_pwd<br>
If the database hbtn_0d_2 already exists, your script should not fail<br>
If the user user_0d_2 already exists, your script should not fail<br>
<h2>3. Always a name</h2>
<br>
Write a script that creates the table force_name on your MySQL server.
<br>
force_name description:<br>
id INT<br>
name VARCHAR(256) can’t be null<br>
The database name will be passed as an argument of the mysql command<br>
If the table force_name already exists, your script should not fail<br>
<h2>4. ID can't be null</h2>
<br>
Write a script that creates the table id_not_null on your MySQL server.
<br>
id_not_null description:<br>
id INT with the default value 1<br>
name VARCHAR(256)<br>
The database name will be passed as an argument of the mysql command<br>
If the table id_not_null already exists, your script should not fail<br>
<h2>5. Unique ID</h2>
<br>
Write a script that creates the table unique_id on your MySQL server.
<br>
unique_id description:<br>
id INT with the default value 1 and must be unique<br>
name VARCHAR(256)<br>
The database name will be passed as an argument of the mysql command<br>
If the table unique_id already exists, your script should not fail<br>
<h2>6. States table</h2>
<br>
Write a script that creates the database hbtn_0d_usa and the table states (in the database hbtn_0d_usa) on your MySQL server.
<br>
states description:<br>
id INT unique, auto generated, can’t be null and is a primary key<br>
name VARCHAR(256) can’t be null<br>
If the database hbtn_0d_usa already exists, your script should not fail<br>
If the table states already exists, your script should not fail<br>
<h2>7. Cities table</h2>
<br>
Write a script that creates the database hbtn_0d_usa and the table cities (in the database hbtn_0d_usa) on your MySQL server.
<br>
cities description:<br>
id INT unique, auto generated, can’t be null and is a primary key<br>
state_id INT, can’t be null and must be a FOREIGN KEY that references to id of the states table<br>
name VARCHAR(256) can’t be null<br>
If the database hbtn_0d_usa already exists, your script should not fail<br>
If the table cities already exists, your script should not fail<br>
<h2>8. Cities of California</h2>
<br>
Write a script that lists all the cities of California that can be found in the database hbtn_0d_usa.
<br>
The states table contains only one record where name = California (but the id can be different, as per the example)<br>
Results must be sorted in ascending order by cities.id<br>
You are not allowed to use the JOIN keyword<br>
The database name will be passed as an argument of the mysql command<br>
<h2>9. Cities by States</h2>
<br>
Write a script that lists all cities contained in the database hbtn_0d_usa.
<br>
Each record should display: cities.id - cities.name - states.name<br>
Results must be sorted in ascending order by cities.id<br>
You can use only one SELECT statement<br>
The database name will be passed as an argument of the mysql command<br>
