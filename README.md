# Trinity Removals

A professional Django web application where customers can request moving services for furniture, houses, or apartments and store their requests in an administrative interface.

## 🚀 Features

- Service booking system
- Static and dynamic HTML templates
- Admin dashboard (Django admin)
- Clean and responsive frontend
- Easy deployment-ready structure

## 🛠️ Tech Stack

- Backend: Django (Python)
- Templates: HTML/CSS (Bootstrap or custom)
- Database: SQLite (default) or PostgreSQL (optional)

## 📦 Setup Instructions

```bash
# Clone the repository
git clone https://github.com/puuq/Trinity-Removals.git
cd Trinity-Removals

# Create virtual environment
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Apply migrations
python manage.py migrate

# Run development server
python manage.py runserver
