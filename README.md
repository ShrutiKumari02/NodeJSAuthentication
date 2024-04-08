# Node.js Authentication System

This project aims to provide a comprehensive authentication system that can be used as a starter code for creating new applications. It includes features such as sign up with email, sign in, sign out, reset password, and social authentication using Google. The system is built with scalability and maintainability in mind, with a well-structured folder architecture and clean code.

# Setup Instructions

Follow these steps to set up the project on your local system:

1. Clone the repository:
   git clone <repository_url>
   
2. Install dependencies:
   cd nodejs-authentication
   npm install
   
3. Set up environment variables:
   Create a .env file in the root directory and add the following variables:

4. Start the server:
   npm start

5. Access the application:
   Open your web browser and go to http://localhost:3000

# Explanation of Components

- Controllers: Responsible for handling user input and responding with appropriate outputs. Separation of concerns is maintained, with different controllers for authentication and user-related operations.
- Models: Contains the schema and model definition for the User entity. MongoDB is used as the database, and Mongoose is the ODM (Object Data Modeling) library.
- Routes: Defines the API endpoints for different functionalities. Routes are divided based on authentication and user operations for better organization.
- Public: Static files such as CSS, images, and client-side JavaScript.
- Utils: Utility functions used across the application, including email sending, password encryption, and input validation.
- Views: HTML templates for different pages of the application, including sign up, login, reset password, and home page.


# Additional Notes

- For additional features such as Google login/signup and forgot password functionality, refer to the respective controller files (authController.js) and implement the necessary logic.
- Ensure that sensitive information such as passwords and API keys are not committed to version control systems like Git.
- Follow best practices for security, such as using HTTPS for secure communication and properly sanitizing user inputs to prevent injection attacks.
