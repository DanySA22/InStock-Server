# Table of Contents
+ [Project Title](#project-title)
   + [Overview](#overview)
      + [Benefits](#benefits)
      + [Features](#features)
   + [Implementation](#implementation)
      + [Tech Stack](#tech-stack) 
      + [Installation Instructions](#installation-instructions) 
   + [Next Steps](#next-steps)


# Project Title

In-Stock

## Overview

This collaborative project turns out on a fully responsive full-stack website that reproduce a warehouse website that allow the user to visualize, create, modify, and eliminate all type of item products and all type of warehouses.

It was a great experience to implement Git Flow and GitHub best Practice under an Agile work environment using JIRA.

**This project software developers collaborators where:**

+ Indira Pandey

+ Travis Chung

+ Toba Omoniyi

+ Abdulrahman Aljuobori

### Benefits

This application allows the user to create, read, update, delete warehouse and they related inventory items information.


### Features 

+  User possibility to see the different warehouse relevant information like name, address, contact information; but also the possibility to add a new warehouse with all the necessary information, update a warehouse information, and delete a warehouse information.


+ User possibility to see the different inventory items relevant information like name, category, status, quantity; but also the possibility to add a new inventory item with all the necessary information, update an item information, and delete an item information.

+ User possibility to visualize what items inventory are present in each one of the warehouses.


## Implementation

### Tech Stack

We used the MERN stack:

+ Styling: Sass 

+ Client-Side functionality: React.js, Axios library  

+ Database: MySQL (SQL), Knex.js (query builder)

+ Server-side functionality:  Node.js, Express.js  


### Installation Instructions

1. Clone the main branch from client and backend repositories. Below the links:

(https://github.com/DanySA22/InStock-Server.git)

(https://github.com/DanySA22/InStock-Client.git)

2. Make sure you have locally installed node.js and npm, and then run npm install in both folders with the cloned repositories.

3. Add a .env file on server folder that mimic the next keys with your own values:

PORT=*number*

DB_HOST=*localhost/port*

DB_NAME=*your_prefered_name*

DB_USER=*your_prefered_user*

DB_PASSWORD=*password*

4. Set your MySQL local server. On the server express app, run npm run migrate and npm knex seed:run to set up MySQL configured tables and populated with testing data.

5. Use npm start to run the client app and npm run dev to run the server app.



## Next Steps

+ We would like to add authentication system to include data saved information as well as a shopping cart functionality to add the possibilities that users can buy the items on inventory on the different warehouses.

+ We would like to add a search functionality with multiple filters type.