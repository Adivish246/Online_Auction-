# 🧑‍⚖️ Online Auction Platform

An Online Auction Platform built with Django, enabling users to list products for auction, bid on items, and manage auction events efficiently.

## 🚀 Features

* 🧾 User registration and authentication
* 📦 Product listing by users
* 🧑‍💻 Bidding system with real-time bid updates
* 🏆 Automatic winner determination
* 📊 Admin dashboard for user and auction management
* 🖼️ Media support for product images
* 📍 Location-based data using JSON city-state-country files

## 🛠️ Tech Stack

* **Backend:** Django (Python)
* **Database:** SQLite (default)
* **Frontend:** HTML, CSS, JS (basic templates with static assets)
* **Others:** Django Admin, JSON static files for location selection

## 📁 Project Structure

```
Online_Auction/
├── auction/                # Django app with models, views, migrations, static files
├── static/                 # CSS and image files for UI
├── db.sqlite3              # SQLite database
├── manage.py               # Django management script
└── .idea/                  # IDE config (ignore this)
```

## ⚙️ Installation

1. **Clone the repo:**

   ```bash
   git clone https://github.com/your-username/online-auction.git
   cd online-auction/Online_Auction/Online_Auction
   ```

2. **Create and activate a virtual environment:**

   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

3. **Install dependencies:**

   ```bash
   pip install -r requirements.txt  # Create this file if missing
   ```

4. **Apply migrations:**

   ```bash
   python manage.py migrate
   ```

5. **Create a superuser:**

   ```bash
   python manage.py createsuperuser
   ```

6. **Run the server:**

   ```bash
   python manage.py runserver
   ```

Visit `http://127.0.0.1:8000/` to access the application.

*Add UI screenshots here if available.*

## ✅ To Do

* Add AJAX real-time bidding
* Add email notifications
* Improve responsive UI


