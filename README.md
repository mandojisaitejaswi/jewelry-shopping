# Jewelry Shopping

Welcome to the **Jewelry Shopping** repository! This project is a Django-based e-commerce platform designed for users to browse, select, and purchase jewelry items online.

## Features

- **User Authentication**: Secure login and registration system.
- **Product Catalog**: Browse a wide range of jewelry items.
- **Shopping Cart**: Add or remove items before checkout.
- **Order Management**: Track and view order history.
- **Admin Panel**: Manage products, categories, users, and orders.
- **Search & Filter**: Find products easily based on categories and keywords.
- **Secure Transactions**: (If payment integration is implemented).

## Technologies Used

- **Frontend:** HTML, CSS, JavaScript (Bootstrap)
- **Backend:** Python (Django)
- **Database:** SQLite (Default) / PostgreSQL / MySQL
- **Authentication:** Django's built-in authentication system
- **Deployment:** AWS / Heroku / DigitalOcean (if applicable)

## Installation

### Prerequisites
- Python 3.x installed
- Virtual environment tool (venv recommended)
- Git installed

### Steps to Set Up Locally

1. **Clone the repository**:
   ```bash
   git clone https://github.com/mandojisaitejaswi/jewelry-shopping.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd jewelry-shopping
   ```
3. **Create and activate a virtual environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scriptsctivate`
   ```
4. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
5. **Apply database migrations**:
   ```bash
   python manage.py migrate
   ```
6. **Create a superuser for admin access**:
   ```bash
   python manage.py createsuperuser
   ```
   Follow the prompts to set up the admin credentials.

7. **Run the development server**:
   ```bash
   python manage.py runserver
   ```
8. **Access the application**:
   - User-facing site: `http://127.0.0.1:8000/`
   - Admin panel: `http://127.0.0.1:8000/admin/`

## Usage

- **For Users**:
  - Browse and search for jewelry products.
  - Add items to the shopping cart.
  - Register or log in to proceed with checkout.
  - View and track orders in the user dashboard.

- **For Admins**:
  - Manage products, categories, users, and orders through the admin panel.
  - Monitor sales and generate reports.

