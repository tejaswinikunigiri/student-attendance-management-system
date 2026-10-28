# Student Attendance Management System

A web-based attendance management project built with Python, Flask, SQLite, HTML, and CSS.

## Features
- Student registration with duplicate roll-number prevention
- Dashboard with total students, today's present/absent counts, and attendance percentage
- Daily attendance marking with duplicate attendance prevention per student and date
- View all attendance records
- Student-wise attendance report
- Search attendance by date
- Export attendance records to Excel

## Requirements
- Python 3.10 or newer recommended
- pip

## Run locally

1. Download or clone this repository.
2. Open a terminal in the project folder.
3. Create a virtual environment:

   ```bash
   python -m venv .venv
   ```

4. Activate it on Windows:

   ```powershell
   .venv\Scripts\Activate.ps1
   ```

   If PowerShell blocks activation, use Command Prompt:

   ```bat
   .venv\Scripts\activate.bat
   ```

5. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

6. Start the application:

   ```bash
   python app.py
   ```

7. Open `http://127.0.0.1:5000` in your browser.

The SQLite database `students.db` is created automatically when the application starts.

## Project structure

```text
student_attendance_management_system/
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
└── templates/
    ├── base.html
    ├── index.html
    ├── register.html
    ├── attendance.html
    ├── records.html
    ├── student_report.html
    └── search_attendance.html
```

## Notes
- This is a learning/personal project. Change `app.secret_key` before deploying publicly.
- Do not upload private student data or your local database to a public repository.
