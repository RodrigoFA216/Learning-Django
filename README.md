# Requerimientos
- Python 3.11.0^
- Vscode

# Inicio del proyecto
- Generar un entorno virtual
```bash
cd project
pip install virtualenv
python -m virtualenv venv
.\venv\scripts\activate.bat
pip install django
```

- Selecciona el intérprete
    - Ctrl+p
    - escribe python: Select interpreter
    - escoje el venv
    - abre una terminal con el comando Ctrl + Shift + ñ

Podemos verificar la instalación con una terminal que ejecute el venv con el comando 

    django-admin --version

- Iniciar un proyecto en Django
```
    django-admin startproject mysite .
```

- Ejecutar un proyecto de Django
```
python manage.py runserver
```