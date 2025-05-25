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

This will start the Django development server on port 8000. You can access the site by navigating to http://localhost:8000 in your web browser.

🛡️ License & Use
This codebase is licensed under the MIT License.
However, all brand assets, photos, and written content belong to Sifu Lloyd Wright and the Hung Family Kung Fu school.
Please do not reuse media or likeness without written permission.

For more about the lineage and organization, visit:

- [Yee’s Hung Ga Main Site](https://www.yeeshungga.com/)
- [Original Midtown Branch Site (being retired)](https://www.hungfamilykungfu.com/)
