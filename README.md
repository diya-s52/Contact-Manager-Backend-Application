<h1>Contact Manager Backend Application</h1>
This project is a backend application for managing contacts. It provides a robust and scalable solution for creating, reading, updating, and deleting (CRUD) contact information. The application is built using Node.js and Express, with MongoDB as the database. It also incorporates JWT (JSON Web Token) for authentication and authorization, and Thunder Client API for testing purposes.

<h2>Features</h2>
1. User Authentication and Authorization: Secure user registration and login using JWT.</br>
2. CRUD Operations: Create, read, update, and delete contacts.</br>
3. Search and Filter: Search contacts by name, email, or phone number and filter by specific criteria.</br>
4. Secure API Endpoints: Protected routes to ensure only authenticated users can access specific resources.</br>
5. Error Handling: Comprehensive error handling for various scenarios.</br>
6. Environment Configuration: Use of environment variables to manage configuration settings.</br>

<h2>Technologies Used</h2>
1. Node.js: A JavaScript runtime built on Chrome's V8 JavaScript engine.</br>
2. Express: A minimal and flexible Node.js web application framework.</br>
3. MongoDB: A NoSQL database for storing contact information.</br>
4. Mongoose: An Object Data Modeling (ODM) library for MongoDB and Node.js.</br>
5. JWT: JSON Web Token for secure authentication.</br>
6. Thunder Client: A lightweight REST API Client extension for VS Code used for testing APIs.</br>
7. dotenv: Module to load environment variables from a .env file into process.env.</br>

<h2>API Endpoints</h2>
1.User Registration: POST /api/users/register - Register a new user.</br>
2.User Login: POST /api/users/login - Authenticate a user and return a token.</br>
3.Get All Contacts: GET /api/contacts - Retrieve all contacts (protected).</br>
4.Create Contact: POST /api/contacts - Create a new contact (protected).</br>
5.Get Contact by ID: GET /api/contacts/:id - Retrieve a contact by ID (protected).</br>
6.Update Contact: PUT /api/contacts/:id - Update a contact by ID (protected).</br>
7.Delete Contact: DELETE /api/contacts/:id - Delete a contact by ID (protected).</br>


<h2>License</h2>
This project is licensed under the MIT License. See the LICENSE file for more details.</br>

<h2>Acknowledgements</h2>
Thanks to the developers of Node.js, Express, MongoDB, and all the other libraries and tools used in this project.
