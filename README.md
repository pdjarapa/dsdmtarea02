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

wagtail start mysite dsdmtarea02

# Instalar dependencias del proyecto

cd dsdmtarea02

pip install -r requirements.txt

# Crear la base de datos

python manage.py migrate

# Crear un usuario administrador

python manage.py createsuperuser

Username: admin 

Email: paulo.jara@unl.edu.ec 

Password: admin

# Iniciar el servidor

python manage.py runserver

http://localhost:8000/

http://localhost:8000/admin