# Flask Student Management System

This project is a **Database-Driven CRUD Application built with Flask and SQLite**.  
It allows authenticated users to manage student records such as adding, editing, viewing, and deleting students.

## Features

- User Registration
- User Login and Logout
- Session-based Authentication
- Add Student
- View Students
- Edit Student
- Delete Student
- SQLite Database Integration

## Technologies Used

- Python
- Flask
- SQLite
- HTML
- CSS

## Project Structure

```
project
│
├── app.py
├── database.db
│
├── templates
│   ├── login.html
│   ├── register.html
│   ├── dashboard.html
│   ├── students.html
│   ├── add_student.html
│   └── edit_student.html
│
└── static
    └── style.css
```

## Installation

1. Clone the repository

```
git clone https://github.com/yourusername/flask-student-management.git
```

2. Navigate to the project folder

```
cd flask-student-management
```

3. Install Flask

```
pip install flask
```

4. Run the application

```
python app.py
```

5. Open your browser

```
http://127.0.0.1:5000
```

## Database

The project uses **SQLite database** (`database.db`) with two tables:

### Users Table
- id
- username
- password

### Students Table
- id
- name
- email
- course

## Author

Kanagasundaram  
MSc Computer Science  
Bharath College of Science & Management (Autonomous)

## Internship

This project was developed as part of a **Python Full Stack Web Development Internship Task**.
