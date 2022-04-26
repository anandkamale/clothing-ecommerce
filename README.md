Run Locally
Create .env File
duplicate .env.example in backend folder and rename it to .env

Setup MongoDB
Local MongoDB
Install it from here
In .env file update MONGODB_URI=mongodb://localhost/amazona
OR Atlas Cloud MongoDB
Create database at https://cloud.mongodb.com
In .env file update MONGODB_URI=mongodb+srv://your-db-connection

Run Backend
$ cd backend
$ npm install
$ npm start
5. Run Frontend
# open new terminal
$ cd frontend
$ npm install
$ npm start

Topics:
HTML5 and CSS3: Semantic Elements, CSS Grid, Flexbox
React: Components, Props, Events, Hooks, Router, Axios
Context API: Store, Reducers, Actions
Node & Express: Web API, Body Parser,JWT
MongoDB: Mongoose, Aggregation

Features:-
Any user can read data if user wants to order product it need to signin or register first.
Sorting products using rating, price, categories.
Paypal transaction.
CRUD application.
