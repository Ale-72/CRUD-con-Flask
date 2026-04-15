# CRUD Kardex - Participacion 2

Aplicación web desarrollada con **Flask** y **SQLite** que permite gestionar un kardex de personas con operaciones CRUD completas.

## Funcionalidades

- **Listar** todas las personas registradas
- **Agregar** una nueva persona (nombre, teléfono, fecha de nacimiento)
- **Editar** los datos de una persona existente
- **Eliminar** un registro del sistema

## Tecnologías

- Python 3 + Flask
- SQLite (base de datos `kardex.db`)
- HTML con Jinja2 (templates)

## Estructura

```
kardex/
├── app.py          # Lógica principal y rutas de la aplicación
├── kardex.db       # Base de datos SQLite (se crea automáticamente)
└── templates/
    ├── base.html   # Plantilla base
    ├── index.html  # Lista de personas
    ├── create.html # Formulario de creación
    └── edit.html   # Formulario de edición
```

## Cómo ejecutar

```bash
# Activar el entorno virtual (con la libreria Flask instalada)
source venv/bin/activate

# Ejecutar la aplicación
python app.py
```

La app estará disponible en `http://127.0.0.1:5000`