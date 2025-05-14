# Django_Administration
Clone the repository
git clone https://github.com/Pavanikoduru/Django_Administration.git
cd suggesionbox

Create and activate a virtual environment
1)python3 -m venv venv
2)source venv/bin/activate

Install dependencies
pip install -r requirements.txt

Apply database migrations
python manage.py migrate

Create a superuser
python manage.py createsuperuser
Follow the prompts to set up your admin credentials.

Start the development server
python manage.py runserver

Access the application
Open your browser and go to: http://127.0.0.1:8000/admin/
Login using the superuser credentials.
