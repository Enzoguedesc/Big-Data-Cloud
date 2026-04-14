## Criar o ambiente virtual

Contr + Shift + P 
python criate enviremente
.venv
python

## Instalar as dependencias 
pip install django djangorestframework pillow gunicorn

## Criar projeto Django e app REST
django-admin startproject catalogo .
python manage.py startapp produtos


Crie o banco de dados SQLite
`python manage.py migrate`


Requisitos do projeto
`pip freeze > requirements.txt`

Criar usuário na api
`python manage.py createsuperuser`


Rodar server local
`python manage.py runserver`
