# 🍳 Recipe Book Web Application

A clean and beginner-friendly **Django** application for creating, organizing, and managing recipes. The project features a nostalgic **90s-inspired web interface** while demonstrating core Django concepts such as models, views, forms, and CRUD operations.

---

## ✨ Features

- Create, update, and delete recipes
- Organize recipes using custom categories
- Search recipes by title or ingredients
- Filter recipes by category
- Store preparation time, cooking time, and serving size
- Set recipe difficulty levels
- Responsive and lightweight interface built with pure HTML and CSS

---

## 🛠️ Tech Stack

- **Backend:** Django 4.2
- **Language:** Python 3.8+
- **Database:** SQLite
- **Frontend:** HTML5 & CSS3 (Retro 90s theme)

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Amarnath201099/recipe_book_django.git
```

### 2. Create a Virtual Environment

**Windows**

```bash
python -m venv venv
venv\Scripts\activate
```

**macOS/Linux**

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Apply Database Migrations

```bash
python manage.py migrate
```

### 5. (Optional) Create an Admin Account

```bash
python manage.py createsuperuser
```

### 6. Run the Development Server

```bash
python manage.py runserver
```

Open your browser and visit:

```
http://127.0.0.1:8000/
```

---

## 📖 Usage

1. Click **Add Recipe** to create a new recipe.
2. Enter the recipe title, description, ingredients, and cooking instructions.
3. Select an existing category or create a new one.
4. Add preparation time, cooking time, servings, and difficulty level.
5. Save the recipe.

From the home page, you can browse all recipes, search by keyword, filter by category, and edit or delete existing entries.

---

## 📁 Project Structure

```text
Recipe-Book-App/
├── manage.py
├── requirements.txt
├── recipe_project/        # Django project configuration
├── recipes/               # Main application (models, views, forms, URLs)
└── templates/             # HTML templates
```

---

## 🎯 Learning Objectives

This project demonstrates several fundamental Django concepts, including:

- Django models and database relationships
- CRUD (Create, Read, Update, Delete) operations
- Function-based views
- Django forms and validation
- URL routing
- Template inheritance
- Search and filtering
- Django Admin integration

---

## 💡 Possible Improvements

Future enhancements could include:

- User authentication and personal recipe collections
- Recipe ratings and reviews
- Image uploads
- Printable recipe pages
- Import and export functionality
- Shopping list generation
- Favorites and bookmarks
- Responsive mobile-first design

---
