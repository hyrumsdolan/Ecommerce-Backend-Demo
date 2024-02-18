# Ecommerce Backend Demo

This project is a simple Express.js API backed by a MySQL database using the Sequelize ORM. It simulates an Ecommerce inventory backend database, allowing for additions, deletions, and editing of items.

## Installation

1. Clone the repository
2. Run `npm install` to install the dependencies
3. Create a [`.env`](command:_github.copilot.openRelativePath?%5B%22.env%22%5D ".env") file and add your MySQL user, password and database name
4. Run `npm run seed` to seed the database
5. Run `npm run start` to start the server

## Usage

The API has routes for:

- Categories: `GET`, `POST`, `PUT`, `DELETE` at `/api/categories`
- Products: `GET`, `POST`, `PUT`, `DELETE` at `/api/products`
- Tags: `GET`, `POST`, `PUT`, `DELETE` at `/api/tags`

## Dependencies

- [express](https://www.npmjs.com/package/express)
- [mysql2](https://www.npmjs.com/package/mysql2)
- [sequelize](https://www.npmjs.com/package/sequelize)
- [dotenv](https://www.npmjs.com/package/dotenv)

## Dev Dependencies

- [nodemon](https://www.npmjs.com/package/nodemon)

## Scripts

- `npm run start`: Starts the server
- `npm run watch`: Starts the server with nodemon
- `npm run seed`: Seeds the database

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.