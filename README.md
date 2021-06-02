# E-Commerce-Backend

![Screen Shot](assets/E-Commerce01.png)

## Description ![](https://img.shields.io/badge/License-MIT-yellow.svg)
Our clients are in the process of creating an online store and needed some help in building the back-end functionality.  We created some models & routes for them to use.

[Walkthrough Video](https://drive.google.com/file/d/1mWCLKPy30O50la0oHR80dt8Vlf_5rtJa/view?usp=sharing)

![Screenshot](assets/E-Commerce02.png)
SQL database creation

![Screenshot](assets/E-Commerce03.png)
Database seeding

## Installation
- Clone the repository
- Run ```npm i``` to install dependancies
- Enter database, username and password
- Create the Database using the SQL Shell:
    - in the terminal run ```mysql -u root -p```
    - enter your mysql password
    - type ```source db/schema.sql```
    - enter ```quit``` to exit SQL shell
- Seed the database with test data using ```npm run seed```

## Usage  
- Run ```npm start``` to start the server.
- Using Insomnia Core, use routes for Categories, Products & Tags on ```localhost:3001``` e.g. ```localhost:3001/api/categories/``` | ```localhost:3001/api/products/``` | ```localhost:3001/api/tags/```


## Technologies
- Node.js, using express, dotenv, sequelize
- SQL

## License 
This project is licensed under ![License: mit](https://img.shields.io/badge/License-MIT-yellow.svg)

For more information, please visit: https://opensource.org/licenses/MIT
