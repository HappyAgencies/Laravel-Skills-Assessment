# Task 12: OAuth Integration for Social Login

## Objective

The goal of this task is to integrate social login using OAuth for the bookstore application, allowing users to log in via third-party providers like Google or Facebook.

## Instructions

1. **Install Laravel Socialite:**
   - Install Laravel Socialite, which will be used to manage social login for OAuth providers.

2. **Configure OAuth Provider:**
   - Set up the necessary API keys, client ID, and client secret for a third-party provider (e.g., Google or Facebook).
   - Add the required credentials to your `.env` file for the OAuth provider.

3. **Implement Social Login:**
   - Create routes and a controller method to handle social login. 
   - Allow users to authenticate via the OAuth provider, and retrieve user details (e.g., name, email) upon successful authentication.

4. **Handle User Registration:**
   - If the user logging in via social login doesn’t already exist in your system, create a new user in the `users` table.
   - Store relevant user information from the OAuth provider (e.g., name, email, OAuth token).

5. **Testing:**
   - Test the OAuth login process to ensure users can authenticate via Google or Facebook.
   - Verify that new users are correctly registered and returning users can log in seamlessly.

6. **Commit Your Work:**
   - Once you have completed the task, commit your changes with a meaningful commit message (e.g., `Implemented OAuth login using Google`).

7. **(Optional) Push to GitHub:**
   - If you are working remotely and choose to push your code, ensure that your repository is private and that access is granted to the evaluators.

## Deliverables

- OAuth integration using Laravel Socialite for social login (e.g., Google or Facebook).
- New users are registered automatically, and returning users are logged in successfully.
- Commit your work with a meaningful commit message.
- (Optional) Push your code to a private GitHub repository with access granted to the evaluators.

Once you've completed this task, you're ready to move on to Task 13!
