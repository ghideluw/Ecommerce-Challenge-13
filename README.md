# Ecommerce-Challenge-13

## Description
The goal of this project is to utilize an Express.js API and build a backend to an existing e-commerce website. This project will use Sequelize in conjunction with
a MYSQL database to create our models and store the seed data for the database to be retrieved and utilized by the API to relay the relevant information available 
for the e-commerce website so that visitors of the website are able to view the inventory and interact with the website for business needs.
our challenge is to build the back end for an e-commerce site. You’ll take a working Express.js API and configure it to use Sequelize to interact with a MySQL database.

With an available Express.js API, Sequelize will be used to connect to the database given certain environment variables specified like the database name, the MYSQL username,
and MYSQL passowrd. The database schema will outline the model and be used as a guide to available for the seed data to be stored. The information will be available 
on a local server and the test seed data will sync to the MYSQL database upon initiation of the server. GET, POST,PUT, and DELETE routes will be used in Insomina to link
input data from the database to the API linking the backend to the front end and update the database for the website functionality.

## Table of Contents 

- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Installation
The application will require that the user run the following installations in the terminal - "npm install --save dotenv" to use environment variables to
store sensitive data, like your MySQL username, password, and database name. The user must also run "npm install MYSQL2 Sequelize Express.js" in to the command line
as necessary dependencies for the application to work.
What are the steps required to install your project? Provide a step-by-step description of how to get the development environment running.


## Usage
In order to start using the application run npm start in the terminal to connect to the server. Use Insomnia to perform GET, PUT, POST, and Delete requests between 
the API and the server so that the database can be manipulated. Use the schema.sql file in the db folder to create your database workbench or SQL shell commands 
can be used to update and alter the database values.

Seed the Database
After creating the models and routes, run npm run seed to seed data to your database so that you can test your routes.

Sync Sequelize to the Database on Server Start

##SCREENSHOT ![image](https://user-images.githubusercontent.com/111549689/218640019-912b815e-4615-4925-af36-26e6e681b340.png)


## License

MIT License

Copyright (c) [2023] [Luwam Ghide]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

