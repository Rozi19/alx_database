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
