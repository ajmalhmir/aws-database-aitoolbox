sudo apt install python3 python3-pip

sudo apt install python3-venv

python3 -m venv env

source env/bin/activate

pip install django

django-admin startproject myproject

python manage.py startapp Api

pip install djangorestframework



install setting.py
'rest_framework',
'Api',

Step 1 make Models

Step 2 Regester Admin

Step 3 make serializers


python manage.py makemigrations
python manage.py migrate

cd myproject
python manage.py runserver