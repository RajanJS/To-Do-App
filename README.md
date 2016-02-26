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
* to get all json data.
````
http://rajan-todo-api.herokuapp.com/todos 
````
* to filter data with id;
````
http://rajan-todo-api.herokuapp.com/todos/1
````
* to filter data with query params; 'q' for filtering with description and 'completed' to filter with completed status
````
http://rajan-todo-api.herokuapp.com/todos?q=Walk
http://rajan-todo-api.herokuapp.com/todos?completed=true
````

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
