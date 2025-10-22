# Django Shell Commands for Creating Post Objects

This file contains the Django shell commands used to create at least three `Post` objects using the ORM (Object-Relational Mapping).

---

## 🔄 Step 1: Open the Django shell

```bash
python manage.py shell
# Post 1
post1 = Post.objects.create(
    title="Getting Started with Django",
    content="This post introduces the basics of Django, including how to set up a project and an app."
)

# Post 2
post2 = Post.objects.create(
    title="Understanding the MTV Pattern",
    content="The MTV (Model-Template-View) pattern is at the core of Django's architecture. This post explains how it works."
)

# Post 3
post3 = Post.objects.create(
    title="Using Django ORM Effectively",
    content="Learn how to use Django's Object-Relational Mapping (ORM) to interact with your database in a clean and Pythonic way."
)
