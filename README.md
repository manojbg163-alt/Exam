# Online Examination Software

This is a simple online examination software built with Flask and SQLAlchemy.

## Features

- User registration and login
- Admin panel for creating exams and adding questions
- Students can take exams and view results
- Basic scoring system

## Installation

1. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

2. Run the application:
   ```
   python app.py
   ```

3. Open your browser and go to `http://127.0.0.1:5000/`

## Usage

- Register as a user (check admin for admin access)
- Login
- Admins can create exams and add multiple-choice questions
- Users can take exams and see their scores

## Troubleshooting

- Ensure Python 3.7+ is installed
- If database issues, delete `exam.db` and restart