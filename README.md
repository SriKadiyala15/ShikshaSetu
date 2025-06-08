Required Commands - 
# 1. Create virtual environment
python -m venv venv

# 2. Activate the virtual environment (on Windows)
venv\Scripts\activate

# 3. Install dependencies from requirements.txt
pip install -r requirements.txt

# 4. Make migrations for your Django models
python manage.py makemigrations

# 5. Apply migrations to the database
python manage.py migrate

# 6. Run the Django development server
python manage.py runserver

# 7.To get access to Django admin create acc at 
python manage.py createsuperuser
