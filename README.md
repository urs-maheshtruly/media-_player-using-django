# media-_player-using-django

# Project Setup Instructions

Follow the steps below to set up and run the project on your local machine.

### 📦 Step-by-step Setup

1. **Download the ZIP file** and extract it.

2. **Place the project folder at:**

3. **Open Command Prompt inside the project folder and run:**

```bash
# Create virtual environment (if not already created)
python -m venv venv

# Activate virtual environment
.\venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Apply migrations
python manage.py makemigrations
python manage.py migrate

# Create superuser (follow the prompts to set username and password)
python manage.py createsuperuser

# Run the development server
python manage.py runserver



Access the project
Visit: http://127.0.0.1:8000/ in your browser.




make sure you install django-pip install django
