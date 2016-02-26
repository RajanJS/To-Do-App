## Todo API
Simple NodeJS Todo API with CRUD (GET, POST, DEL, PUT) functionalites with authentications.

#### To use this application
* Clone this application or download as zip.
* Run the following scripts;
```
npm install
node server.js

```
##### To use API
* to create new user (POST) request.
```
http://rajan-todo-api.herokuapp.com/users
```
* to login with created user (POST) request.
```
http://rajan-todo-api.herokuapp.com/users/login
```
* to delete/logout user (DELETE) request.
```
http://rajan-todo-api.herokuapp.com/users/login
```
* to add todos (POST) request.
```
http://rajan-todo-api.herokuapp.com/todos
```
* to delete todos with id; (DEL) request.
```
http://rajan-todo-api.herokuapp.com/todos/1
```
* to get all json data (GET) request.
````
http://rajan-todo-api.herokuapp.com/todos 
````
* to filter data with id (GET) request.
````
http://rajan-todo-api.herokuapp.com/todos/1
````
* to filter data with query params (GET) request; 'q' for filtering with description and 'completed' to filter with completed status
````
http://rajan-todo-api.herokuapp.com/todos?q=Walk
http://rajan-todo-api.herokuapp.com/todos?completed=true
````
* to update todos with id ; (PUT) request.
```
http://rajan-todo-api.herokuapp.com/todos/1
```

#### For live API :
[Todo API](http://rajan-todo-api.herokuapp.com/)

##### Used libs.:
*  [Express.js](http://expressjs.com/) to create web app.
*  [Postman](http://www.getpostman.com/) for easy developement.
*  [Underscore.js](http://underscorejs.org/) to refactor the code.
*  [Body-parser](https://www.npmjs.com/package/body-parser-json) body parsing middleware.
*  [Sequelize](http://docs.sequelizejs.com/en/latest/) ORM.
*  [Sqlite](https://www.sqlite.org/) DB for data storage in local environment.
*  Heroku [Postgresql](https://www.heroku.com/postgres) DB for production environment.
*  [bcrypt](https://www.npmjs.com/package/bcrypt) for hashing passwords.
*  [jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken) for web token implementation.
*  [crypto-js](https://www.npmjs.com/package/crypto-js) to encrypt data with secret key.
*  [pg](https://www.npmjs.com/package/pg) PostgreSQL client for heroku production env.
*  [pg-hstore](https://www.npmjs.com/package/pg-hstore) for serializing and deserializing JSON data in to hstore format.

###### Author: [Rajan Maharjan](http://mrajan.com.np/)
