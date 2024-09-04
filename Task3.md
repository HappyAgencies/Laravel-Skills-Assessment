# Task 3: Implement User Authentication for the Bookstore Application

## Objective

The goal of this task is to implement user authentication in your bookstore application, allowing users to log in, manage books, and log out.

## Instructions

1. **Install Authentication:**
   - Use Laravel's built-in authentication system to add login, registration, and logout functionality.
   
2. **User Registration:**
   - Implement a registration page where users can create an account.
   - Ensure that users are properly stored in the database after registration.

3. **Login and Logout:**
   - Implement a login page that allows users to log in to the application.
   - Add logout functionality to allow users to log out of the application.

4. **Restrict Access:**
   - Restrict access to the book management routes (create, edit, delete) so that only authenticated users can manage books.
   - Non-authenticated users should only be able to view the list of books without performing any CRUD operations.

5. **Test Authentication:**
   - Manually test the registration, login, and logout features.
   - Ensure that non-authenticated users cannot access restricted routes (book management).

6. **Commit Your Work:**
   - Once you have completed the task, commit your changes with a meaningful commit message (e.g., `Implemented user authentication`).

7. **(Optional) Push to GitHub:**
   - If you are working remotely and choose to push your code, ensure that your repository is private and that access is granted to the evaluators.

## Deliverables

- A fully functional authentication system for the bookstore application.
- Routes protected so that only authenticated users can manage books.
- Proper testing of the authentication system.
- Commit your work with a meaningful commit message.
- (Optional) Push your code to a private GitHub repository with access granted to the evaluators.

Once you've completed this task, you're ready to move on to Task 4!
