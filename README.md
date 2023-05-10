# Books-API

This API provides basic CRUD operations for managing a collection of books.

GET all books: 
    GET http://localhost:5000/books

GET a specific book: 
    GET http://localhost:5000/books/{id}

CREATE a new book: 
    POST http://localhost:5000/books with JSON payload {"title": "New Book", "author": "New Author"}

UPDATE a book: 
    PUT http://localhost:5000/books/{id} with JSON payload {"title": "Updated Title", "author": "Updated Author"}

DELETE a book: 
    DELETE http://localhost:5000/books/{id}
    
    
###
