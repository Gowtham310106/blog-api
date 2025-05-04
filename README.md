# Blog API

A simple **Blog API** built using **Node.js** and **Express.js** that demonstrates **CRUD operations**.  
This project does **not** use a database or in-memory storage — it’s focused on structuring API routes only.

---

## Features

- API routes for:
  - Creating a blog post
  - Reading all blog posts
  - Updating a blog post
  - Deleting a blog post

> *Note: Actual blog data handling/storage is not implemented.*

---

## Project Structure

blog-api/
│
├── index.js # Express server & route setup
├── server.js # Blog route handler functions
├── package.json # Dependencies
└── .gitignore # Hides node_modules and logs

---

## Tech Stack

- Node.js
- Express.js

---

## Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/your-username/blog-api.git
cd blog-api
npm install
node index.js
node server.js
http://localhost:3000

