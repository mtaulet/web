# REST API

The **app.js** file contains functional boilerplate code for the basics of creating a RESTful API.

Its goal is the creation and maintenance of a blog made up of articles.
The underlying database is MongoDB with the mongoose module.

The file contains code for following HTTP requests:

- GET (Read)
- POST (Create)
- PUT & PATCH (Update)
- DELETE (Delete)

To start up the MongoDB server in your local machine, use the mongod command and specify a filesystem path to your database:

`mongod --dbpath /usr/local/var/mongodb`

Personally, I have used Robo 3T to visualize my database, as it provides a nice grafical user interface: https://robomongo.org/
An alternative is to use the mongo shell which can be access by:

`mongo`

To set up your server:
- Inside the directory containing your server app.js file, initialize npm:
`npm init`

- Install the following modules: bodyparser, mongoose, ejs, and express
`npm i body-parser mongoose ejs express`

To test my API without a frontend, I have used Postman to make requests: https://www.postman.com/
