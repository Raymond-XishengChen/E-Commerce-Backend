# Object-Relational Mapping (ORM): E-Commerce Back End

## Description

This application creates an E-Commerce Back End, using Express.js API, Sequelize and MySQL2 database and dotenv.
Allows user to make API calls to fetch data from Categories, Tags and Products.
Call functions include Gets, Get by IDs, Posts, Updates and Deletes.

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

## Mock-Up

The following animation shows the application's GET, GET by IDs, Post, Update and Delete in "Tags" in Insomnia:

![In Insomnia, the user tests GET, GET by IDs, Post, Update and Delete in "Tags".”.](./Assets/tags-calls.gif)

The following animation shows the application's GET, GET by IDs, Post, Update and Delete in "Categories" in Insomnia:

![In Insomnia, the user tests GET, GET by IDs, Post, Update and Delete in "Categories"..”](./Assets/category-calls.gif)

The following animation shows the application's GET, GET by IDs, Post, Update and Delete in "Products" in Insomnia:

![In Insomnia, the user tests GET, GET by IDs, Post, Update and Delete in "Products"..”](./Assets/product-calls.gif)

The following animation shows the entire walkthrough of the application:
[Walkthrough Video](https://watch.screencastify.com/v/YKXsHTgMFWbrJP1BujA6)

![App Walk-through gif](./Assets/insomnia-walkthrough.gif)

![](./Assets/insomnia-walkthrough.webm)

## Installations

To set up the application, the following steps are required:
Connecting to MySQL:
`mysql -u root -p`

Building database:
`SOURCE schema.sql`

Quit mySQL shell.
Install all dependencies of the application:
`npm install`

Seeding the files:
`npm run seed`

Connecting to localhost
`npm start`
