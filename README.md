# e-commerce-backend-app

## Description 
The purpose of this project was to hone my backend development skills using various tools and technologies such as MySQL, npm sequelize, npm dotenv, ExpressJS, Insomnia, and npm mysql2. Inspired by the immense scope of the internet retail sector, I aimed to create a backend application that emulates the key principles of the industry.

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Usage 
To use this application, you must git clone this repository to your local computer. Navigate to the repository through the terminal. 
Once, you've done that, log into mysql using the following command:
```bash
mysql -u root -p
```
Now, source the schema:
```bash
SOURCE db/schema.sql;
quit
```
Now, seed the database:
```bash
node seeds/index.js
```
Now, you are ready to start the server using the following command and test the routes using insomnia:
```bash
node server.js
```

Here is a video of me walking through the steps to use this application

![Walk Through](./assets/images/ecommercewalkthrough.gif)


## How to Contribute 
For information on how to contribute or if you have any questions, email me at elva.rothman.developer@gmail.com