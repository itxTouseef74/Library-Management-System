# Library Management System

This Library Management System is a web application built using Node.js, Express, MongoDB, and various other dependencies to help manage a library's resources and operations.

## Features

- **User Authentication**: Allows users to sign up, log in, and manage their accounts securely.
- **Admin Dashboard**: Provides an admin panel for managing books, users, and transactions.
- **Book Management**: Enables the addition, deletion, and update of books in the library's inventory.
- **User Management**: Admins can manage user accounts, including granting or revoking privileges.
- **Transaction History**: Tracks borrowing and returning of books by users.
- **Search and Filter**: Allows users to search for books based on various criteria.

## Dependencies

- bcrypt: For hashing and verifying user passwords.
- body-parser: Middleware for parsing request bodies.
- cookie-parser: Parses cookies for handling user sessions.
- debug: For debugging purposes.
- dotenv: For managing environment variables.
- express: Web framework for handling routes and requests.
- express3-handlebars: View engine for rendering dynamic content.
- hbs: Handlebars templating engine for views.
- http-errors: Handles HTTP errors.
- jsonwebtoken: For generating and verifying JSON Web Tokens.
- mongoose: MongoDB object modeling for database interaction.
- morgan: HTTP request logger middleware.
- nodemon: Utility for automatically restarting the server during development.

## Getting Started

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/itxTouseef74/Library-Management-System.git
   ```

2. Navigate to the project directory:

   ```bash
   cd library-Management-System
   ```

3. Install the required dependencies:

   ```bash
   npm install
   ```

4. Set up your environment variables:

   - Rename `.env.example` to `.env`.
   - Add your environment variables, including database connection URI and session secret.

5. Start the application:

   ```bash
   npm start
   ```

6. Open your web browser and navigate to `http://localhost:3000` to access the Library Management System.

## Usage

1. Register for a new account or log in if you already have one.
2. If you're an admin, log in and access the admin dashboard to manage books, users, and transactions.
3. If you're a regular user, you can browse books, borrow, and return them.

## Contributions

Contributions and suggestions for new features are welcome! If you'd like to contribute or have ideas for enhancements, please feel free to create an issue or pull request.

## Acknowledgments

- This project was developed to showcase a comprehensive Library Management System using Node.js, Express, MongoDB, and other technologies.

