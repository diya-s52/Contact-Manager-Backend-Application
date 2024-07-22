<h1>Contact Manager Backend Application</h1>
This project is a backend application for managing contacts. It provides a robust and scalable solution for creating, reading, updating, and deleting (CRUD) contact information. The application is built using Node.js and Express, with MongoDB as the database. It also incorporates JWT (JSON Web Token) for authentication and authorization, and Thunder Client API for testing purposes.

Features:
User Authentication and Authorization: Secure user registration and login using JWT.
CRUD Operations: Create, read, update, and delete contacts.
Search and Filter: Search contacts by name, email, or phone number and filter by specific criteria.
Secure API Endpoints: Protected routes to ensure only authenticated users can access specific resources.
Error Handling: Comprehensive error handling for various scenarios.
Environment Configuration: Use of environment variables to manage configuration settings.

Technologies Used:
Node.js: A JavaScript runtime built on Chrome's V8 JavaScript engine.
Express: A minimal and flexible Node.js web application framework.
MongoDB: A NoSQL database for storing contact information.
Mongoose: An Object Data Modeling (ODM) library for MongoDB and Node.js.
JWT: JSON Web Token for secure authentication.
Thunder Client: A lightweight REST API Client extension for VS Code used for testing APIs.
dotenv: Module to load environment variables from a .env file into process.env.

API Endpoints
User Registration: POST /api/users/register - Register a new user.
User Login: POST /api/users/login - Authenticate a user and return a token.
Get All Contacts: GET /api/contacts - Retrieve all contacts (protected).
Create Contact: POST /api/contacts - Create a new contact (protected).
Get Contact by ID: GET /api/contacts/:id - Retrieve a contact by ID (protected).
Update Contact: PUT /api/contacts/:id - Update a contact by ID (protected).
Delete Contact: DELETE /api/contacts/:id - Delete a contact by ID (protected)
