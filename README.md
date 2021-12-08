# E-commerce back end

## Table Of Contents

- [E-commerce back end](#e-commerce-back-end)
  - [Table Of Contents](#table-of-contents)
  - [Description](#description)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Test](#test)
  - [Links](#links)
  - [Questions](#questions)

## Description

This app is the back end of an e-commerce website. The app allows you to create different categories, products and tags on the database.

## Installation

Package required: </br>

- node.js
- mysql2.js
- sequelize.js
- express.js
- dotenv.js

```bash
npm i
```

## Usage

Firstly we need to create the data base running:

```bash
mysql -u root -p
source db/schema.sql
quit
```

After that we need to seed the database running:

```bash
npm run seed
```

Once the seeds are in the database we can start the server running:

```bash
npm run start
```

Using insomnia you can interact with the database.

## Test

There is no test available for this app.

## Links

Github Link: https://github.com/GrilloGG/e-commerce-back-end

## Questions

If you have any questions you can find me in: </br>
GitHub: https://github.com/GrilloGG </br>
Email: grillo.garnacho@gmail.com
