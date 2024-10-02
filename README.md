# User Management System

This is a simple User Management System built with Python using the Flask web framework and SQLite as the database. The system allows user registration, authentication (login), profile updates, and account deletion.

## Features

- User registration with email, username, and password.
- User authentication (login/logout).
- Profile management (update username/email).
- Account deletion.
- Secure password hashing using `werkzeug`.
- Basic form validation using `Flask-WTF`.

## Technologies

- **Flask**: Web framework.
- **Flask-WTF**: Form handling and validation.
- **Flask-SQLAlchemy**: ORM for database operations.
- **Flask-Login**: User authentication management.
- **SQLite**: Database.
- **Werkzeug**: Password hashing and security.

## Prerequisites

Make sure you have Python installed on your machine. You can check by running the following command:

```bash
python --version

Installation
git clone https://github.com/your-username/user-management-system.git

Navigate to the project directory:
cd user-management-system

Create a virtual environment:
python -m venv venv

Activate the virtual environment:
On Windows:
venv\Scripts\activate

On MacOS/Linux:
source venv/bin/activate

Install the required dependencies:
pip install -r requirements.txt

Create the database:
Open a Python shell and run:
from app import db
db.create_all()

Run the application:
flask run

