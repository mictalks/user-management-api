# User Management API

REST API for user management (CRUD) built with **Node.js**, **Prisma ORM**, and **MongoDB**.

---

## About the Project

This project is a backend application designed to manage users through a complete CRUD system:

* Create users
* Retrieve users
* Update user data
* Delete users

It was developed to demonstrate backend fundamentals such as API design, database integration, and ORM usage.

---

## Tech Stack

* Node.js
* Express
* Prisma ORM
* MongoDB

---

## Project Structure

```
├── prisma/
│   └── schema.prisma      # Database schema
├── generated/             # Prisma client (auto-generated)
├── src/ (or root)
│   └── server.js          # Main server file
├── .env                   # Environment variables (not committed)
├── .env.example           # Example environment config
├── package.json
└── README.md
```

---

## Setup & Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/user-management-api.git
cd user-management-api
```

---

### 2. Install dependencies

```bash
npm install
```

---

### 3. Configure environment variables

Create a `.env` file based on `.env.example`:

```env
DATABASE_URL="your_mongodb_connection_string"
```

---

### 4. Generate Prisma Client

```bash
npx prisma generate
```

---

### 5. Push database schema

```bash
npx prisma db push
```

---

### 6. Run the project

```bash
npm run dev
```

---

## API Endpoints

| Method | Endpoint   | Description    |
| ------ | ---------- | -------------- |
| GET    | /users     | Get all users  |
| GET    | /users/:id | Get user by ID |
| POST   | /users     | Create user    |
| PUT    | /users/:id | Update user    |
| DELETE | /users/:id | Delete user    |

---

## Purpose

This project was created to practice and demonstrate:

* REST API development
* Database integration with MongoDB
* Prisma ORM usage
* Backend project structure and organization

---

## Contact

Feel free to connect with me:

* LinkedIn: https://www.linkedin.com/in/milenaporto/
* GitHub: https://github.com/mictalks
