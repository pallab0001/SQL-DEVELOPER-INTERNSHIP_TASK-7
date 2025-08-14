# 📘 Task 7: Views in SQL (Northwind Database)

This task demonstrates how to **create and use views** in SQL for **abstraction and security** using the `northwind.db` sample database.

---

## 📂 Project Structure
📁 SQL-Views-Task7/
├── northwind.db # SQLite database file
├── task7.sql # All CREATE VIEW statements and usage examples
├── README.md # Project documentation
└── result/ # (Optional) Query results/screenshots


---

## 📝 Description
The goal of **Task 7** is to:
- Understand what **views** are and why they are used.
- Learn how to create and query views.
- Use **views for abstraction and security** in a real database scenario.

---

## ✅ What is a View?
A **view** in SQL is a **virtual table** that:
- Stores the result of a **query**.
- Does **not** hold data physically (it’s a saved query).
- Simplifies complex queries by hiding join logic (**abstraction**).
- Restricts user access to sensitive data (**security**).

---

## ✅ Why Use Views?

### **1. Abstraction**
- A view acts like a virtual table that hides the complexity of the underlying query or schema.
- Instead of writing long, complex queries every time, you create a view once and use it like a table.

### **2. Security**
- Views can restrict access to certain columns or rows, so users see only what they are allowed to.
