<h2>Musical Track Database</h2>
<p>This application will read an iTunes export file in XML and produce a properly normalized database with this structure:</p>
<pre>
CREATE TABLE Artist (
    id  INTEGER NOT NULL PRIMARY KEY AUTOINCREMENT UNIQUE,
    name    TEXT UNIQUE
);

CREATE TABLE Genre (
    id  INTEGER NOT NULL PRIMARY KEY AUTOINCREMENT UNIQUE,
    name    TEXT UNIQUE
);

CREATE TABLE Album (
    id  INTEGER NOT NULL PRIMARY KEY AUTOINCREMENT UNIQUE,
    artist_id  INTEGER,
    title   TEXT UNIQUE
);

CREATE TABLE Track (
    id  INTEGER NOT NULL PRIMARY KEY 
        AUTOINCREMENT UNIQUE,
    title TEXT  UNIQUE,
    album_id  INTEGER,
    genre_id  INTEGER,
    len INTEGER, rating INTEGER, count INTEGER
);</pre>
<p>
If you run the program multiple times in testing or with different files, make sure to empty out the data before each run.

You can use this code as a starting point for your application: http://www.py4e.com/code3/tracks.zip. The ZIP file contains the Library.xml file to be used for this assignment. You can export your own tracks from iTunes and create a database, but for the database that you turn in for this assignment, only use the Library.xml data that is provided.

To grade this assignment, the program will run a query like this on your uploaded database and look for the data it expects to see:
</p>
<pre>
SELECT Track.title, Artist.name, Album.title, Genre.name 
    FROM Track JOIN Genre JOIN Album JOIN Artist 
    ON Track.genre_id = Genre.ID and Track.album_id = Album.id 
        AND Album.artist_id = Artist.id
    ORDER BY Artist.name LIMIT 3
</pre>


<p>The expected result of the modified query on your database is: (shown here as a simple HTML table with titles)</p>


<table border="2">
<tbody><tr>
<th>Track</th><th>Artist</th><th>Album</th><th>Genre</th>
</tr>
<tr><td>Chase the Ace</td><td>AC/DC</td><td>Who Made Who</td><td>Rock</td></tr><tr>
</tr><tr><td>D.T.</td><td>AC/DC</td><td>Who Made Who</td><td>Rock</td></tr><tr>
</tr><tr><td>For Those About To Rock (We Salute You)</td><td>AC/DC</td><td>Who Made Who</td><td>Rock</td></tr><tr>
</tr></tbody></table>
