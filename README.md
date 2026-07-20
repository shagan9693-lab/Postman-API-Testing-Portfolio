# 🚀 Postman API Testing Portfolio

A collection of hands-on API Testing projects built using **Postman** and **JavaScript**.

This repository showcases practical API testing skills through real-world projects covering CRUD operations, authentication, request chaining, dynamic variables, business validations, and automated Postman scripting.

---

# Projects Included

## Project 1 – Employee CRUD API

Developed an end-to-end Employee CRUD testing suite using the Dummy Employee REST API.

### Covered

- Get All Employees
- Get Single Employee
- Create Employee
- Update Employee
- Delete Employee

### Validations

- Status Code Validation
- Response Time Validation
- Structure Validation
- Data Type Validation
- Business Validation
- Request vs Response Validation
- Dynamic Employee ID Handling

---

## Project 2 – JSONPlaceholder API

Built API validations using the JSONPlaceholder public REST API.

### Covered

- Get All Posts
- Get Single Post
- Get All Comments
- Get All Albums
- Get All Photos

### Validations

- Status Code Validation
- Response Time Validation
- Structure Validation
- Data Type Validation
- Business Validation

---

## Project 3 – Authentication API

Implemented authentication testing using JWT-based authentication.

### Covered

- Login
- Protected User API
- Invalid Login
- Protected API without Token
- Protected API with Invalid Token

### Validations

- Authentication Flow
- Authorization Validation
- Positive & Negative Scenarios
- Response Structure
- Business Rules
- Token Handling

---

## Project 4 – Resource Management API

Developed complete CRUD API testing for Resource Management APIs.

### Covered

- Get All Resources
- Get Single Resource
- Create Resource
- Update Resource
- Delete Resource

### Validations

- Status Code Validation
- Response Time Validation
- Structure Validation
- Data Type Validation
- Business Validation
- Dynamic Resource ID Handling

---

## Project 5 – E-Commerce API

Developed an end-to-end API Testing suite using DummyJSON.

### Modules Covered

### Authentication

- Login
- Refresh Token
- Current User
- Current User without Token
- Current User with Invalid Token
- Invalid Login

### Products

- Get All Products
- Get Single Product
- Search Products
- Products by Category

### Users

- Get All Users
- Get Single User
- Filter Users
- Search Users

### Carts

- Get All Carts
- Get Single Cart
- Add Cart
- Update Cart
- Delete Cart

### Validations

- Status Code Validation
- Response Time Validation
- Structure Validation
- Data Type Validation
- Business Validation
- Request Chaining
- Environment Variables
- Collection Variables
- Dynamic Data Validation

---

# Skills Demonstrated

- REST API Testing
- CRUD Operations
- Authentication & Authorization
- Request Chaining
- Environment Variables
- Collection Variables
- Dynamic Data Handling
- JavaScript in Postman
- Chai Assertions
- Response Validation
- Schema Validation
- Data Type Validation
- Business Validation
- Positive Testing
- Negative Testing
- Collection Runner
- API Documentation
- Git & GitHub

---

# Tools Used

- Postman
- JavaScript
- Chai Assertion Library
- Git
- GitHub

---

# API Observations

While working with public APIs, a few API-side inconsistencies were identified and documented.

Examples include:

- Dummy Employee API occasionally returns inconsistent data types and intermittent HTTP 429 responses.
- DummyJSON Authentication API occasionally behaves differently when executed through the Postman Runner compared to individual request execution.
- DummyJSON Cart Add API returns incorrect product quantities when multiple products are added in a single request, exposing an API defect rather than a scripting issue.

These behaviors were documented as API limitations instead of modifying validations to force test success.

---

# Repository Contents

Each project contains:

- Postman Collection
- Project README
- Execution Evidence
- Validation Scripts

---

## Author

**Ganesh Gurusamy**

QA Engineer | API Testing | Manual Testing | JavaScript | SQL | Playwright (Learning)

GitHub:
https://github.com/shagan9693-lab/Postman-API-Testing-Portfolio
