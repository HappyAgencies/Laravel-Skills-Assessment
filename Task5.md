# Task 5: Develop a RESTful API for the Bookstore Application

## Objective

The goal of this task is to develop a RESTful API for the bookstore application, allowing external clients to interact with the books (Create, Read, Update, Delete).

## Instructions

1. **API Route Setup:**
   - Define API routes for managing books (e.g., `/api/books`).
   - Ensure that the routes follow RESTful conventions (GET, POST, PUT/PATCH, DELETE).

2. **API Controller:**
   - Create a dedicated API controller for handling the book-related API endpoints.
   - Implement methods for:
     - Fetching the list of books.
     - Fetching a single book by its ID.
     - Creating a new book.
     - Updating an existing book.
     - Deleting a book.

3. **Request Validation:**
   - Implement request validation for the API endpoints to ensure the submitted data (e.g., for creating or updating books) meets the necessary requirements (e.g., title is required, price must be a valid number).

4. **Authentication for API:**
   - Apply authentication to protect certain API routes (e.g., creating, updating, and deleting books should require authentication).
   - Public routes (e.g., viewing books) should not require authentication.

5. **Testing the API:**
   - Use tools like Postman, Insomnia, or Curl to manually test the API.
   - Ensure that all CRUD operations work as expected and that authenticated users can perform the necessary actions.

6. **Commit Your Work:**
   - Once you have completed the task, commit your changes with a meaningful commit message (e.g., `Developed RESTful API for books`).

7. **(Optional) Push to GitHub:**
   - If you are working remotely and choose to push your code, ensure that your repository is private and that access is granted to the evaluators.

## Deliverables

- A fully functional RESTful API for managing books.
- Proper request validation to ensure data integrity.
- Authentication applied to protected API routes.
- API routes tested using a tool like Postman, Insomnia, or Curl.
- Commit your work with a meaningful commit message.
- (Optional) Push your code to a private GitHub repository with access granted to the evaluators.

Once you've completed this task, you're ready to move on to Task 6!
