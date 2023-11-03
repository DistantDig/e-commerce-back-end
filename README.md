![Static Badge](https://img.shields.io/badge/License-MIT-yellow)


  # E-Commerce Back End


  ## Description


  This project is functionally a back-end database that holds tables for different things relating to internet retail. This project was designed to allow myself to practice object relational mapping, and a majority of the code was supplied by the edx bootcamp through UC Berkeley.


  ## Table of Contents


  - [Installation](#installation)
  - [Usage](#usage)
  - [Credits](#credits)
  - [License](#license)
  - [Contributing](#contributing)
  - [Tests](#tests)


  ## Installation


  To install this project, start by cloning the repository down to your local machine. Once the project is cloned, navigate into the source folder and execute the command 'npm i' in your terminal to install all of the needed dependencies. After that is complete, you will need an application to run sql commands such as MySQL Workbench. Inside the 'db' folder is an sql command which you will need to execute in Workbench to create the needed database. After the database has been completed, you can return to your terminal and run the command 'npm run seeds' and the database will be populated with all of the needed data. Lastly, rename the .env.EXAMPLE file to be just .env and enter your user name and password within it. After saving the file, you can then run npm start to run the server on your local machine.


  ## Usage


  Once the project has been successfully installed and the server starts, you can now interact with the database via another third party application such as Insomnia to perform get, post, pull and delete requests. The base url for the application is 'http://localhost:3001' which all other requests build off of. In order to interact with each of the tables within the database, you must enter '/api/:table/:id' to the end of the url where ':table" is the name of the table you wish to interact with and ':id' is the id number of the row you wish to request. The id is optional in get requests, required with put and delete requests, but cannot be included with post requests. Simply entering 'http://localhost:3001/api/categories' as a get request will return a list of all categories for example.


  ## Credits


  This project was designed by DistantDig. Their Github profile can be found [here](https://github.com/DistantDig), and they can be reached via email at jameswaller711@gmail.com.


  ## License


  This project is covered under the MIT license. The full documentation on this license can be found [here](https://opensource.org/licenses/MIT)


  ## Contributing


  Feel free to fork the project and create pull requests should you wish. I am always happy to find new ways to grow!


  ## Tests


  No automatic methods of testing are included in this project, however feel free to fork the project and add some! Otherwise feel free to just experiment with the project and create issues for any odd behavior.