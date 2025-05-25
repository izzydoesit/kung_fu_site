# Hung Family Kung Fu – Midtown NYC Branch

This is a modern Django-powered website built for the Midtown NYC branch of the Hung Family Kung Fu school under the direction of Sifu Lloyd Wright (4th Dan Black Belt, Yee’s Hung Ga system).

💡 The goal is to offer an updated online presence to help new students discover traditional Hung Gar Kung Fu, class info, and contact Sifu directly.

## 🔧 Tech Stack

- Django 5.2
- Django Ninja (future API support)
- Gunicorn (for production WSGI serving)
- Bootstrap 5 (template styling)
- Render.com (deployment)

## 🚀 How to Run Locally

```bash
git clone https://github.com/izzydoesit/kung_fu_site.git
cd kung_fu_site
poetry install
poetry shell
python manage.py migrate
python manage.py runserver
```
