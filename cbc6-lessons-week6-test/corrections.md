INDEX.HTML
-no changes

404.HTML
-no changes

LOGIN.HTML
-inserted main.js (line 7)
-inserted server.js (line 8)

MAIN.JS
-inserted var port= 8080; (line 2)

SERVER.JS
-inserted var port= 8080; (line 4)
-added ''' if (filePath== './login.html') ''' (line 40)
-added ''' filePath+= '404.html'; ''' (line 43)
-changed "error" to "err" (line 55)

DATABASE
	I figured I would have to use a database and create a table to insert the
passwords and usernames in the text file, but I kept getting a syntax error when I tried to 
create and add data into the table. I looked up resources on what the problem could be and 
how to create a table to load into the database to see if I was doing something small wrong,
but I couldn't find the issue. The next thing I looked up was how to connect the database to
the server.