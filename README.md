# E-Commerce-Backend
![badge](https://img.shields.io/badge/license-MIT-blue.svg)

Internet retail, also known as e-commerce, is the largest sector of the electronics industry, generating an estimated $29 trillion in 2019. E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. The goal of this project was to understand the fundamental architecture of these platforms.

The E-Commerce Backend is a REST API for an internet retail website. The API is built onto an Express.js server that uses Sequelize to interact with a MySQL database. Sequelize is a promise-based Node.js ORM(Object Relation Mapping) for Postgres, MySQL, MariaDB, SQLite and Microsoft SQL Server.

This E-Commerce backend has the API routes that point to each of the standard CRUD operations for each data group. The routes can be used to:

* Create categories, products, tags
* View categories, products, tags
* Establish associations between the different entities
* Update categories, products, & tags
* Delete entries from the database

## Table Of Content
* [Technologies](#technologies)
* [Installation](#installation)
* [Usage](#usage)
* [License](#license)

## Technologies

Project is created with 
* [Javascript](https://www.javascript.com/)
* [Node.js](https://nodejs.org/en/)
* [Sequelize](https://www.npmjs.com/package/sequelize)
* [MySQL2](https://www.npmjs.com/package/mysql2)
* [Express](https://www.npmjs.com/package/express)
* [Dotenv](https://www.npmjs.com/package/dotenv)

## Installation

Install dependencies 
```terminal
npm init -y
``` 
```terminal
npm install express sequelize mysql2
```
Open up MySQL shell and input 
```terminal
source db/schema.sql
```
Then quit MySQL shell and input the following in your terminal
```terminal
node seeds/index.js
```
to start running application simply input 
```terminal
npm start
```
Open up Insomnia core to GET, POST, PUT and DELETE from different routes.

## Usage
The application is used to GET data for each route(categories, products, or tags) as well as create, update, and delete data in those routes.<br>
Image showcasing the application running in Insomnia:<br>
![insomnia-test](./Assets/insomnia.png)

Demonstration Video <br>
[Link to the video](https://www.loom.com/share/7a7baa4a81e640a1b708f7e7749b931e?sid=d435a233-0239-41ff-b7bb-5a83ed37b626)

## License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
<br>
This repository is licensed under the MIT license.