# 🚀 Express.js Product API

## 📘 Overview
This project is a RESTful API built using **Express.js**.  
It provides CRUD operations for managing products, implements middleware for logging, authentication, and validation, and includes error handling, filtering, pagination, and search functionality.

---

## ⚙️ Setup Instructions

### 1️⃣ Prerequisites
- Node.js (v18 or higher)
- npm or yarn
- Postman, Insomnia, or curl (for testing API)

### 2️⃣ Installation
Clone your repository and install dependencies:
```bash
npm install

## Environment Variables
API_KEY='Choose your secret key'
PORT=3000

## Run Server
- npm start
- The server will run on http://localhost:3000


## API Documentation
- http://localhost:3000/api/products

## Example Request:
- curl -H "x-api-key: mysecretkey" http://localhost:3000/api/products?category=electronics&page=1&limit=2

## Example response

{
  "total": 2,
  "page": 1,
  "limit": 2,
  "data": [
    {
      "id": "1",
      "name": "Laptop",
      "description": "High-performance laptop",
      "price": 1200,
      "category": "electronics",
      "inStock": true
    },
    {
      "id": "2",
      "name": "Smartphone",
      "description": "Latest smartphone",
      "price": 800,
      "category": "electronics",
      "inStock": true
    }
  ]
}


