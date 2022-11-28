# Object-Relational Mapping (ORM) | E-Commerce Back End 

## Description 
This application is the back end for an e-commerce site. It takes a working Express.js API and configures it to use Sequelize to interact with a MySQL database.

This application demonstrates the use of Object-Relational Mapping (ORM). 

## Installation 
The user should clone the repository from GitHub and download Node and mysql2. 

Add a .env file to the root of the app with the following details: 
```text
DB_NAME='ecommerce_db'
DB_USER='root'
DB_Password='Enter Your Password Here'
```
Run the following commands in your terminal to make sure the application works correctly: 
* `` npm install `` or `` npm i `` to download the npm packages to run this application.
* `` mysql -u root -p ``
* Enter your password for mysql
* `` source db/schema.sql; ``
* `` exit ``
* `` node seeds/index.js `` 
* `` node server.js `` or `` npm start `` to start the application. 

## Mock Up 

### GET Routes 
![GET Routes](./assets/images/GET-Routes.gif)

### POST, PUT, DELETE Routes 
![POST PUT DELETE Routes](./assets/images/POST-PUT-DELETE-Routes.gif)

View walk through video - [Demo Video](https://drive.google.com/file/d/1l5N6SHfeVcNRSB0T4PJ6zV3q-UyMctSX/view)