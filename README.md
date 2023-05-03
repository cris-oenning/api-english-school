# API system for controlling classes at an English school:

This is a system developed in Node.js with ORM Sequelize and MySQL to control classes in an English school. The main objective of this system is to manage the school's classes, students and teachers, allowing administrators to create, update, read and delete information related to classes and students.

# How the System Works:

The system is developed in the MVC (Model-View-Controller) architecture pattern, where the model layer manages the connection with the database and the CRUD operations, the control layer is responsible for making the connection with the models and perform the necessary operations, and the visualization layer is responsible for showing the information to the user.

The system uses the Sequelize ORM to manage the database connection and to perform CRUD operations. Sequelize is a very popular ORM that simplifies working with relational databases and allows us to use the JavaScript language to perform database operations.

Express was also used to access the database

# How to use:

Requires Node.Js version 18 (or higher) installed. -> https://nodejs.org/

1. Install Node.Js 18 (or higher) from the official website https://nodejs.org/, if not installed.
2. In the terminal, type "npm install express" for database access.
3. In the terminal, type "npm install body-parser" to convert the data to JSON type.
4. In the terminal, type "npm install --save-dev nodemon" to speed up the development.
5. In the terminal, type "npm run start"
6. In the terminal, type "npm install mysql2" for database installation.
7. In the terminal, type "npm install sequelize-cli path" for using the sequelize ORM.
8. In the terminal, type "npx sequelize-cli init" to run the deponents locally.

# Expansion:

With this code base, you can further expand the features of this API, as we will always have features to add and refine errors, tests, creating your own features depending on your needs.