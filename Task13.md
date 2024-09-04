# Task 13: Implement Role-Based API Access with Laravel Passport

## Objective

The goal of this task is to implement role-based API access control using Laravel Passport, ensuring that only authorized users can interact with certain API endpoints.

## Instructions

1. **Install Laravel Passport:**
   - Install and configure Laravel Passport to handle API token-based authentication.

2. **Role-Based Access Control:**
   - Ensure that the `users` table has a `role` field (e.g., `admin`, `user`).
   - Only allow users with the `admin` role to perform certain actions via the API, such as creating, updating, or deleting books.
   - Regular users should only be able to retrieve (read) book data.

3. **Secure API Endpoints:**
   - Apply Passport authentication and role-based access control to the following API routes:
     - **Admin-only routes:** API routes for creating, updating, and deleting books should be restricted to users with the `admin` role.
     - **Public routes:** API routes for retrieving book data should remain accessible to all authenticated users, regardless of their role.

4. **Token Management:**
   - Use Passport’s token system to authenticate API requests. 
   - Implement proper error handling for unauthorized or unauthenticated requests (e.g., returning a `403 Forbidden` or `401 Unauthorized` response).

5. **Testing:**
   - Test the API by generating API tokens for both admin and regular users. 
   - Verify that admins can access all routes, while regular users are restricted from accessing certain routes (e.g., create or delete).

6. **Commit Your Work:**
   - Once you have completed the task, commit your changes with a meaningful commit message (e.g., `Implemented role-based API access using Laravel Passport`).

7. **(Optional) Push to GitHub:**
   - If you are working remotely and choose to push your code, ensure that your repository is private and that access is granted to the evaluators.

## Deliverables

- Role-based API access implemented using Laravel Passport.
- API routes properly secured based on user roles (`admin` vs. `user`).
- Authentication handled via API tokens with appropriate error handling for unauthorized access.
- Commit your work with a meaningful commit message.
- (Optional) Push your code to a private GitHub repository with access granted to the evaluators.

Once you've completed this task, you're ready to move on to Task 14!
