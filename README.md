# ChirpChirp!
Project created by Daniele Biagio De Luca.
## Overview
ChirpChirp! is a project developed for the "Programmazione 3" (Coding 3) exam of the Parthenope University of Naples. It is a microblogging web platform which allows users to send 140 characters posts, with or without hashtags. They can even follow other users on the site and view their updates. Besides this, the platform enables users with administrator permissions to access to a special section of the site where they can view a list of all of users with the number of published posts; categorise messages by hashtags and find them based on a word inputted by the admin.
## Used language and libraries/frameworks
The front-end of the web application has been created with HTML, Bootstrap, CSS and Javascript with the JQuery library. The back-end has been developed using the Web Application server Apache Tomcat, Java and some libraries:
* **Java Database Connectivity** (JDBC) to connect to a SQL Database (Oracle in my case) and perform CRUD operations;
* **MongoDB Java drivers** to connect to a MongoDB database;
* **Bson library** which contains different interfaces (such as Document) needed to operate with the methods provided by the MongoDB library;
* **Gson library** which is a library developed by Google and it's used to convert objects to JSON and the other way round.
## Used design patterns
* Singleton;
* Factory Method;
* Facade.
