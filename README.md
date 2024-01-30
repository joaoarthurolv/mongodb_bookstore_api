# Bookstore API
## _A MongoDB Bookstore API developed with Node.js to improve my skills at NoSQL databases_

## Features

- Insert a book
- Fetch all books and a single book by its id
- Delete a book based on its id
- Update a book based on its id

## Installation

The Bookstore API requires [Node.js](https://nodejs.org/) and [MongoDB](https://www.mongodb.com/) to run.

After installing both Node.js and MongoDB, clone the project and run the following commands:

```sh
cd node_api
npm i
node app
```

We're all set. The app is listening on the port 3000. You can open your API testing plataform and test the endpoints listed bellow.

## Endpoint routes

- (GET) /books - Retrieve all the books.
- (GET) /books/:id - Retrieve a book by its id.
- (POST) /books - Insert a book 
- (DELETE) /books/:id - Delete a book by its id.
- (PATCH) /books/:id - Update a book by its id.
