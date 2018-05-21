"# python3.6_django_react_demo"

1. Run Backend API Server

cd backend/todo_api

python manage.py migrate
python manage.py makemigrations todos
python manage.py migrate todos
python manage.py createsuperuser
python manage.py runserver

http://127.0.0.1:8000/admin/
http://127.0.0.1:8000/api/


2. Run Frontend Server

cd frontend

npm install
npm start

http://localhost:3000/

