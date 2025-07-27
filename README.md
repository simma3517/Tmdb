# Tmdb
The Movie Database
# TMDb Django Project

A Django-based web application inspired by TMDb (The Movie Database).  
Features include:
- ✅ Movie Listings
- ✅ Watchlist Functionality
- ✅ User Authentication (Login/Register)
- ✅ Ratings & Reviews
- ✅ Quiz System for Movie Fans
- ✅ Newsletter Subscription
- ✅ Admin Panel for CRUD Operations

---

## 🚀 Tech Stack
- **Backend:** Django (Python)
- **Frontend:** HTML, CSS, JavaScript
- **Database:** SQLite (default) / PostgreSQL (for deployment)
- **APIs:** TMDb API (for movie data)

---

## ⚡ Installation & Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/simma3517/tmdb.git
   cd tmdb

python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python3 manage.py migrate
python3 manage.py runserver
