# Backend Demo of Quora Platform

This is a simple backend application built using **Node.js** and **Express.js** to demonstrate basic CRUD operations. It mimics the core functionality of a Quora-like platform where users can create, view, edit, and delete posts.

## 🚀 Features

- Create a new post
- View all posts at `/posts`
- View a single post in detail at `/posts/:id`
- Edit a post at `/posts/:id/edit`
- Delete a post

## 📂 Routes Overview

| Method | Route              | Description               |
|--------|-------------------|---------------------------|
| GET    | `/posts`           | View all posts            |
| GET    | `/posts/:id`       | View post in detail       |
| GET    | `/posts/:id/edit`  | Edit a post               |
| POST   | `/posts`           | Create a new post         |
| PUT    | `/posts/:id`       | Update a post             |
| DELETE | `/posts/:id`       | Delete a post             |

## 🖼️ Screenshot

Main page showing all posts with links to edit, delete, or see details:

![Main Page](./Screenshot%20(2).png)

## 🛠 Tech Stack

- Node.js
- Express.js
- EJS (if templating used)
- Body-parser / Express middleware

## 🔧 Setup Instructions

1. Clone the repository:
   ```bash
   git clone <repo-url>
   cd backend-quora-demo
2. Install all modules:
     npm i
3. Run the server:
     nodemon index.js
