Project: WeLoveMovies
I've been hired on as a backend developer for a new startup called WeLoveMovies! As another developer works on the design and frontend experience, I have been tasked with setting up a database and building out specific routes so that users can gain access to data about movies, theaters, and reviews.

TASKS

Install and use common middleware packages.
Receive requests through routes.
Running tests from the command line.
Access relevant information through route and query parameters.
Create an error handler for the case where a route does not exist.
Build an API following RESTful design principles.
Create and customize a knexfile.js file.
Create a connection to your database with Knex.
Write database queries to complete CRUD routes in an Express server.
Return joined and nested data with Knex.
Write database migrations using Knex's migration tools.
Deploy your backend server to a cloud service. It's not necessary to deploy the frontend.

DATABASE TABLE TASKS

You will create five tables for this project. View the docs/tables/ folder in this project to get more detailed information on each table.
You will need to create migrations for each of these tables and run those migrations.
Seed data is included in this project in the ./src/db/seeds folder. The seeds will run correctly if and only if the tables are setup as described in the previous documents.

GENERAL TASKS

Your app.js file and server.js file are correctly configured, with your app.js file exporting the application created from Express.
You make use of the cors package so that requests from the frontend can correctly reach the backend.
If a request is made to a route that does not exist, the server returns a 404 error.
If a request is made to a route that exists, but the HTTP method is wrong, a 405 error is returned.
All of your routes should respond with the appropriate status code and should use a data key in the response.