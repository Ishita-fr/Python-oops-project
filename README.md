# Python-oops-project
# 📚 Library Management System

## 📝 Project Description

This Library Management System is a **console-based Python application** designed to simulate a real-world library's core functions. It allows a librarian or administrator to **manage books and users**, handle **borrowing and returning of books**, and persist data using **JSON files**.

The project showcases **object-oriented programming (OOP)** principles in Python, making use of classes like `Book`, `User`, and `Library`. It provides a functional CLI menu for user interaction and demonstrates how to structure a small system with proper encapsulation, data persistence, and interaction logic.

---

## 🎯 Objectives

- Create a simple, interactive system for library operations
- Apply OOP principles in a real-world context
- Use JSON to simulate a small-scale database
- Practice building maintainable and modular Python code

---

## 🧱 Key Components

### 1. `Book` Class
- Represents a book with attributes: title, author, ISBN, and availability
- Can be borrowed and returned

### 2. `User` Class
- Represents a user with name and ID
- Tracks which books the user has borrowed

### 3. `Library` Class
- Central management system that holds collections of books and users
- Handles borrowing, returning, searching, and registration
- Saves and loads data from `books.json` and `users.json`

---

## 🔄 Functionalities

- Add or remove books (if not borrowed)
- Register or remove users (if no borrowed books)
- Borrow and return books
- Search books by title, author, or ISBN
- Display all books or users
- Show which books a user has borrowed

---

## 📁 Data Storage

All books and user data are stored locally using JSON:
- `books.json` — list of all book objects
- `users.json` — list of all registered users and their borrowed books

This allows persistence across program restarts without needing a database.

---

## 👩‍💻 Why This Project?

This project is ideal for:
- Beginners learning Python and OOP
- Students practicing file I/O and JSON
- Demonstrating clean, modular code in portfolios
- Understanding system design with real-world analogy

---

## 🚀 How to Use

1. Run the Python file:
   ```bash
   python main.py
