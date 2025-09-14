###1. Clonar el Repositorio
git clone https://github.com/tuusuario/math-project.git
cd math-project


###2. rear Entorno Virtual
# Windows
py -m venv venv

# Linux/Mac
python3 -m venv venv


###3. Activar Entorno Virtual
bash
# Windows
.\venv\Scripts\activate

# Linux/Mac
source venv/bin/activate


###4. Instalar Dependencias
pip install -r requirements.txt


###5. Configurar Base de Datos
# Crear migraciones
python manage.py makemigrations

# Aplicar migraciones
python manage.py migrate


###6. Crear Superusuario (Opcional)
python manage.py createsuperuser
# Sigue las instrucciones para crear un usuario admin


###7. Ejecutar Servidor de Desarrollo
python manage.py runserver


###8. Acceder a la Aplicación
Abre tu navegador y ve a:
Aplicación: http://localhost:8000
Admin Django: http://localhost:8000/admin