JobPortal

A simple job portal web application built using Django, designed to connect employers and job seekers on a single platform.

🚀 Features

User authentication system

Employers can create, update, and delete job posts

Job seekers can browse and apply for jobs

Admin panel for platform management

Clean and easy-to-use interface

🛠 Tech Stack

Backend: Django (Python)

Frontend: HTML, CSS, Bootstrap

Database: SQLite (default)

📦 Installation
1. Clone the repository
git clone https://github.com/kavyapulipati1/JobPortal.git
cd JobPortal

2. Create and activate virtual environment
python -m venv venv


Windows

venv\Scripts\activate


Mac / Linux

source venv/bin/activate

3. Install dependencies
pip install -r requirements.txt

4. Database configuration

Configure the database inside settings.py.
(Default SQLite works fine for development.)

🔄 Database Migration
python manage.py makemigrations
python manage.py migrate

📁 Collect Static Files
python manage.py collectstatic

▶️ Run the Server
python manage.py runserver


Open your browser and visit:

http://127.0.0.1:8000/

💡 Future Enhancements

Advanced job search and filters

Resume upload functionality

Email notifications

Employer and candidate profile pages

REST API integration

📝 License

This project is intended for learning and academic use.
