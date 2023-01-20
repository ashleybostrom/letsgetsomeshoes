# Let's Get Some Shoes!
This project builds the backend for an e-commerce site with Object-Relational Mapping (ORM). This application will use an Express.js API that is configured through Sequelize that interacts with a MySQL datbase and uses CRUD operations.

## Table of Contents:
* [Installation](#installation)
* [Usage](#usage)
* [Walk-Through Video](#walkthroughvideo)
* [Links](#links)

## Installation

### Technology Used:  
* Node.js 
* MySQL database and MySQL2
* Sequelize
* dotenv

### How to start the project:  
1. **Copy link in code dropdown menu:** Copy the link with SSH key to clone the repo
1. **Clone:** In GitBash (Windows) or Terminal (Mac), type `git clone < $link >`
1. **NPM:** From the root directory, type `npm init` to install NPM (Node Package Manager)
1. **Dependencies:** To install all dependencies needed:
* Type `npm i`
* Type `npm i mysql2`
* Type `npm i sequelize`
* Type `npm i dotenv`
1. **MySQL Tables:** 
* Type `mysql -u root -p` then enter password to access MySQL
* Type `source db/schema.sql;` to use the schema files from that database
* Type `quit;` to exit MySQL when you are complete

## Usage
Once the above steps are complete, you are ready to run access your database with the seeds.

In your terminal, type `npm run seed && npm start`

Your application is now ready.

## Walk-Through Video
* [![Watch the video]]

## Links


