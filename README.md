
# WorkshopDjango
Meu primeiro projeto django na fabrica/Unipe

# shell
# Criando venv
  python-m venv venv

# Crie um gitignore e escreva /venv/ dentro

# Ativar venv (Windows)
.\venv\Scripts\activate

# Instalar Django
pip install django

# Criar requirements
pip freeze > requirements.txt

# Criar a pasta do projeto django
django-admin startproject Workshop .

# Migrar banco de dados 
python manage.py makemigrations
python magane.py migrate

# Criar um usuario administrador para acessar o banco de dados do django
python manage.py createsuperuser

# Rodar o django
python manage.py runserver

python manage.py startapp nome_do_app

# Set-ExecutionPolicy -ExecutionPolicy RemoteSigned CurrentUser