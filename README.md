# 🎂 CS50X-Birthdays

**CS50X-Birthdays** is a simple web application built with **Flask** that allows users to **add, view, and delete birthdays** from a list. This project was my **first web app using Flask** and served as my **introduction to working with databases**, built as part of Harvard’s **CS50X** course.

## 🧠 Purpose

The project was designed to teach foundational web development concepts using Flask, HTML, and SQL. It introduces:

* Routing and HTTP methods
* HTML form handling
* SQLite database integration
* Rendering templates with Jinja2
* Basic CRUD operations (Create, Read, Delete)

## ✨ Features

* ➕ Add birthdays with a name, month, and day
* 📋 View all stored birthdays in a table
* 🗑️ Delete existing birthdays by ID or name (depending on implementation)
* 🛠️ Simple form validation for empty fields
* 🔄 Auto-refresh on submission using POST/Redirect/GET pattern

## 🛠️ Tech Stack

* **Python 3**
* **Flask** – Web framework
* **SQLite** – Lightweight relational database
* **Jinja2** – Templating engine
* **HTML/CSS** – Frontend structure and styling

## 📂 Project Structure

```
CS50X-Birthdays/
├── static/               # CSS files (optional)
├── templates/
│   └── index.html        # Main page template
├── app.py                # Flask application
├── birthdays.db          # SQLite database (generated)
└── README.md             # Project documentation
```

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/cs50x-birthdays.git
cd cs50x-birthdays
```

### 2. (Optional) Create a Virtual Environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install Flask

```bash
pip install Flask
```

### 4. Run the App

```bash
flask run
```

Then, open your browser and go to:
📍 `http://127.0.0.1:5000`

## 🗃️ Database Schema

The app uses a single table:

### `birthdays`

| Column | Type    | Description        |
| ------ | ------- | ------------------ |
| id     | INTEGER | Primary key (auto) |
| name   | TEXT    | Person's name      |
| month  | INTEGER | Birth month        |
| day    | INTEGER | Birth day          |

## 📚 Learning Outcomes

* Built a complete Flask app from scratch
* Learned to structure routes and templates
* Connected a Python app to a SQLite database
* Understood basic SQL operations in a web context
* Practiced form handling and server-side validation

## 👨‍💻 Author

Created by [@AceBurgundy](https://github.com/AceBurgundy)
🧠 Built as part of **CS50X – Harvard's Introduction to Computer Science**

## 📄 License

This project is licensed under the **MIT License**.
See the [LICENSE](LICENSE) file for more details.
