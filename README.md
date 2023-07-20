# 13 Object-Relational Mapping (ORM): E-Commerce Back End

## Description

 Build the back end for an e-commerce site by modifying starter code. Moreover, Configure a working Express.js API to use Sequelize to interact with a MySQL database.

## Table of Contents

- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [License](#license)
- [Installation](#installation)
- [Instructions](#instructions)
- [Contributing](#contributing)
- [Questions](#questions)


## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```md
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```

## License 
MIT License

## Installation
1. Clone the repository
2. Install the following: 
- Node.JS [Version 16.18.1](https://nodejs.org/en/blog/release/v16.18.1/)
- Inquirer.js: [Version 8.2.4](https://www.npmjs.com/package/inquirer/v/8.2.4)
- mysql2 (https://www.npmjs.com/package/mysql2)
- Sequelize ( https://www.npmjs.com/package/sequelize)
- dotenv (https://www.npmjs.com/package/dotenv)

## Instructions
💻   
Run the following command at the terminal:
`mysql -u root -p` <br>
`npm run seed` <br>
`npm start`
Please watch the Walkthrough viedo for step by step instructions<br>
https://drive.google.com/file/d/1NhSf1V5wi4tG9vXRYL4bAIXRMsixZQJB/view

## Contributing
Rajni bala : (https://github.com/rbala16)

## Questions
✉️ Contact me with any questions: [Email:]bala12rajni@gmail.com , [Github](https://github.com/rbala16)<br />

## Mock-Up

The following animation shows the application's GET routes to return all categories, all products, and all tags being tested in Insomnia:

![In Insomnia, the user tests “GET tags,” “GET Categories,” and “GET All Products.”.](./Assets/13-orm-homework-demo-01.gif)

The following animation shows the application's GET routes to return a single category, a single product, and a single tag being tested in Insomnia:

![In Insomnia, the user tests “GET tag by id,” “GET Category by ID,” and “GET One Product.”](./Assets/13-orm-homework-demo-02.gif)

The following animation shows the application's POST, PUT, and DELETE routes for categories being tested in Insomnia:

![In Insomnia, the user tests “DELETE Category by ID,” “CREATE Category,” and “UPDATE Category.”](./Assets/13-orm-homework-demo-03.gif)



## Important links

You are required to submit BOTH of the following for review:

* A walkthrough video demonstrating the functionality of the application and all of the acceptance criteria being met.<br>
https://drive.google.com/file/d/1NhSf1V5wi4tG9vXRYL4bAIXRMsixZQJB/view

* The URL of the GitHub repository. Give the repository a unique name and include a readme describing the project.
https://github.com/rbala16/e-commerce-website_rb

