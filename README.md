# Django Storefront2

A fully-featured e-commerce backend built with Django and Django REST Framework, designed to manage products, customers, and orders efficiently. The project implements secure user authentication, role-based access control, and a RESTful API structure for seamless integration with front-end clients or third-party services.

### Key Features:

### User Management:
Registration, authentication, and customer profile management.

### Product Catalog: 
CRUD operations for products and categories with search and filtering capabilities.

### Order History: 
Tracks customer orders and purchase history.

### Admin Dashboard: 
Full control over products, customers, and orders through Django’s admin interface.

### API-First Design: 
REST API endpoints for all core resources, ready for frontend or mobile integration.

### Security & Best Practices: 
Role-based permissions, environment variable management for sensitive data, and proper database handling.

This project demonstrates a scalable backend architecture, clean code organization, and practical implementation of Django’s ORM, serializers, viewsets, and authentication mechanisms.
---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/leopirounis/storefront2.git
cd storefront2
```

### 2. Create a virtual environment

```bash
python3 -m venv .venv
source .venv/bin/activate   # macOS/Linux
.venv\Scripts\activate      # Windows
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Set environment variables

Create a `.env` file in the project root :

```
SECRET_KEY=your_secret_key_here
DB_NAME=storefront2
DB_USER=your_db_user
DB_PASSWORD=your_db_password
DB_HOST=localhost
DB_PORT=3306
```

### 5. Run migrations

```bash
python manage.py migrate
```

### 6. Create superuser (for admin access)

```bash
python manage.py createsuperuser
```

### 7. Run the development server

```bash
python manage.py runserver
```

Now open: [http://127.0.0.1:8000/store/](http://127.0.0.1:8000/store/)

---

## 📦 Database Seeding

If you want to load some test data:

```bash
python manage.py loaddata seed.json
```

or import `seed.sql` into MySQL.

---


