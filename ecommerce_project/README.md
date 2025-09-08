# Django eCommerce Platform

A full-featured eCommerce platform built with **Django**, supporting multiple vendors, buyers, carts, orders, reviews, and more.

---

##  Features

- **User Roles**
  - Vendor: Create and manage stores and products
  - Buyer: Browse, add to cart, checkout, leave reviews
- **Store Management**
  - Vendors can create multiple stores
  - Track products, stock, and activity
- **Product Management**
  - Create, edit, delete products with images
  - Stock quantity and active/inactive status
- **Shopping Cart**
  - Add/remove/update items
  - Session-based cart linked to user
- **Checkout & Orders**
  - Place orders with shipping address
  - Track order history
- **Reviews**
  - Buyers can review purchased products
  - Verified review badge
- **Authentication**
  - Custom user model with roles
  - Register, login, logout, profile management

---

## Tech Stack

- **Backend:** Django 5.x
- **Database:** MariaDb
- **Frontend:** Django Templates, Bootstrap 5
- **Other:** Django ORM, Crispy Forms, Messages Framework

---

## Installation

1. **Clone the repo**
   ```bash
   git clone https://github.com/YOUR-USERNAME/ecommerce_project.git
   cd ecommerce_project
2 **Creation of virtual enviroment***
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows
3***Install dependencies***
pip install -r requirements.txt
4. ***Apply migrations***
python manage.py migrate
5. **Create superuser***
python manage.py createsuperuser
6. **Run server***
python manage.py runserver


