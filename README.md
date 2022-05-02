# ECommerce BackEnd Project

## Table of Contents
### -[links](#links)
### -[Installation](#installation)
### -[Technologies](#technologies)
### -[Questions](#questions)

## Links
### Screencastify Walkthrough

https://drive.google.com/file/d/1BmJ0-rd75aeg5XP9sjAMo_f5SLLQ4qki/view

## Description
This project requires the creation of a backend for an online retail store. Using MySQL2, we were tasked with connecting to a database that could store all of the necessary data for the store. With Sequelize and Express, connect to the database and make it possible to use different routes to navigate a theoretical front end. Using Sequelize's Model concepts, we could navigate data-handling with ease.

This project requires several different types of requests--GET, POST, PUT, and DELETE. In the GET requests, there were two options--findAll or findOne. In the findAll requests, the user should be able to search just 'categories/' or 'products/' and find all of the corresponding objects. For the findOne, the user needs to know the id of whatever category/etc. they are looking for, in order to access the request. For instance, '/categories/2' should return the category with the correct id of 2. 

The POST request is fairly straightforward--take the JSON data that the user inputs into insomnia and POST it to the corresponding array of objects (like categories). In the PUT request, the user should be able to change part of their data and update it in the array. Again, the user needs to know the correct id in order to find the object they are looking for. If they want to update the category with the id of 2, they must use 'categories/2'. DELETE requests are similar; use the correct id in order to delete that object from the array.
  
## Installation
### Instructions for Project Installation:
This product utilizes MySQL2, Sequelize, and dotenv packages. Be sure to run 'npm i' in order to install these packages before use.
  
## Technologies
### Built With:
This project is primarily built with JavaScript. It also uses MySQL2, Sequelize, and dotenv.
  
## Questions
### Please reach out with any questions or concerns!
Github: https://github.com/mtpott

Email: mtpott23@gmail.com