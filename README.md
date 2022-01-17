# MEAN-Stack-Book-Store
The Book Store is a single page app built on the M-Mongo, E-Express, A-Angular, N-Node.js stack. 
As an Admin, this application allows us to add books for sales and as a user, allows us to buy, rate and leave comments on the books.
Tech Stack used are:
Mongodb - for DB purposes
Mongoose - To connect to the DB from the Angular App.
NodeJS - Runtime environment for the Angular
Angular - Platform for building the application.
ExpressJS - The Framework running on top of the NodeJS 
JSON WebToken - For authorization

These steps are for running the MEAN stack on a Linux OS. Same can be followed for Windows too.
Do not follow the same for Dockerized application.
Ensure the MongoDB and NodeJS(NPM by default) is installed on the OS.

After having forked the files into your local repo or having downloaded the zip from here.
Proceed to open the directory within your editor.
You should see 2 sets of files.
1. client
2. server

Setup a Project Directory. Example. Project1
Project 
--> client
--> server

Ensure that your mongodb service is running.
In case of Linux use # systemctl status mongod.
Make sure the service is active.

Now. 
$ cd server

$ npm install

$ npm start

With the above 3 commands run from the server directory, we should see that the server is started on port 8000 and the mongodb is connected.

Now.
$ cd client

$ npm install

$ ng serve 

With the above 3 commands run from within the client directory, the service should be opened on the http://localhost:4200

•	Anonymous users can 
  > Login/Register, 
  > View all books, 
  > View books details, 
  > Leave ratings and comments
  
•	Authenticated users can
  > Buy books, 
  > Rate books, 
  > Comment on books, 
  > View user profiles, 
  > View purchases history, 
  >	Create favorite books list, 
  > Can change own avatar
  
•	Admin users
  > Add books to the store, 
  > Edit books, 
  > Delete books, 
  > Edit/Delete offensive user comments, 
  > Block/Unblock user from commenting, 
  > Change unappropriate user avatars

We have checked the functionality of the files on the below environment
Angular CLI: 13.1.3 / Node: 14.18.3 / Package Manager: npm 8.3.1/OS: linux x64 / MongoDB: MongoDB shell version v4.4.11

