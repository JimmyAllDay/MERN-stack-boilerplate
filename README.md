# MERN Stack Boilerplate

This is a boilerplate app for a MERN stack application. It's built using create-react-app and the MongoDB walkthrough tutorial.

It updates a MongoDB Atlas instance using CRUD operations.

Current dependencies include those in the c-r-a toolchain, bootstrap, react-router, express, dotenv, and cors.

To prepare the app for further development, instantiate a MongoDB Atlas instance, clone the repo and run npm install in each of the server and client directories, rename config.env2 to config.env, and update it with the MongoDB username, password and cluster info.

Note: For development purposes, you will get a server error if you don't add your IP address to the Network Access tab within your instantiated Mongo database. You can set the IP address to 000.000.0.0 for development purposes, if it's appropriate to do so.
