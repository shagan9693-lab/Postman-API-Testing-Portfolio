# Project 2 - JSONPlaceholder API Testing

## Project Overview

This project demonstrates API testing using the JSONPlaceholder REST API. The objective was to understand CRUD operations, validate API responses, and implement Postman test scripts using JavaScript.

---

## API Endpoints Covered

- GET Single Post
- GET All Posts
- POST Create Post
- PUT Update Post
- PATCH Update Post
- DELETE Post

---

## Validations Implemented

### Status Code Validation
- 200 OK
- 201 Created

### Response Time Validation
- Response time less than 2000 ms

### Structure Validation
- Response body contains expected fields
- Mandatory fields are validated

### Data Type Validation
- Number
- String

### Business Validation
- Response values match request body
- ID validation
- Email validation (Regex)
- Positive value validation
- Field comparison between request and response

---

## Postman Features Used

- Collection Variables
- Environment Variables
- JavaScript Test Scripts
- pm.expect Assertions
- JSON Parsing
- Request Body Validation
- Regular Expressions

---

## Tools Used

- Postman
- JavaScript
- REST API
- JSONPlaceholder API

---

## Learning Outcomes

- Learned REST API fundamentals
- Understood CRUD operations
- Implemented API validations using JavaScript
- Worked with variables in Postman
- Performed response comparison with request payload
- Improved scripting skills using Postman Test Scripts