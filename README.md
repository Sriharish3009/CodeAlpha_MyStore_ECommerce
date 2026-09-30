# MyStore – Full Stack E-Commerce Web Application

## 📌 Project Overview

MyStore is a full-stack e-commerce web application developed using HTML, CSS, JavaScript, Python, and Django.

The application allows users to browse products, search and filter products, manage their shopping cart, register and log in, enter delivery details, complete a demo payment, place orders, view order history, and track order status.

The backend is developed using Django and Django REST Framework, with SQLite used as the database.

## 🚀 Features

- Product browsing
- Product search
- Category filtering
- Product details
- Shopping cart
- User registration and login
- User profile
- Checkout
- Demo payment system
- Order creation
- Order history
- Order details
- Order status tracking
- Stock management
- Django Admin product management
- Responsive user interface

## 🛠️ Technologies Used

### Frontend
- HTML5
- CSS3
- JavaScript

### Backend
- Python
- Django
- Django REST Framework

### Database
- SQLite

### Development Tools
- Visual Studio Code
- Git
- GitHub

## 📁 Project Structure

```text
e-commerce/
├── backend/
│   ├── manage.py
│   ├── ecommerce/
│   ├── products/
│   └── media/
│
└── frontend/
    ├── index.html
    ├── product.html
    ├── cart.html
    ├── checkout.html
    ├── register.html
    ├── login.html
    ├── profile.html
    ├── orders.html
    ├── order-details.html
    ├── payment.html
    ├── css/
    └── js/


⚙️ Setup / Installation
1. Clone the Repository
git clone https://github.com/Sriharish3009/CodeAlpha_MyStore_ECommerce.git
cd CodeAlpha_MyStore_ECommerce
2. Create a Virtual Environment
python -m venv venv

Activate the virtual environment on Windows:

venv\Scripts\activate
3. Install Required Packages
pip install django djangorestframework pillow django-cors-headers
4. Run Database Migrations
cd backend
python manage.py migrate
5. Start the Django Backend
python manage.py runserver

The backend will run at:

http://127.0.0.1:8000/

6. Run the Frontend

Open the frontend folder in Visual Studio Code and run index.html using the Live Server extension.

The frontend will normally run at:

http://127.0.0.1:5500/frontend/

🔗 API Endpoints
GET /api/products/products/ – List products
POST /api/products/products/ – Create a product
GET /api/products/products/<id>/ – View product details
PUT /api/products/products/<id>/ – Update a product
DELETE /api/products/products/<id>/ – Delete a product
POST /api/products/register/ – Register a user
POST /api/products/login/ – Login a user
POST /api/products/orders/ – Create an order
GET /api/products/orders/history/ – View order history
💳 Payment

The project includes a demo payment system for demonstrating the checkout and order placement workflow.

No real payment gateway or real financial transaction is used.

📦 Product Images

Product images used by the application are included in:

backend/media/products/

🗄️ Database Note

The db.sqlite3 database file is intentionally not included in this repository for security and privacy reasons.

The repository contains the application source code and product images. Local database records such as user accounts, orders, and development data are not included.

Running the Django migration command creates a fresh local database.

🧪 Testing

The application was tested for:

Product browsing and search
Product details
Shopping cart
User registration and login
Profile management
Checkout
Demo payment
Order creation
Order history
Order status tracking
Stock reduction
Django Admin product CRUD operations
End-to-end shopping flow
🔮 Future Enhancements
Real payment gateway integration
Product reviews and ratings
Wishlist functionality
Email notifications
Advanced product filtering
Improved authentication and security
Deployment to a cloud platform
👨‍💻 Project

Developed as part of the CodeAlpha Full Stack Development Internship.

GitHub Repository:
https://github.com/Sriharish3009/CodeAlpha_MyStore_ECommerce
