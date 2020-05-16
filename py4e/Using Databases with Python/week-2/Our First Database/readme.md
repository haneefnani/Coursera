<h1>Instructions</h1>
<p> 
If you don't already have it, install the SQLite Browser from
<a href="http://sqlitebrowser.org/" target="_blank">
http://sqlitebrowser.org/</a>.
<p>
Then, create a SQLITE database or use an existing 
database and create a table 
in the database called "Ages":

<pre>CREATE TABLE Ages ( 
  name VARCHAR(128), 
  age INTEGER
)
</pre>
<p>
Then make sure the table is empty by deleting any rows that 
you previously inserted, and insert these rows and only these rows 
with the following commands:
<pre>DELETE FROM Ages;
INSERT INTO Ages (name, age) VALUES ('Darcy', 22);
INSERT INTO Ages (name, age) VALUES ('Euan', 24);
INSERT INTO Ages (name, age) VALUES ('Karl', 38);
INSERT INTO Ages (name, age) VALUES ('Kyrah', 14);
INSERT INTO Ages (name, age) VALUES ('Rayyan', 28);
INSERT INTO Ages (name, age) VALUES ('Mercedez', 14);
</pre>
Once the inserts are done, run the following SQL command:
<pre>SELECT hex(name || age) AS X FROM Ages ORDER BY X
</pre>
Find the <b>first</b> row in the resulting record set and enter the long string that looks like 
<b>53656C696E613333</b>.
</p>
<p>
<b>Note:</b> This assignment must be done using SQLite - in particular, the 
<code>SELECT</code> query above will not work in any other database.  So 
you cannot use MySQL or Oracle for this assignment.
</p>
