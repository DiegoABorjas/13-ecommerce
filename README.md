# 13-ecommerce

## Description
This application was created as a challenge for the KU Coding Bootcamp. Starter code was provided of a working Express.js API, the application uses Sequelize to interact with a MySQL database.

Code syncs Sequelize models to a MySQL database on the server start, includes column definitions for all four models and model associations, and provides GET, POST, PUT, and DELETE routes.

## Video
Here's a walkthrough of the application 

[Video](https://drive.google.com/file/d/1fv4zOI8dfsEBfuhhO2cKUqSuVteEi9JW/view)

## Link to repository:
[Github](https://github.com/DiegoABorjas/13-ecommerce)


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

## Installation
* Clone this project repository to your computer. 
* Use the command `npm i` to install dependencies. 
* Create a file in the root directory titled `.env` and include database name and personal MySQL login information:
```
DB_NAME='YOUR DATABASE NAME'
DB_USER='YOUR USERNAME'
DB_PW='YOUR PASSWORD'
```
* Open MySQL with command `mysql -u root -p` and enter your personal MySQL password. 
* Create databse with command `source schema.sql`.
* Seed database with command `npm run seed`.
## Usage

Run `npm run start` to start running the application

---

## Questions
If you have any questions about the repo, open an issue or contact me directly at diegoborjas@gmail.com. You can find more
of my work at [diegoaborjas](https://github.com/diegoaborjas)