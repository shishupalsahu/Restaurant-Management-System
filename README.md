# Restaurant Management System

A web-based **Restaurant Management System** built using **Python** and **Django** that allows users to order food, book tables, and manage reservations efficiently.

## Features

- **User Authentication** – Secure login and registration for customers and admins.
- **Online Food Ordering** – Add food items to the cart, place orders, and track status.
- **Table Reservation System** – Users can book tables based on real-time availability.
- **Admin Dashboard** – Manage menu, orders, reservations, and customer details.
- **Payment Integration** – Secure online transactions for food orders.
- **Order Management** – Admins can update order status and track payments.
- **Django ORM** – Used for efficient database management and retrieval.
- **Deployment** – Hosted on **Heroku** for public access.

## Tech Stack

- **Backend:** Python, Django, Django ORM
- **Frontend:** HTML, CSS, JavaScript, Bootstrap
- **Database:** SQLite / MySQL
- **Deployment:** Heroku

## Installation & Setup

### Prerequisites
- Python (>= 3.8)
- Django (>= 4.0)
- Virtual Environment (recommended)

### Steps to Run the Project

1. **Clone the Repository**
   ```bash
   git clone https://github.com/shishupalsahu/restaurant-management-system.git
   cd restaurant-management-system# Restaurant-Management-System


2. **Create and Activate Virtual Environment**
  ```bash
 python -m venv venv
source venv/bin/activate  # For Mac/Linux
venv\Scripts\activate  # For Windows



3. Install Dependencies
 pip install -r requirements.txt

4.Apply Migrations
python manage.py migrate

5. Create Superuser (For Admin Access)
python manage.py createsuperuser

6. Run the Development Server
   python manage.py runserver

   Open-  http://127.0.0.1:8000/ in your browser.
