# E-Commerce-Back-End-Provider

## Description

The purpose of this program is to provide a functional back-end server for retreiving and storing records within a personalized database for the purpose of E-Commerce.

This program utilizes node.js as well as the npm packages 'express' for handling server routing, 'mysql2' for communicating with the database, 'dotenv' for storing and using sensitive information such as a database username and password, and 'sequelize' for easy translation of database information into js objects for use in code. 

## Installation

This program was built and tested using node.js v16.19.0.

After cloning this repository into a working folder of your own, you'll need to run the following command to pull in the node packages required to run the program.

```md
npm install OR npm i
```

## Usage

Before running the server, you should navigate to the 'db' folder, setup the schema, and also seed the database in order to have data to display and manipulate by running the following commands after logging in through the SQL Client:

```md
source schema.sql
```

After installation and setting up the database schema, you can run the seed information to the database and then run the server by typing in the root folder:

```md
npm seed
npm start
```

This will bring up a message:

```md
App listening on port 3001!
```

## Testing

From here you can test the established API routes by using a program such as Insomnia.

## Demo

Here is an external link to a video demonstrating how the program should run: [Google Drive](https://drive.google.com/file/d/1nYgJwubMo5YDdqJ61N9l5b0WrVhfDGMR/view)