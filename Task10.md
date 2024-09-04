# Task 10: Add Advanced Relationships and Reports (Authors and Books)

## Objective

The goal of this task is to implement advanced relationships between `Authors` and `Books` and generate simple reports based on this relational data (e.g., books per author).

## Instructions

1. **Create Author Model and Migration:**
   - Create an `Author` model with the necessary migration file.
   - The `authors` table should have fields such as `name` and `bio`.

2. **Define Relationships:**
   - Define the `hasMany` relationship between `Author` and `Book` (one author can have many books).
   - Define the `belongsTo` relationship in the `Book` model to associate each book with an author.

3. **Author Management:**
   - Add CRUD functionality to manage authors (similar to book management).
   - Modify the book creation and editing forms to allow users to select an author for each book.

4. **Generate Reports:**
   - Create a simple report page that displays the number of books each author has written.
   - Optionally, create other reports (e.g., most prolific author, total books per genre).

5. **Testing:**
   - Test the author-book relationships by creating and managing authors and assigning books to them.
   - Ensure the reports display the correct data (e.g., books per author).

6. **Commit Your Work:**
   - Once you have completed the task, commit your changes with a meaningful commit message (e.g., `Added author-book relationships and reports`).

7. **(Optional) Push to GitHub:**
   - If you are working remotely and choose to push your code, ensure that your repository is private and that access is granted to the evaluators.

## Deliverables

- `Author` model and relationships established with the `Book` model.
- CRUD functionality for managing authors and associating them with books.
- A simple report displaying books per author.
- Commit your work with a meaningful commit message.
- (Optional) Push your code to a private GitHub repository with access granted to the evaluators.

Once you've completed this task, you're ready to move on to Task 11!
