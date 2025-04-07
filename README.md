📘 Attendance Management System

An Attendance Management System built with **Django**, **Python**, **HTML**, **CSS**, and **JavaScript** using **SQLite3** as the backend database.

This system is designed to manage and track student attendance, academic marks, and class timetables efficiently. It features **two main user sections**: **Teacher** and **Student**, each with a distinct set of features.

🚀 Features

### 👩‍🏫 Teacher Section
- ✅ **Take Attendance**: Teachers can mark daily attendance for students.
- 📊 **Upload Marks**: Teachers can upload students' academic scores.
- 🗓️ **Update Timetable**: Teachers can add, edit, or delete the class timetable.

### 👨‍🎓 Student Section
- 📅 **View Attendance**: Students can check their attendance history.
- 📝 **View Marks**: Students can view their subject-wise marks uploaded by teachers.
- 📘 **View Timetable**: Students can check the class timetable.



## 🛠️ Tech Stack

| Technology     | Description                      |
|----------------|----------------------------------|
| Django         | Backend web framework            |
| Python         | Core programming language        |
| HTML/CSS       | Frontend design & layout         |
| JavaScript     | Frontend interactivity           |
| SQLite3        | Lightweight relational database  |



## 🧑‍💻 How to Run the Project Locally

1. Clone the Repository

   ```bash
   git clone https://github.com/imdheeraj26/Attendance_Management_System.git
   cd Attendance_Management_System
2. Create a Virtual Environment
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate

3. Install Dependencies
   pip install -r requirements.txt
 
4. Run Migrations
   python manage.py makemigrations
   python manage.py migrate

5. Create Superuser(Admin)
   python manage.py createsuperuser

6. Start the Development Server
   python manage.py runserver

