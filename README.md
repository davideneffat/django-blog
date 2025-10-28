# 📝 Mini Blog - Django

**Mini Blog** is a web application built with **Django**, designed to learn the basics of the framework and demonstrate core features: post management, user authentication and a dynamic web interface.

---

## 🚀 Key features
- Display of all published posts
- Create new posts via a web form
- User login and logout
- Admin panel for full content management
- Dynamic HTML templates for a user-friendly interface

---

## 🛠️ Technologies used
- **Language:** Python 3.x
- **Framework:** Django
- **Database:** SQLite (default)
- **Frontend:** HTML + Django templatess
- **Package management:** pip, virtualenv

---

## 📂 Project structure

django-social-network/
│
├── myblog/ # Django configuration
│ ├── settings.py
│ ├── urls.py
│ └── wsgi.py
│
├── blog/ # Main app
│ ├── models.py # Data models
│ ├── views.py # View logic
│ ├── urls.py # URL routing
│ ├── forms.py # Form for creating posts
│ └── templates/blog/ # HTML templatess
│
├── manage.py # Django commandss
└── db.sqlite3 # SQLite database


---

## ⚡ Installation and runninging

1. **Clone the repository***
```bash
git clone https://github.com/tuo-username/mini-blog.git
cd mini-blog
```

2. **Create and activate a virtual environment**nment**
```bash
python -m venv venv
# Windows
venv\Scripts\activate
# Linux / macOS
source venv/bin/activate
```

3. **Install dependencies**
```bash
pip install django
```

4. **Run migrations**
```bash
python manage.py makemigrations
python manage.py migrate
```

5. **Create a superuser** (optional, to use the admin)
```bash
python manage.py createsuperuser
```

6. **Start the server***
```bash
python manage.py runserver
```

App access:
- Homepage: http://127.0.0.1:8000/
- Create post: http://127.0.0.1:8000/new/
- Admin panel: http://127.0.0.1:8000/admin/