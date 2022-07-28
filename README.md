# MongoDB API example

In this example we will show you the basics of a api connecting to a the mongodb atlas sample mflix database and pulling the first 10 movies from the example movies collection. 
You also have a way to "POST" a new movie to the collection 

## To get started
- Clone this repo locally
- Rename the dbservices-example.js file to dbservices.js
- go to cloud.mongodb.com and click the "connect" button and choose "connect your application". copy the url that starts with mongodb+srv://...... and paste it with quotes to the right of the = in the bservices.js
- Make sure your cloud.mongodb.com (atlas) has the "sample mflix database"
- run ```npm i``` on the command line (to install all npm dependancies)
- node . (or nodemon .) to start the project 
- Open http://localhost:4000/movies on your browser to see the first 10 movies in the "movies" collection
- Using POSTMAN send a body with a new movie to http://localhost:4000/movie (yes: movies,  singular)