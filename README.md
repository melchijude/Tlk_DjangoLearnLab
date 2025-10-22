# Tlk_DjangoLearnLab

Welcome to **Tlk_DjangoLearnLab**, a Django-based personal blog project built as part of **Week 2: Django Basics** of the Django learning series.

This project demonstrates the foundational principles of Django's **MTV (Model-Template-View)** architecture. It includes setting up a Django project, defining models, using the ORM, creating views, rendering templates, and displaying data on the frontend.

---


---

## ✅ Features

- Django project and app setup
- `Post` model with `title`, `content`, and `created_at` fields
- Database setup using Django ORM
- Post creation via Django shell
- View to display all posts (`post_list`)
- Template system using `base.html` and `post_list.html`
- Nicely styled blog list with content previews

---

## 🛠 Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/YOUR-USERNAME/Tlk_DjangoLearnLab.git
   cd Tlk_DjangoLearnLab
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate
pip install django
python manage.py makemigrations
python manage.py migrate
python manage.py shell
# Then follow the commands in shell_commands.md
python manage.py runserver
http://127.0.0.1:8000/blog/

