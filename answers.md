### 1. What is responsible for defining the routes of the `games` resource?
server.js in conjunction with create_routers.js, in the "server" folder

### 2. What do you notice about the folder structure?  Whats the client responsible for? Whats the server responsible for?
The "client" "folder is responsible for handling the front-end (displaying the data, and getting data from the user);
The "server" folder is responsible for handling the connection and communication between the front-end and the back-end (database), and defining the routes (urls)

### 3. What are the the responsibilities of server.js?
Creates connection with the database, and handle the routing through create_routers.js

### 4. What are the responsibilities of the `gamesRouter`?
It is used to append specific routes for the different REST (contained in methods to the common prefix of the url '/api/games\'92, passing at the same time the data from the db?!
(Not really sure)

### 5. What process does the the client (front-end) use to communicate with the server?
It passes specific REST request (and data, if required) through specific routes?

### 6. What optional second argument does the `fetch` method take? And what is it used for in this application? Hint: See [Using Fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch) on the MDN docs
The method to use if we want to delete a record, and the method plus the data if we want to add a new record

### 7. Which of the games API routes does the front-end application consume (i.e. make requests to)?
GET, POST and DELETE

### 8. What are we using the [MongoDB Driver](http://mongodb.github.io/node-mongodb-native/) for?
To create a dependency in the package.json file and establish a connection with the db?}