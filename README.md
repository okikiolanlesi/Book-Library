# Book-Library

A simple library where users can store, read and receive books

## Routes

### User routes

- POST /register => Registers a new user
- POST /login => Login a user into the application
- POST /logout => Logout a user from the application

### Book routes

- GET /all => Returns all available books in the library
- GET /:id => Returns a particular book by its ID
- POST / => Adds a new book to the library
- DELETE /:id => Removes a book from the library
- PUT /id => Updates a book in the Library

## Models

### Book models

- title
- author
- description
- body
- isbn
- category
- timestamps

### User models

- first_name
- last_name
- email
- password
- role

## Frontend

- Home/landing page
- Register/Login page
- Form page
- Book page
