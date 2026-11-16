 🎓 Student Management System

 About the Project

The **Student Management System** is a web application developed using Python and FastAPI.

This application is designed to manage student information efficiently. Users can add new students, view all student records, view individual student details, update student information, and delete student records.

This project implements all four CRUD operations (Create, Read, Update, Delete) using FastAPI and SQLite.

 🚀 Technologies Used

- **Python** – Backend programming language.
- **FastAPI** – Web framework for building the application.
- **SQLite** – Database for storing student information.
- **HTML** – Structure of web pages.
- **CSS** – Styling and designing web pages.
- **Jinja2** – Dynamic HTML templates.
- **Pydantic** – Data validation.
- **Uvicorn** – ASGI server to run the application.

 ✨ Features

 1. Create Student
- Add new student information.
- Enter student name, age, gender, marks, course, image and status.
- Save student records in the SQLite database.

 2. Read Student
- Display all student records.
- View individual student details using Student ID.
- Display student information dynamically.

 3. Update Student
- Edit existing student information.
- Update student records using Student ID.
- Save updated information in the database.

 4. Delete Student
- Delete student records using Student ID.
- Remove unwanted student information from the database.

💻 FastAPI Concepts Implemented

- FastAPI Application Creation
- API Routing
- GET and POST Methods
- Request Handling
- Form Data Handling
- Dynamic URL Parameters
- SQLite Database Connectivity
- SQL Queries
- Pydantic Models
- Data Validation
- Jinja2 Templates
- TemplateResponse
- RedirectResponse
- CRUD Operations

 📂 Project Structure

```text
Student-Management-System/
│
├── main.py
├── students.db
├── requirements.txt
├── README.md
│
├── templates/
│   ├── home.html
│   ├── add_student.html
│   ├── update_student.html
│   └── student_details.html
│
└── static/
    ├── css/
    └── images/
```

 ⚙️ Installation and Setup

 Step 1: Clone the Repository

```bash
git clone https://github.com/likhithanagadiyva/Student-Management-System.git
```

 Step 2: Navigate to the Project Folder

```bash
cd Student-Management-System
```

Step 3: Create a Virtual Environment

```bash
python3 -m venv venv
```

Step 4: Activate Virtual Environment

```bash
source venv/bin/activate
```

Step 5: Install Required Packages

```bash
pip install -r requirements.txt
```
 Step 6: Run the Application

```bash
uvicorn main:app --reload
```

### Step 7: Open the Application

Open your browser and visit:

http://127.0.0.1:8000

 🎯 Learning Outcomes

Building this project helped me understand and practically implement FastAPI fundamentals.

Through this project, I gained hands-on experience in:

- Creating web applications using FastAPI.
- Connecting Python with SQLite databases.
- Performing CRUD operations.
- Handling HTML forms and user inputs.
- Validating data using Pydantic.
- Working with Jinja2 templates.
- Connecting frontend pages with backend logic.
- Understanding how different FastAPI concepts work together in a real-world application.

🙏 Acknowledgement

I would like to thank **Innomatics Research Labs** and **Full Stack Experts Academy** for providing me with the opportunity to learn these technologies and implement them through practical projects.

 👩‍💻 Author

** Likhitha Naga Divya **

GitHub Profile: https://github.com/likhithanagadiyva

---

⭐ Thank you for visiting my Student Management System project!


