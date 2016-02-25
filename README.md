## Todo API
Simple NodeJS Todo API with CRUD (GET, POST, DEL, PUT) functionalites.

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

##### Features:
* Used [Express.js](http://expressjs.com/) to create web app.
* Developed using [Postman](http://www.getpostman.com/)
* Used [Underscore.js](http://underscorejs.org/) to refactor the code.
* Used [Body-parser](https://www.npmjs.com/package/body-parser-json) body parsing middleware.
* Used [Sequelize](http://docs.sequelizejs.com/en/latest/) ORM.
* Used [Sqlite](https://www.sqlite.org/) DB for data storage in local environment.
* Used Heroku [Postgresql](https://www.heroku.com/postgres) DB for production environment.

###### Author: [Rajan Maharjan](http://mrajan.com.np/)
