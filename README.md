# Airline-reservation
## Description ##
Using this website user can register, login, search for a flights, book the tickets and cancel the tickets.

## Technology Stack ##
* Backend Server -> Nodejs
* Authentication -> Passport.js
* Middleware Framework -> Express.js
* Node Database Driver -> mysql
* DataBase -> MySQL
* Frontend -> HTML, CSS, Javascript, Bootstrap, jQuery, EJS

## Set up ##
* Install nodejs and mySql database server
* Change your database connectivity details in `./config/db_conf.js`
* Run create_table_scripts.js in setup_scripts folder(`node ./setup_scripts/create_table_scripts.js`)
* Run sql statements in `load_data.sql`(In mySql shell)(run the statements in the order of tables created in create_table_scripts)

## How to Run ##
* Run `node server.js` Port can be changed in server.js
* open browser and hit 'http://localhost:port/airlineReservation'
