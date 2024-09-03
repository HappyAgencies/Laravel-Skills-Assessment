# Task 2: Create a Basic CRUD Application for a Bookstore

## Objective

The goal of this task is to develop a simple CRUD (Create, Read, Update, Delete) application in Laravel to manage a list of books in a bookstore.

## Instructions

1. **Model Creation:**
   - Create a new model to represent the books in the bookstore.
   - Create the necessary database migration file to define the table structure for books.

2. **Database Migration:**
   - Define the fields for your books table in the migration file. Include fields such as title, author, description, price, and publication date.
   - Run the migration to create the table in the database.

3. **Controller Setup:**
   - Create a new controller to handle the CRUD operations for the Book model.
   - Implement methods to display a list of books, show forms for creating and editing books, handle form submissions, and delete books.

4. **Routes:**
   - Define the necessary routes in the `web.php` file to map URLs to your controller methods.
   - Consider using resource routing to simplify the route definitions.

5. **Views:**
   - Create Blade templates for listing books, creating a new book, and editing an existing book.
   - Ensure the views are well-structured and user-friendly, with appropriate input fields for each book attribute.

6. **Testing:**
   - Manually test your application by creating, reading, updating, and deleting books.
   - Ensure that all operations work as expected and that data is correctly stored in the database.

7. **Commit Your Work:**
   - Once you have completed the task, commit your changes with a meaningful commit message.

8. **(Optional) Push to GitHub:**
   - If you are working remotely and choose to push your code, ensure that your repository is private and that access is granted to the evaluators.

## Deliverables

- A fully functional Laravel CRUD application that manages a list of books in a bookstore.
- Blade templates for listing, creating, and editing books.
- Properly defined routes and controller methods to handle CRUD operations for books.
- Commit your work with a meaningful commit message.
- (Optional) Push your code to a private GitHub repository with access granted to the evaluators.

Once you've completed this task, you're ready to move on to Task 3!
