# 📚 RESTful API – Library System

A simple RESTful API for managing a library system. This API allows users to *add books* along with their authors and can be extended for retrieving, updating, and deleting book records.

---

## 🚀 Features

- 📘 Add new books with title and author
- 📋 View all books (optional extension)
- 📖 Built using RESTful architecture
- 🧩 Easily extensible for more features (update, delete, search)

---

## 🛠 Tech Stack

> Replace with your actual stack. Example below:

- *Backend:* Node.js + Express (or Python Flask / Django, etc.)
- *Database:* MongoDB / MySQL / SQLite / In-memory (for testing)
- *API Format:* REST + JSON

---

## 📌 API Endpoints

### ➕ Add a Book

*POST* /api/books

![image](https://github.com/harsit6299/TASK_2-RESTFUL_API-/blob/d98427110c7b6a693b1db7514b6ddcee89c25239/Post.png)

*Request Body (JSON):*
```json
{
  "title": "CODE STORY",
  "author": "HARSHIT KUMAR"
}
```
### 📚 Get All Books

![image](https://github.com/harsit6299/TASK_2-RESTFUL_API-/blob/d98427110c7b6a693b1db7514b6ddcee89c25239/Get.png)
