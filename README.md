# To-Do List Application (Django)

## Project Overview
This is a simple To-Do List web application developed using Django as part of the Fullstack Internship – Assessment 1. The application allows users to create, view, edit, and delete to-do items with an easy-to-use interface.

## Features
- Create new to-do items
- View all to-do items
- View a single to-do item
- Edit existing to-do items
- Delete to-do items

## Technologies Used
- Backend: Django (Python)
- Frontend: HTML, Django Templates
- Database: SQLite
- Version Control: Git and GitHub

## Project Structure
todoproject/
├── todo/
│   ├── migrations/
│   ├── templates/
│   │   └── todo/
│   │       ├── index.html
│   │       ├── add_edit_todo.html
│   │       └── view_todo.html
│   ├── models.py
│   ├── views.py
│   ├── forms.py
│   └── urls.py
├── todoproject/
│   ├── settings.py
│   ├── urls.py
├── db.sqlite3
├── manage.py
└── README.md

## Installation and Setup
1. Clone the repository:
   git clone <github-repository-link>

2. Navigate to the project directory:
   cd todoproject

3. Create and activate a virtual environment:
   python -m venv venv
   venv\Scripts\activate

4. Install Django:
   pip install django

5. Apply database migrations:
   python manage.py migrate

6. Run the development server:
   python manage.py runserver

7. Open the application in your browser:
   http://127.0.0.1:8000/

## Application Modules

Module 1: To-Do Creation and Listing
- Add new to-do items with subject and notes
- Display all created to-do items on the home page

Module 2: To-Do Update and Deletion
- View and edit existing to-do items
- Delete to-do items from the list

## Submission Details
- Source code uploaded to GitHub
- Project submitted as a ZIP file
- Developed for Fullstack Internship – Assessment 1

