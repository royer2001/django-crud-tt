# OPERACIONES CRUD EN DJANGO

OPERACIONES CRUD EN DJANGO

## Requisitos

- Python 3.x
- Django 3.x o superior
- Django REST Framework

## Instalación

1. Clona el repositorio:

   ```bash
   git clone https://github.com/royer2001/django-crud-tt.git
   ```

2. Navega al directorio del proyecto:

   ```bash
   cd django-crud-tt
   ```

3. Crea un entorno virtual:

   ```bash
   python -m venv venv
   ```

4. Activa el entorno virtual:

   - En Windows:

     ```bash
     venv\Scripts\activate
     ```

   - En macOS/Linux:

     ```bash
     source venv/bin/activate
     ```

5. Instala las dependencias:

   ```bash
   pip install -r requirements.txt
   ```

## Ejecución del Proyecto

Para iniciar el servidor de desarrollo, ejecuta:

```bash
python manage.py runserver
```

Visita `http://127.0.0.1:8000/` en tu navegador.

## Endpoints

El proyecto cuenta con los siguientes Endpoints para realizar alguna operación CRUD

`HTTP GET: /api/products/` --> LISTAR TODOS LOS REGISTROS

`HTTP GET: /api/products/{id}/` --> OBTENER UN REGISTRO PASANDO EL ID

`HTTP POST: /api/products/` --> INGRESAR UN NUEVO REGISTRO

`HTTP PUT: /api/products/{id}/` --> MODIFICAR UN REGISTRO EXISTETE PASANDO EL ID

`HTTP DELETE: /api/products/{id}/` --> ELIMINAR UN REGISTRO PASANDO EL ID