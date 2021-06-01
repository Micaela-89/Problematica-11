# 'BECOME A QA AUTOMATION' - Week 11 - Node & Express.

## Description
This project consists of creating a web server to handle HTTP requests and responses from the data entered in the Login and Register Forms, created during week 10 (https://github.com/Micaela-89/Semana-10)

The objective is, once the user submits the form,to make an HTTP call with the data entered. The server will receive this call and process it. Once the call is processed, the server will send a response to the browser with the result of the processing.

## Technology stack
* [Node.js](https://nodejs.org/es/docs/)
* [Express.js](https://expressjs.com/es/) 

## Installation 

**After downloading the project from this repository, the following procedures are needed before tests can be run:**

 (You should use the following commands, either on the git or on the VS console)

* $ npm install
* $ npm init to create a package.Json 
* $ npm install express --save

 *The package.Json should contain the following script:*
 
      "scripts": {
        "start": "nodemon index.js",
        "dev": "nodemon index.js"
      },

## Starting the server 
 (You should use the following commands, either on the git or on the VS console)
 
* $ npm start

## Opening the forms  (Once the server was started to run)

*   [Login](http://localhost:4000/login)
*   [Register](http://localhost:4000/register)

## Author
Micaela Casais
