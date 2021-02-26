# Aprendiendo Django
Voy a seguir [este tutorial](https://tutorial.djangogirls.org/es/)  
Y desplegando en [pythonanywhere](https://www.pythonanywhere.com/)

## Tutorial acortado

* Para crear la app:
	1. Crear el ambiente
		~~~
		python3 -m venv myenv
		source myenv/bin/activate
		~~~

	2. Crear el proyecto:
		~~~
		django-admin startproject mysite .

		#Acá cambiás la configuración en mysite/settings.py
		python manage.py migrate

		python manage.py startapp blog
		#Acá creás la clase para los posts en blog/models.py
		python manage.py makemigrations blog
		python manage.py migrate blog

		#Acá editás blog/admin.py
		python manage.py createsuperuser
		~~~

* Para correr el server:
~~~
python manage.py runserver
~~~
