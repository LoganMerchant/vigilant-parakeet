
[![License Badge](https://img.shields.io/badge/License-MIT_License-blueviolet.svg)](https://shields.io/)

# Vigilant Parakeet


## Description
This is an example backend for an e-commerce website. You can create a database through your MySQL shell, seed the database with data, and perform various CRUD methods on the database via Sequelize.


## Table of Contents
  * [Installation](#installation)
  * [Usage](#usage)
  * [How to Contribute](#how-to-contribute)
  * [Licenses](#licenses)
  * [Questions](#questions)


## Installation
To install the necessary components, you will need to clone this repository onto your local machine, navigate to the cloned repository and run `npm install` via the command line.


## Usage
In order to use this project, you must first create the database. The easiest way for me is to log into the MySQL shell and typing `source db/schema.sql` (make sure youre in the root directory for the cloned resository). After creating the database, you can seed it with data by running `npm run seed` in your regular command line. 
<br>
In order to connect to the database, you will need to create a `.env` file with `DB_NAME=ecommerce_db`, `DB_USER=<your-mysql-username>`, and `DB_PW=<your-mysql-password>`. Add this file to a `.gitignore` if you plan to publish it anywhere. Now you can enter `npm run start` in your command line to connect to the database, and start the server.
<br>
You are now free to perform the various CRUD methods on the database in your browser, or in Insomnia, Postman, etc.


## How to Contribute
The application will need a front in the future, which may be forthcoming shortly. Other than that, not much is to be contributed at this time.


## Licenses
This project is registered with the following license(s), to find out more visit [Choose a License](https://choosealicense.com/licenses):
* MIT License

## Questions
Check me out on [GitHub](https://www.github.com/loganmerchant). 
<br>
<br>
If you have any further questions, please reach out here: merchantclogan@gmail.com
  
