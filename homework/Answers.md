# games_app_hw

1. What is responsible for defining the routes of the `games` resource?
The CRUD functions in create_router.js

2. What do you notice about the folder structure?  Whats the client responsible for? Whats the server responsible for?
The folder structure is separated by function - front and back ends. The client folder is responsible for the front end(form), while the server folder is responsible for the back end(database and express)

3. What are the the responsibilities of server.js?
Connects front end and back end.

4. What are the responsibilities of the `gamesRouter`?
To connect the routes with the database

5. What process does the the client (front-end) use to communicate with the server?
The post function after filling out the form

6. What optional second argument does the `fetch` method take? And what is it used for in this application? Hint: See [Using Fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch) on the MDN docs


7. Which of the games API routes does the front-end application consume (i.e. make requests to)?
Get, post, delete

8. What are we using the [MongoDB Driver](http://mongodb.github.io/node-mongodb-native/) for?

