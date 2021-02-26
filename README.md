# Aprendiendo Django
Voy a seguir [este tutorial](https://tutorial.djangogirls.org/es/)  
Y desplegando en [pythonanywhere](https://www.pythonanywhere.com/)

## Tutorial acortado

* Para crear la app
~~~
python3 -m venv myenv
source myenv/bin/activate

django-admin startproject mysite .
#Acá cambiás la configuración en mysite/settings.py
python manage.py migrate
python manage.py startapp blog
~~~

* Para correr el server
~~~
python manage.py runserver
~~~
