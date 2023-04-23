
## E-commerce Back End 🚀✨

### Description

This is the back end for an e-commerce site. It uses the latest technologies so that the site owner can compete with other e-commerce companies.

### Table of Contents

* [Installation](#installation)

* [Usage](#usage)

* [License](#license)

* [Contributing](#contributing)

* [Tests](#tests)


### Installation

To install necessary dependencies, run the following command:

```
npm i
dotenv: "^8.2.0",
express: "^4.17.1",
mysql2: "^2.1.0",
sequelize: "^5.21.7"
```

### Usage

This application is used to create a database for an e-commerce site. It uses the latest technologies so that the site owner can compete with other e-commerce companies.

### License

This project is licensed under the MIT license.

### Contributing

If you would like to contribute to this project, please contact me.

### Tests

To run tests, run the following command:

```
mysql -u root -p // to run the mysql shell
node seeds
npm start
```

## User Story

```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database
```

## Mock-Up

The following animation shows the web application's appearance and functionality:


## Links

GitHub Repository: <https://github.com/Vinni99/orm-challenge.git>

Video Walkthrough: <https://drive.google.com/file/d/1ehynxLuOaI5wkmfbBQ1gyPXUUpgADhod/view>
