# Pollster

**Pollster** is a Django-based web application that allows users to create and vote on polls in a simple and interactive interface.

---

## 🚀 Features

- ✅ User-friendly interface for creating and voting on polls  
- 🧩 Modular app structure (`pages`, `polls`)  
- 🔐 Django admin interface for content management  
- 💾 SQLite database for quick local development  

---

## 📁 Project Structure

```
pollster/
├── db.sqlite3
├── manage.py
├── pages/
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
├── polls/
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
├── pollster/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
└── templates/
    ├── base.html
    └── pages/
        └── partials/
        └── polls/
```

---

## ⚙️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/KHANDAKERALIARIYAN/POLLSTER.git
   cd pollster
   ```

2. **Install dependencies**
   ```bash
   pip install pipenv
   pipenv install
   ```

3. **Apply migrations**
   ```bash
   pipenv run python manage.py migrate
   ```

4. **Run the development server**
   ```bash
   pipenv run python manage.py runserver
   ```

5. **Access the app**  
   Open your browser and visit: [http://localhost:8000](http://localhost:8000)

---

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Developed By
Khandaker Ali Ariyan
