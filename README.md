# Node.js E-Commerce REST API

## Overview

This repository contains a **Node.js E-Commerce REST API** that **I built** as part of my learning and practice in backend development. The project focuses on designing and implementing a real-world API for an online store, including products, orders, and users management.

I used this project to practice RESTful API design, clean project structure, and common backend patterns.

---

## Getting Started

### Install Dependencies

```bash
npm install
```

### Run the Server

```bash
npm start
```

Once started, the API is ready to receive HTTP requests.

---

## API Endpoints

### 📦 Products

```text
GET      /api/v1/products
GET      /api/v1/products/:id
POST     /api/v1/products
PUT      /api/v1/products/:id
DELETE   /api/v1/products/:id
PUT      /api/v1/products/gallery-images/:id
GET      /api/v1/products/get/featured/:count
GET      /api/v1/products/get/count
```

---

### 🧾 Orders

```text
GET      /api/v1/orders
GET      /api/v1/orders/:id
POST     /api/v1/orders
PUT      /api/v1/orders/:id
DELETE   /api/v1/orders/:id
GET      /api/v1/orders/get/count
```

---

### 👤 Users

```text
GET      /api/v1/users
GET      /api/v1/users/:id
POST     /api/v1/users
PUT      /api/v1/users/:id
DELETE   /api/v1/users/:id
GET      /api/v1/users/get/count
```

#### User Registration

```text
POST     /api/v1/users/register
```

#### User Login

Used to authenticate users and return a JWT token:

```text
POST     /api/v1/users/login
```

---

## Project Workflow

I manage and improve this project using a task-based workflow, similar to real-world team development:

* Pick a task or feature to work on
* Implement and refactor the code
* Review every part of the implementation

---

## Notes

* RESTful API with versioning (`v1`)
* Structured for scalability and maintainability
* Suitable as a backend foundation for an e-commerce application

---

Built and maintained as part of my backend development journey 🚀
