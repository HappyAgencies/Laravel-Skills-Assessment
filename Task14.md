# Task 14: Implement Rate Limiting on API Endpoints

## Objective

The goal of this task is to implement rate limiting for the API endpoints to prevent abuse and ensure the API is not overwhelmed by excessive requests from a single client.

## Instructions

1. **Rate Limiting Setup:**
   - Use Laravel’s built-in rate limiting features to limit the number of requests a user can make to specific API endpoints.
   - Set a reasonable rate limit, such as 60 requests per minute, for the book API endpoints.

2. **Apply Rate Limiting to Routes:**
   - Apply the rate limit to sensitive API routes, such as those for creating, updating, and deleting books.
   - Ensure that public routes, such as retrieving book data, can either have a higher limit or no limit if necessary.

3. **Rate Limit Responses:**
   - Ensure that when the rate limit is exceeded, the API returns an appropriate error message and HTTP status code (e.g., `429 Too Many Requests`).
   - Include information in the response headers about the rate limit, remaining requests, and when the limit will reset.

4. **Testing:**
   - Use Postman, Curl, or a similar tool to test the rate limiting.
   - Simulate multiple rapid requests to verify that the rate limit is enforced, and that an appropriate response is returned once the limit is reached.

5. **Commit Your Work:**
   - Once you have completed the task, commit your changes with a meaningful commit message (e.g., `Implemented rate limiting on API endpoints`).

6. **(Optional) Push to GitHub:**
   - If you are working remotely and choose to push your code, ensure that your repository is private and that access is granted to the evaluators.

## Deliverables

- Rate limiting applied to sensitive API endpoints.
- Proper error responses and headers for users exceeding the rate limit.
- Testing to ensure the rate limit is properly enforced.
- Commit your work with a meaningful commit message.
- (Optional) Push your code to a private GitHub repository with access granted to the evaluators.

Once you've completed this task, you're ready to move on to Task 15!
