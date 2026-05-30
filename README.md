# Flask Auth 🔐

A simple authentication system built with Flask featuring user registration, login, logout, password hashing, and protected routes.

## Features

* User Registration & Login
* Secure Password Hashing
* Session Management with Flask-Login
* Protected Routes
* SQLite Database
* Authenticated File Downloads

## Installation

```bash
git clone https://github.com/shivam-cantcode/flask-auth.git
cd flask-auth

pip install flask flask-sqlalchemy flask-login werkzeug

python main.py
```

Visit: `http://127.0.0.1:5000`

## Routes

| Route       | Description             |
| ----------- | ----------------------- |
| `/`         | Home Page               |
| `/register` | Register New User       |
| `/login`    | User Login              |
| `/secrets`  | Protected Page          |
| `/logout`   | Logout User             |
| `/download` | Download Protected File |

## Tech Stack

* Flask
* Flask-SQLAlchemy
* Flask-Login
* SQLite
* Werkzeug

## Author

Shivam

⭐ Star this repository if you found it useful!
