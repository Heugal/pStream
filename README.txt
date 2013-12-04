Ian Rockefeller
Stephan Luchanko
3238 Final Project

I believe I have included everything to build this locally. 
The /includes/functions.php has the dbCon() function to connect to the DB
this is also where the login info is that you can edit to run locally.
mysqldump1.sql is the dump of the database called StreamDB.
I have included pictures of the tables and columns, the relationships aren't
worth noting and are obvious. Each user can have many objects and many rss links
, per each user. The website link to access the application is :

	http://ec2-54-214-14-238.us-west-2.compute.amazonaws.com/

some good users to log into are jen@jen.com password: jen123
and bob@bob.com password: bob123, I believe jen only has facebook and twitter
where bob has RSS, twitter and facebook. 

Username: test
Password: test
The above account has all APIs and an RSS feed. Possible that we may need to reauthenticate
to get a live demonstration, but there are examples if you scroll down the page
to earlier posts. To manually update the stream, simply go to /updateStream.php until
you go to a blank white page. That is the file that the cronjob uses to update our timeline
at a periodic interval, but it can be manually called as well.

The cronjob is included in crontab.txt and all the libraries we used are located 
respectively in /pStream,
and lastly /stream/ is / 
Enjoy!
