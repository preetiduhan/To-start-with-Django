mkdir tinyurlproject

cd tinyurlproject

virtualenv venv -p python3.6

source venv/bin/activate

pip install Django==2.1.*

django-admin startproject tinyurlproject

python manage.py runserver

