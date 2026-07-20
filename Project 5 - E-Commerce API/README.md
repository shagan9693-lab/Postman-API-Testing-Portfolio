# 🛒 E-Commerce API Testing using Postman

## 📌 Project Overview

This project demonstrates comprehensive API testing of an E-Commerce application using **Postman**. It covers end-to-end testing of core business functionalities including authentication, product management, cart operations, and user management.

The project focuses on validating API functionality through structured test scripts written in JavaScript and executed using the Postman Collection Runner.

---

## 🚀 Modules Covered

### 🔐 Authentication
- User Login
- Refresh Access Token
- Get Current User
- Current User Without Token
- Current User With Invalid Token
- Invalid Login

### 📦 Products
- Get All Products
- Get Single Product
- Search Products
- Get Products by Category

### 🛒 Carts
- Get All Carts
- Get Single Cart
- Add Cart
- Update Cart
- Delete Cart

### 👤 Users
- Get All Users
- Get Single User
- Search Users

---

## ✅ Validations Implemented

- HTTP Status Code Validation
- Response Time Validation
- Response Structure Validation
- Data Type Validation
- Business Rule Validation
- Array & Nested Object Validation
- Regular Expression Validation
- URL Validation
- JWT Authentication Validation
- Cross-field Validation
- Dynamic Variable Validation

---

## 🛠 Technologies Used

- Postman
- JavaScript
- REST API
- JSON
- Postman Environment Variables
- Postman Collection Runner

---

## 🔑 Environment Variables

The project uses environment variables for dynamic request execution.

- `baseUrl`
- `accessToken`
- `refreshToken`
- `productId`
- `cartId`
- `userId`

---

## 💡 Highlights

- Designed reusable API test scripts using JavaScript.
- Implemented positive and negative test scenarios.
- Validated complex nested JSON responses.
- Performed business rule validation using calculated values.
- Used environment variables to manage dynamic data across requests.
- Executed the complete collection using the Postman Collection Runner.

---

## 📝 Observation

During testing, the **DummyJSON Add Cart API** returned incorrect product quantities when multiple products were added in a single request.

To validate the response accurately, `Array.find()` was used to match response products with request products using **Product ID**. This validation correctly exposed the API inconsistency, demonstrating the effectiveness of the implemented business validation.

Additionally, the **Current User – Without Token** request occasionally behaves differently during full Authentication folder execution against the public DummyJSON API. Individual execution returns the expected **401 Unauthorized**, while folder execution may return **200 OK** despite the request being configured with **No Auth**.

---

## 🎯 Key Learning Outcomes

- REST API Testing
- API Validation Techniques
- JWT Authentication Testing
- Dynamic Data Handling
- Business Rule Validation
- JavaScript in Postman
- Collection Runner Execution
- API Defect Identification

---

## 👨‍💻 Author

**Ganesh Gurusamy**

Software Test Engineer | 10+ Years in Banking & Financial Services Testing

**Skills:** Manual Testing • API Testing • Playwright Automation • UAT • SQL • JavaScript