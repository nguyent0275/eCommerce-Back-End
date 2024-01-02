# eCommerce-Back-End

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Technologies
![Technologies](https://img.shields.io/badge/-Git-F05032?logo=Git&logoColor=white)
![Technologies](https://img.shields.io/badge/-JavaScript-007396?logo=JavaScript&logoColor=white)
![Technologies](https://img.shields.io/badge/-Node.js-339933?logo=Node.js&logoColor=white)
![Technologies](https://img.shields.io/badge/-npm-CB3837?logo=npm&logoColor=white)
![Technologies](https://img.shields.io/badge/-MySQL-4479A1?logo=MySQL&logoColor=white)

## Table of Contents
[Description](#description)<br>
[Installation](#installation)<br>
[User Story](#user-story)<br>
[Acceptance Criteria](#acceptance-criteria)<br>
[Questions](#questions)<br>
[Links](#links)<br>
[License](#license)<br>

## Description
The backend for an e-commerce site build with a Express.js API configured with Sequelize to interact with a MYSQL Database. To test the routes, run the command:
```
npm start
```
## Installation
***Requirments***

[Node.js](https://nodejs.org/en/) | [MySQL](https://www.npmjs.com/package/mysql2) | [Postman](https://www.postman.com/downloads/)

***Initial Cloning/Download:***
1. Clone the repository or download the zipfile from Github.
2. Open the file/repo in your preferred code editor.
3. Open the integrated terminal in the root folder.
4. Make sure you have Node.JS installed.

***Initial SQL setup:***
1. Open the intergrated terminal in the ```db``` folder.
2. Run the command ```mysql -u root -p```.
3. Login with your credentials.
4. Run the command ```source schema.sql``` to create the database.

***Setting up .env file:***
1. Copy the ```.env.EXAMPLE``` file in the ```Develop``` folder and rename it to ```.env```.
2. Fill out the ```DB_...``` with your credentials.

***Starting the Server:***
1. Open the intergrated terminal in the ```Develop``` folder.
1. Run the command ```npm i``` to install any necessary packages.
2. Run the command ```npm run seed``` to populate the database.
3. Run the command ```npm start``` to start the server.

## User Story
```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria
```
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database
```
## Questions

What is my github repository?<br>
https://github.com/nguyent0275

What is my email and how can you reach me?<br>
My email is nguyentoan0275@gmail.com, please feel free to send me an email with any questions regarding projects or colllaborations.

## Links
![Postman Routes](./assets/images/command_line.png)

A link to the [Video](link):
```
link
```
A link to the [repository](repo link):
```
https://github.com/nguyent0275/eCommerce-Back-End
```


## License
eCommerce-Back-End is licensed under the MIT (or any later version). Refer to the LICENSE.txt.