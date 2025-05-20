# SQLite3 Understanding with Example

This repository provides a beginner-friendly understanding of **SQLite3** using simple and practical Python examples. It is designed for students, developers, or anyone new to databases who want to learn how to use SQLite in their Python applications.

## 🧠 What You’ll Learn

- What is SQLite?
- How to connect SQLite with Python.
- Creating a database and tables.
- Performing CRUD operations (Create, Read, Update, Delete).
- Using parameterized queries.
- Using Python functions for database tasks.
- Committing and closing connections.

## 📂 Repository Structure

All examples and explanations are provided in a **single Python file** to keep it simple and easy to follow.

```
sqlite3_example.py
README.md
```

## 🔧 Requirements

- Python 3.x  
- No external libraries required — SQLite comes built-in with Python.

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/shishiradk/sqlite3-understanding-with-example.git
cd sqlite3-understanding-with-example
```

2. Run the Python script:

```bash
python sqlite3_example.py
```

## 📘 sqlite3_example.py – What’s Inside

The script includes:

- **Database Connection:** How to connect to an SQLite database.
- **Table Creation:** Creating a sample table (`students`).
- **Insert Operation:** Adding new records using parameterized queries.
- **Fetch Operations:** Selecting data from the table using `fetchall()` and `fetchone()`.
- **Update Operation:** Updating student details based on ID.
- **Delete Operation:** Deleting records.
- **Functions:** Code is modularized with Python functions for better understanding and reuse.

## 📝 Example Table Schema

```sql
CREATE TABLE students (
    id INTEGER PRIMARY KEY AUTOINCREMENT,
    name TEXT NOT NULL,
    age INTEGER,
    department TEXT
);
```

## 📸 Sample Output

```text
Database connected.
Table created.
Student added successfully.
Fetching all students:
[(1, 'Alice', 21, 'CS'), (2, 'Bob', 22, 'IT')]
Student updated.
Student deleted.
Database closed.
```

## 🙌 Contribution

Feel free to fork the repo and improve or add more examples. Pull requests are welcome!

## 📄 License

This project is licensed under the MIT License.

---

Happy Learning! 🚀  
Author: [Shishir Adk](https://github.com/shishiradk)
