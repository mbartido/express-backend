# express-backend

An express REST API. We have a model for a mongoDB database, routes to serve up GET, POST, PUT, and DELETE endpoints, and a controller with important functions that the routes use.

# Prereqs
To run this you'll need to have mongoDB set up on your environment. Install the latest one on the website.

# Install
1. npm install
2. mongod
    * If this doesn't work and your're running Windows, look up where your mongoDB is installed and then copy the location where mongod is located. Put this in your environment variables and then you should be able to run this command.
3. npm start
4. You can now run any of these using [Postman](https://www.getpostman.com/) :
    * localhost:3000/contact
    A GET gets all the user in the database. A POST adds a new user in the database.
    * localhost:3000/contact/:contactID
    A GET gets the specific contact with the contact ID.. A PUT updates the user with contact ID in the database . A DELETE deletes the contact with the contact ID.



