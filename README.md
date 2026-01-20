@"
# Task Manager App – Django

Aplicación web desarrollada con Django que permite a los usuarios gestionar sus tareas de forma simple y eficiente. Incluye autenticación, CRUD completo, búsqueda, contador de tareas pendientes y una interfaz limpia basada en plantillas HTML.

## Características principales

- Registro e inicio de sesión con autenticación integrada de Django
- CRUD completo de tareas: crear, leer, actualizar y eliminar
- Tareas privadas por usuario: cada usuario solo ve sus propias tareas
- Buscador de tareas por título
- Contador de tareas pendientes
- Interfaz simple y funcional basada en plantillas HTML
- Arquitectura clara y modular, ideal para aprendizaje y portafolio

## Tecnologías utilizadas

- Python 3.10 o superior
- Django 5
- HTML5 y CSS3
- SQLite3 como base de datos por defecto
- Git y GitHub para control de versiones

## Instalación y ejecución

### 1. Clonar el repositorio
git clone https://github.com/david-cardenas-dev/task-manager-app.git
cd task-manager-app

### 2. Crear entorno virtual
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows

### 3. Instalar dependencias
pip install -r requirements.txt

### 4. Aplicar migraciones
python manage.py migrate

### 5. Ejecutar el servidor
python manage.py runserver

La aplicación estará disponible en:
http://127.0.0.1:8000/

## Estructura del proyecto

proyecto/
│── proyecto/        # Configuración principal de Django
│── base/            # App principal con vistas, modelos y templates
│── manage.py
│── requirements.txt
│── README.md
│── .gitignore

## Próximas mejoras

- Sistema de categorías
- Paginación de tareas
- Modo oscuro
- API REST con Django REST Framework
- Tests unitarios

## Autor

David Cardenas
Desarrollador en transición , enfocado en soluciones limpias, modulares y bien documentadas.
GitHub: https://github.com/holamundodjc - LinkedIn: https://www.linkedin.com/in/davidjaviercardenas  - Email: davidjaviercardenascl@gmail.com 

## Licencia

Este proyecto se distribuye bajo la licencia MIT.
"@ | Out-File -Encoding UTF8 README.md

