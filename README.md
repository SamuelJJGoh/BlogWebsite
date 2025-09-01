# Flask Blog Website

Welcome to my **Flask Blog Website**! This is a web application built using **Flask**, **PostgreSQL**, and other Python libraries to allow users to register, log in, and view my blog content.

---

## Live Website

You can visit the live website here: https://blogwebsite-ee3d.onrender.com/

---

## Features

- User registration and login
- Secure password storage with hashing
- Create, edit, and view blog posts
- User-friendly interface with Bootstrap styling

---

## Installation

To run this project locally:

1. Clone the repository:
```
git clone https://github.com/SamuelJJGoh/BlogWebsite.git
```

2. Create and activate a virtual environment (optional but recommended)
```
python -m venv venv
```
```
source venv/bin/activate
```

3. Install dependencies:
```
pip install -r requirements.txt
```

5. Set up your environment variables in a .env file:
- Flask secret key (generate a random one for your local setup)
```
FLASK_KEY=your_flask_secret_key_here
```

- Database URI (PostgreSQL example)
- Format: postgresql://username:password@host:port/databasename
```
DB_URI=postgresql://username:password@localhost:5432/your_database_name
```

 - Debug mode (True or False)
```
DEBUG=True
```

- Email account used by the website to send emails on the contact page
```
EMAIL=your_email@example.com
```
```
PASSWORD=your_email_password
```

 - Email address that receives messages from the website
```
EMAIL_RECEIVES_MESSAGE=receiver_email@example.com
```

5. Run the app:
```
python main.py
```
