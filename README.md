# 🍽️ Restaurant Management Website

Welcome to the Restaurant Management Website! This is a full-stack web application built with Django where users can browse the menu, place food orders, book a table, and share feedback. The admin panel allows managing items, viewing reservations, and handling customer interactions.

---

## 1. Overview & Features

### 👤 User Features
* **User Login & Logout:** Secure authentication system for customers.
* **Home, About, Menu & Feedback Pages:** A complete multi-page browsing experience.
* **Online Food Ordering:** Users can order food directly from the menu.
* **Table Booking:** Reserve a table by selecting date, time, and number of members.
* **Feedback Submission:** Share your dining experience through a feedback form.
* **Responsive UI:** Built with HTML, CSS, and Bootstrap for a seamless experience on all devices.

### 🔐 Admin Features
* **Menu Management:** Add, edit, or delete menu items.
* **Order Management:** View and manage all customer orders.
* **Table Bookings:** Access and manage all table reservations.
* **User Feedback:** View all submitted customer feedback.
* **Media Management:** Upload and manage food images via a dedicated media folder.

---

## 2. 🛠️ Tech Stack

| Layer | Technologies |
|---|---|
| **Frontend** | HTML, CSS, JavaScript, Bootstrap |
| **Backend** | Python, Django |
| **Database** | SQLite3 |
| **Static & Media** | CSS, JS, Images, Uploaded Files |
| **Environment** | Python Virtual Environment, python-dotenv |

---

## 3. 📁 Project Structure

```
Restaurant-Website/
│
├── Resturant_Project/
│   ├── Base_App/              # Main Django app (models, views, forms, admin)
│   ├── Media/                 # Uploaded media files (feedback, items)
│   ├── Static/                # Static assets (css, js, fonts, images)
│   ├── Template/              # HTML templates (base, home, about, menu, etc.)
│   ├── Resturant_Project/     # Django project settings, urls, wsgi, asgi
│   ├── manage.py              # Django management script
│   └── db.sqlite3             # SQLite database
│
├── requirements.txt           # Python dependencies
├── .gitignore                 # Git ignore rules
├── LICENSE                    # Project license
└── README.md                  # This file
```

---

## 4. 🚀 Getting Started

### Prerequisites
1. Python 3.8+
2. Git installed on your machine.

### Installation & Running Locally

1. **Clone this repository:**
   ```bash
   git clone https://github.com/sunilrangappa903/Restaurant-Website.git
   cd Restaurant-Website
   ```

2. **Create and activate a virtual environment:**
   ```bash
   python -m venv venv
   ```
   * Windows: `venv\Scripts\activate`
   * macOS/Linux: `source venv/bin/activate`

3. **Install the required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Navigate into the Django project folder:**
   ```bash
   cd Resturant_Project
   ```

5. **Apply database migrations:**
   ```bash
   python manage.py migrate
   ```

6. **Create a superuser (for admin access):**
   ```bash
   python manage.py createsuperuser
   ```

7. **Run the development server:**
   ```bash
   python manage.py runserver
   ```

8. **Open your browser** and visit `http://127.0.0.1:8000/` to explore the website!
   Access the admin panel at `http://127.0.0.1:8000/admin/`.

---

> **Note:** This project is built for educational and learning purposes.
