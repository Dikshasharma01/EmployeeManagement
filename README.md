Backend README
                   
  # **********-----Employee Management System-----**********

An Employee Management System built with Node.js, Express, and MongoDB. This application provides RESTful APIs for managing departments and employees, with authentication and role-based access control.

## **********-----Table of Contents-----*********
- [Installation](#installation)
- [Usage](#usage)
- [API Routes](#api-routes)
- [Environment Variables](#environment-variables)
- [Built With](#built-with)
- [License](#license)

## **********-----Installation-----*********
Clone the repository:
```bash
git clone https://github.com/DikshaSharma11/EmployeeManagement.git
cd employee-management-system
Install dependencies:
npm install
Set up environment variables:
Create a .env file in the root directory and add the following:
MONGODB_URI=mongodb://your-mongo-db-uri
JWT_SECRET=your-jwt-secret
Replace your-mongo-db-uri with your MongoDB connection string and your-jwt-secret with your JWT secret key.
To start the server, run the following command:
nodemon server.js
The server will start at http://localhost:3000.
*-----API Routes-----
Authentication Routes
POST /api/auth/signup: Creates a new user account. Requires name, email, password, and role fields in the request body.
POST /api/auth/login: Logs in an existing user. Requires email and password fields in the request body.
Department Routes
POST /api/departments: Creates a new department (requires manager role).
GET /api/departments: Retrieves all departments.
PUT /api/departments/: Updates a department by ID (requires manager role).
DELETE /api/departments/: Deletes a department by ID (requires manager role).
Employee Routes
POST /api/employees: Creates a new employee.
GET /api/employees: Retrieves all employees.
PUT /api/employees/: Updates an employee by ID (requires manager role).
DELETE /api/employees/: Deletes an employee by ID (requires manager role).
GET /api/employees/filter/location: Retrieves employees filtered by location.
GET /api/employees/filter/name: Retrieves employees filtered by name.
*-----Environment Variables-----
MONGODB_URI: MongoDB connection URI.
JWT_SECRET: Secret key for JWT token generation.
*-----Built With-----
Node.js - JavaScript runtime environment
Express - Web framework for Node.js
MongoDB - NoSQL database
Mongoose - MongoDB object modeling for Node.js
jsonwebtoken - JSON Web Token implementation
dotenv - Environment variable management
GitHub
Contribute to DikshaSharma11/EmployeeManagement development by creating an account on GitHub.
yamlCopy code---### Frontend README```markdown# **********-----Employee Management System - Frontend-----**********This is the front-end application for the Employee Management System, built with React. It provides a user-friendly interface for managing employees and departments while interacting with the backend APIs.## **********-----Table of Contents-----*********- [Installation](#installation)- [Usage](#usage)- [Built With](#built-with)- [License](#license)## **********-----Installation-----*********Clone the repository:```bashgit clone https://github.com/DikshaSharma11/EmployeeManagement.gitcd employee-management-system-frontend
Install dependencies:
bashCopy codenpm install
*-----Usage-----
To start the application, run the following command:
bashCopy codenpm start
The front-end application will start at http://localhost:3000. Open your browser and start exploring the Employee Management System!
*-----Built With-----
React - JavaScript library for building user interfaces
Bootstrap - CSS framework for styling
Axios - Promise-based HTTP client for making requests
React Hook Form - Library for managing forms
date-fns - Library for date formatting
GitHub
Contribute to DikshaSharma11/EmployeeManagement development by creating an account 

Feel free to customize any sections to better fit your project!