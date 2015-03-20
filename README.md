# BookStore

This is a virtualized sample of a simple book store api.

There are three groups of request-response pairs: "/bookstore/book", "/bookstore/booksearch", "/bookstore/book{id}/format{mediaTypeExtension}".

The "/bookstore/book" group contains one pair which is a POST to create a book.  The request takes a title, author and publisher parameters.  The response is just a 200 response code.

The "/bookstore/booksearch" group contains GET requests to search for a book using different parameters viz. by title, by author, by publisher and combinations of these.

The "/bookstore/book{id}/format{mediaTypeExtension}" conatins two GET requests which return a book either in XML or JSON format.
