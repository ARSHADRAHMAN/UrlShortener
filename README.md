# UrlShortener
Url shortner project:
activate virtual env
pip install django
create src folder in env --> cd src
django-admin startproject app .
python .\manage.py startapp urlshort
python manage.py runserver


In app folder --> setting -->installed app --> add your app name i.e urlshort

cd ./src
python mange.py makemigrations
python mange.py migrations
