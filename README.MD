Restaurant Management Website:

Restaurant Management Website built using Django, where users can browse the menu, place food orders, book a table, and share feedback. The admin can manage items, view reservations, and handle customer interactions.
This project demonstrates backend development, form handling, template rendering, and database operations in Django.

Features:
User Features

User Login & Logout

Home, About, Menu & Feedback pages

Online Food Ordering

Table Booking (with date/time & members)

Feedback Submission

Responsive UI (HTML, CSS, Bootstrap)

Admin Features:

Add / Edit / Delete Menu Items

Manage Orders
View Table Bookings
Access User Feedback

Upload & Manage Food Images (Media folder)

Tech Stack:
Layer Technologies
Frontend HTML, CSS, JavaScript, Bootstrap
Backend Python, Django
Database SQLite3
Static & Media CSS, JS, Images, Uploaded Files
Environment Python Virtual Environment

Folder Structure:
Restaurant_Website/
│
├── Resturant_Project/
│ ├── Base_App/
│ │ ├── admin.py
│ │ ├── apps.py
│ │ ├── forms.py
│ │ ├── models.py
│ │ ├── views.py
│ │ └── migrations/
│ │
│ ├── Media/
│ │ ├── feedback/
│ │ └── items/
│ │
│ ├── Static/
│ │ ├── css/
│ │ ├── js/
│ │ ├── fonts/
│ │ └── images/
│ │
│ ├── Template/
│ │ ├── base.html
│ │ ├── home.html
│ │ ├── about.html
│ │ ├── menu.html
│ │ ├── login.html
│ │ ├── book_table.html
│ │ └── feedback.html
│ │
│ ├── db.sqlite3
│ ├── settings.py
│ ├── urls.py
│ ├── wsgi.py
│ └── asgi.py
│
├── manage.py
└── .env
