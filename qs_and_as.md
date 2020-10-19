## Homework: Full Stack Games Hub App

### Questions

1. What is responsible for defining the routes of the `games` resource?
    * The create_router.js file, within server/helpers

2. What do you notice about the folder structure?  Whats the client responsible for? Whats the server responsible for?
    * They are structured for front-end and back-end responsibilities. client = front-end, server = back-end

3. What are the the responsibilities of server.js?
    * Passing data between the server and the Mongodb database.

4. What are the responsibilities of the `gamesRouter`?
    * Directing front-end requests to the relevant API.

5. What process does the the client (front-end) use to communicate with the server?
    * RESTful processes

6. What optional second argument does the `fetch` method take? And what is it used for in this application? Hint: See [Using Fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch) on the MDN docs
    * It can take a second argument of an 'init' object. In this app it is used to specify the data is stored as json.

7. Which of the games API routes does the front-end application consume (i.e. make requests to)?
    * http://localhost:3000/api/games/

8. What are we using the [MongoDB Driver](http://mongodb.github.io/node-mongodb-native/) for?
    * I've no idea, as I can't see that anywhere.