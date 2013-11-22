#Types of Questions to answer

##Who is the target audience for our application?
The target audience are people using both desktops and mobile devices
that want to see a better visual representation and correlation of tweets
they search for.

##What does our application do?
The application takes 2 hashtags from the user input, as well as
a radius in miles to search by location and a date to search by.
Then the app displays the relevant results of the found tweets 
in a list, as well as on a map, showing where else in the U.S. 
this combination of tweets can be found. It also shows a sentiment score
for each tweet so the user knows where positive or negative tweets are coming from. 

##How does our application do it?
The application is using a node.js server, as well as express.js for the framework.
It uses Sentimental module for node.js to score each tweet's positive or negative feeling.
The results are displayed using responsive HTML & CSS,
in both a table and in Google Maps embeded on the page.
We are using Twitter API and Google Maps API to power our application.

##When will this application be available?
12/1/13

##Where can this application be accessed from? (URL)
http://teamnametwitter.herokuapp.com/ ## not currently up