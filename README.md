# Bloglist Web Application

This repository contains a full-stack blog application built with React, JavaScript, Node.js, Express, and MongoDB. The application allows users to create, read, update, and delete blog posts in a user-friendly interface. The frontend is enhanced with Material UI components to provide an intuitive and visually appealing experience.

## Features

- User-friendly interface enhanced with Material UI components.
- User creation and login functionality.
- JSON Web Tokens (JWT) for secure login authentication and authorization.
- Comprehensive CRUD operations for managing blogs.
- Integration with MongoDB for reliable and scalable data storage.
- Robust testing implemented with Jest (backend) and Cypress (frontend).

## Tech Stack

The application is built using the following technologies:

- **Frontend:**
  - React: JavaScript library for building user interfaces.
  - Material UI: React component library for creating visually appealing interfaces.
  - Cypress: JavaScript-based end-to-end testing framework for frontend testing.

- **Backend:**
  - Node.js: JavaScript runtime for executing server-side code.
  - Express: Fast and minimalist web application framework for Node.js.
  - MongoDB: NoSQL database for storing and retrieving blog data.
  - Jest: JavaScript testing framework for backend testing.

## Installation

To run this application locally, follow these steps:

1. Clone the repository:

   ```shell
   git clone https://github.com/your-username/bloglist-app.git
   cd bloglist-app
   ```

2. Install the dependencies:

   ```shell
   npm install
   ```

3. Configure the environment variables:

   - Create a `.env` file in the project root directory.
   - Define the following variables in the `.env` file:

     ```
     MONGODB_URI=<your-mongodb-uri>
     SECRET=<your-secret-key-for-jwt>
     ```

4. Start the development server:

   ```shell
   npm start
   ```

5. Open your web browser and visit `http://localhost:3000` to access the application.

## Usage

Once the application is running, you can perform the following actions:

- Create a new user account.
- Log in to an existing user account.
- Create a new blog post.
- View a list of all blog posts.
- Update or delete your own blog posts.
- Log out from your user account.

## Testing

This application includes comprehensive testing to ensure robust functionality. Testing is divided into two parts:

- **Backend Testing:** Backend tests are implemented using Jest. To run the backend tests, use the following command:

  ```shell
  npm run test:backend
  ```

- **Frontend Testing:** Frontend tests are implemented using Cypress. To run the frontend tests, use the following command:

  ```shell
  npm run test:frontend
  ```

## Contributing

Contributions to this project are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request. Make sure to follow the project's code of conduct.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

Special thanks to the developers and contributors of the technologies used in this project. Your work is greatly appreciated.
