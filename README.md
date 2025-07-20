# 🛍️ Django eCommerce Website

A backend-focused eCommerce website built with **Django**, featuring product listings, search, cart functionality, and a checkout system — complete with admin tools for managing products and orders.

---

## 🚀 Features

- 🔍 **Product Search** – Users can search for products by name  
- 📄 **Pagination** – Browse products in chunks with pagination support  
- 🛒 **Add to Cart** – Simulates a cart feature using item data  
- ✅ **Checkout System** – Collects user information and order data  
- 🧑‍💻 **Django Admin Panel** – Admins can add/edit products and view orders  

---

## 🧱 Tech Stack

- **Backend**: Django (Python)  
- **Frontend**: Django Templates, Bootstrap, jQuery  
- **Database**: SQLite (default with Django)  

---

## 📸 Screenshots

#### 🏠 Home Page
![Home Page](images/homepage.png)

#### 🔍 Product Search
![Search](images/search.png)

#### ✅ Checkout Page
![Checkout](images/checkout.png)

---

## 📂 Project Structure

shop/
├── models.py # Product and Order models
├── views.py # Views for index, detail, checkout
├── templates/shop/
│ ├── index.html # Homepage with product listings
│ ├── detail.html # Product detail page
│ └── checkout.html# Checkout form
├── static/ # (Optional) CSS/JS if added
└── ...


## 🛠️ Getting Started

Follow these steps to clone and run this Django eCommerce project locally.

### 🔄 1. Clone the Repository

```bash
git clone https://github.com/Soham-Kamble/Ecommerce-Site.git
cd Ecommerce-Site
```

### 🧪 2. Create a Virtual Environment

#### On macOS/Linux:
```bash
python3 -m venv env
source env/bin/activate
```

#### On Windows:
```bash
python -m venv env
env\Scripts\activate
```

### 📦 3. Install Dependencies

```bash
pip install --upgrade pip
pip install -r requirements.txt
```

### 🔐 4. Set Up Environment Variables

Create a `.env` file in the root directory and add:

```env
SECRET_KEY=your-django-secret-key
DEBUG=True
```

### 🧱 5. Run Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 🧑‍💻 6. Create a Superuser (for Admin Panel)

```bash
python manage.py createsuperuser
```

Follow the prompts to set your username, email, and password.

### 🚀 7. Start the Development Server

```bash
python manage.py runserver
```

Visit: [http://127.0.0.1:8000](http://127.0.0.1:8000)

To access the Django Admin Panel:  
[http://127.0.0.1:8000/admin](http://127.0.0.1:8000/admin)

---

## 🧹 Notes

- Ensure `.env` is **not committed** — it's already included in `.gitignore`.
- Use the Django admin panel to add products and view orders.
- Static files are loaded via templates or CDN.




