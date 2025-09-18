# Django Storefront2

Storefront2 is a secure e-commerce API built with Django and Django REST Framework. It features an advanced API architecture with serializers, a fully functional shopping cart, and a robust order management system. The project includes Django’s authentication system for secure user management and role-based access, as well as an admin interface for managing products, customers, and orders efficiently. Designed with security and best practices in mind, it provides a solid backend foundation for any e-commerce application.

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


