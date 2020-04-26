
<h1>Counting Organizations</h1>
<p>
This application will read the mailbox data (mbox.txt) and count the
number of email messages per organization (i.e. domain name of the email
address) using a database with the following schema to maintain the counts.
<pre>CREATE TABLE Counts (org TEXT, count INTEGER)
</pre>
When you have run the program on <b>mbox.txt</b> upload the resulting
database file above for grading.
</p>
<p>
If you run the program multiple times in testing or with dfferent files, 
make sure to empty out the data before each run.
<p>
You can use this code as a starting point for your application:
<a href="https://www.py4e.com/code3/emaildb.py" target="_blank">
http://www.py4e.com/code3/emaildb.py</a>.
</p>
<p>
The data file for this application is the same as in previous assignments:
<a href="https://www.py4e.com/code3/mbox.txt" target="_blank">
http://www.py4e.com/code3/mbox.txt</a>.
</p>
<p>
Because the sample code is using an <b>UPDATE</b> statement
and committing the results to the database as each record
is read in the loop, it might take as long as a few minutes to process
all the data.  The commit insists on completely writing all the
data to disk every time it is called.
</p>
<p>
The program can be speeded up greatly by moving the commit operation
outside of the loop.  In any database program, there is a balance
between the number of operations you execute between commits and the
importance of not losing the results of operations that have
not yet been committed.
</p>
