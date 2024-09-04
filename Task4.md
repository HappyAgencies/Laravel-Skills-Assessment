# Task 4: Create and Use Middleware for the Bookstore Application

## Objective

The goal of this task is to create custom middleware to restrict access to certain routes based on user roles, such as `admin` and `user`, for the bookstore application.

## Instructions

1. **Middleware Creation:**
   - Create custom middleware to check if the authenticated user is an `admin`.
   - Only users with the `admin` role should be able to create, edit, or delete books.
   - Regular `user` role should be able to view the list of books but should not have access to book management functions.

2. **User Role Setup:**
   - Add a `role` field to the `users` table that can have values such as `admin` or `user`.
   - During user registration or seeding, assign a role to users for testing purposes.

3. **Apply Middleware:**
   - Apply the middleware to the relevant book management routes (create, edit, delete) to ensure only admins can access these routes.

4. **Testing:**
   - Manually test the middleware by attempting to access restricted routes as both `admin` and `user`.
   - Ensure that the correct access controls are in place, with admins able to manage books and regular users restricted to viewing only.

5. **Commit Your Work:**
   - Once you have completed the task, commit your changes with a meaningful commit message (e.g., `Created middleware for role-based access control`).

6. **(Optional) Push to GitHub:**
   - If you are working remotely and choose to push your code, ensure that your repository is private and that access is granted to the evaluators.

## Deliverables

- Custom middleware for role-based access control.
- Routes restricted based on user roles (`admin` can manage books, `user` can only view).
- Properly tested access control for both admin and regular users.
- Commit your work with a meaningful commit message.
- (Optional) Push your code to a private GitHub repository with access granted to the evaluators.

Once you've completed this task, you're ready to move on to Task 5!
