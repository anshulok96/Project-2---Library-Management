# Project-2---Library-Management# 📚 Library Management System (Node.js + Express + MongoDB)

---

## 📚 CRUD Operations Explained

| Operation | Route | Description |
|-----------|-------|-------------|
| Create | POST /add | Adds a new book |
| Read | GET / | Displays all books |
| Update | POST /edit/:id | Updates book details |
| Delete | GET /delete/:id | Deletes a book |

---

## 📊 Database Schema (Book Model)

```js
{
  title: String,
  author: String,
  status: {
    type: String,
    default: "Available"
  }
}
🎓 Educational Purpose

This project is built for learning purposes to understand:

MVC structure

CRUD operations

MongoDB integration

Express routing

Basic EJS templating

🔮 Future Improvements

User authentication

Role-based access (Admin/User)

Due date tracking

Fine calculation

Book cover image upload

Pagination

👨‍💻 Anshulok
This project is open-source and free to use for educational purposes.

Screenshots : Home Page
<img width="1911" height="749" alt="image" src="https://github.com/user-attachments/assets/56cba935-0eb7-472b-86b4-ce7158600dd0" /> 
1. Add Book Page
<img width="1910" height="583" alt="image" src="https://github.com/user-attachments/assets/5be49cd8-2c5f-4220-83e6-47be6759fa3f" /> 
