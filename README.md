# e-commerce-retail-backend

## Description

This project is the back end for an e-commerce website, built using Express.js and Sequelize to interact with a MySQL database. It allows the user to manage categories, products, and tags for an online store.

The motivation behind this project is to create a functional back end for an e-commerce website, using the latest technologies and best practices in web development. This will enable the company to compete effectively in the growing e-commerce industry.

This project solves the problem of managing and organizing product data in an e-commerce platform. By providing API routes to create, read, update, and delete categories, products, and tags, it allows for efficient management of the online store's inventory.

Through this project, I learned how to set up a Sequelize-based Express.js API, create and associate database models, use environment variables to store sensitive data, and implement RESTful CRUD operations for managing data.

## Table of Contents 

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation

To install and run the application, follow these steps:

1. Clone the repository to your local machine.
2. Navigate to the project directory in the terminal.
3. Run the following command to install the required dependencies: npm install
4. Create a .env file in the root directory and add your MySQL database details as follows:
- DB_NAME=your_database_name
- DB_USER=your_mysql_username
- DB_PASSWORD=your_mysql_password
5. Set up your MySQL database by executing the SQL commands provided in the seeds.sql file. This will create the necessary tables and populate them with sample data.
6. Update the database connection configuration in the server.js file with your MySQL credentials.
7. Seed the database by running the following command line: npm run seeds
7. Start the application server by running the following command: npm start

## Usage

This project provides API routes to manage categories, products, and tags for an e-commerce website. You can test these routes using tools like Insomnia or Postman.

API Routes
* Categories:

    GET /api/categories: Get all categories.
    GET /api/categories/:id: Get a single category by ID.
    POST /api/categories: Create a new category.
    PUT /api/categories/:id: Update a category by ID.
    DELETE /api/categories/:id: Delete a category by ID.
* Products:

    GET /api/products: Get all products.
    GET /api/products/:id: Get a single product by ID.
    POST /api/products: Create a new product.
    PUT /api/products/:id: Update a product by ID.
    DELETE /api/products/:id: Delete a product by ID.
* Tags:

    GET /api/tags: Get all tags.
    GET /api/tags/:id: Get a single tag by ID.
    POST /api/tags: Create a new tag.
    PUT /api/tags/:id: Update a tag by ID.
    DELETE /api/tags/:id: Delete a tag by ID.

Git Hub Repository:

https://github.com/Jalzu1007/e-commerce-retail-backend.git

Walkthrough Video:

Watch the Walkthrough Video to see the functionality of the e-commerce back end in action. The video demonstrates the following:

[![e-commerce-retail-backend](https://img.youtube.com/vi/7dnvO_T9bIc/0.jpg)](https://youtu.be/7dnvO_T9bIc)

- Creating the database schema from the MySQL shell.
- Seeding the database with test data.
- Starting the application server.
- Testing various API routes using Insomnia, including GET, POST, PUT, and DELETE operations for categories, products, and tags.

## Credits

I used the following third-party assets in this project:

- https://sequelize.org/master/
- https://sequelize.org/master/manual/model-basics.html
- https://sequelize.org/master/manual/model-basics.html#data-types
- https://sequelize.org/master/manual/assocs.html
- https://sequelize.org/master/manual/model-querying-basics.html
- https://sequelize.org/master/manual/model-basics.html#taking-advantage-of-models-being-classes
- https://sequelize.org/master/manual/validations-and-constraints.html
- https://www.npmjs.com/package/dotenv
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/async_function
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/try...catch
- https://en.wikipedia.org/wiki/Representational_state_transfer#Applied_to_web_services
- https://developer.mozilla.org/en-US/docs/Web/HTTP/Status
- https://www.npmjs.com/package/bcrypt
- https://eslint.org/docs/user-guide/configuring

## License

N/A