
## 📌 Overview

This project demonstrates how to implement **middleware in an Express.js application** for two main purposes:

1. **Request Logging:** Logging HTTP request details like method, URL, and timestamp.
2. **JSON Body Parsing:** Automatically parsing JSON data from incoming requests using the built-in `express.json()` middleware.

Middleware plays a crucial role in Express apps by **pre-processing requests before they reach the route handlers**, making it easier to implement features like logging, validation, authentication, etc.

---

## 🛠️ Prerequisites

Before you begin, make sure you have the following installed:

- [Node.js](https://nodejs.org/) (v14+ recommended)
- npm (comes with Node.js)
- [Postman](https://www.postman.com/) – For API testing (optional but recommended)

---

## 📁 Project Setup

1. **Create a new folder** and navigate to it:
   ```bash
   mkdir express-middleware
   cd express-middleware
