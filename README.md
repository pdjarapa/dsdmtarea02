# tarea02

# Crear y activar un entorno virtual

virtualenv mysite

cd mysite

cd Scripts

activate

cd..

# Instalar Wagtail

pip install wagtail

# Genera mi sitio

wagtail start hw2wagtail dsdmtarea02

# Instalar dependencias del proyecto

pip install -r requirements.txt

# Crear la base de datos

python manage.py migrate

# Crear un usuario administrador

python manage.py createsuperuser

# Iniciar el servidor

python manage.py runserver

http://localhost:8000/

http://localhost:8000/admin
