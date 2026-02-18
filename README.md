# Gestor Forn Bon Gust

Aplicación sencilla de gestión para el negocio "Forn de Pa i Pastisseria Bon Gust".

## Descripción del proyecto

Esta aplicación permite gestionar:

- Productos (pan, pasteles, bollería...)
- Movimientos de stock (entradas y salidas)

El sistema está desarrollado en Python y utiliza SQLite como base de datos.

Se implementa un CRUD completo para:

1. Producto
   - Crear
   - Leer
   - Actualizar
   - Eliminar

2. Movimiento de stock
   - Crear
   - Leer
   - Eliminar

Cada vez que se registra un movimiento:

- Entrada → aumenta el stock
- Salida → disminuye el stock automáticamente

Esto permite controlar el inventario de forma digital y mantener la integridad del stock.

---

## Tecnologías utilizadas

- Python 3
- SQLite (base de datos integrada en Python)
- Programación modular (separación entre `main.py`, `database.py`, `models.py`)
- Git (para control de versiones)

---

## Estructura del proyecto

```
GestorBonGustProject
│
├─ main.py -------------------# Archivo principal con menú y ejecución
├─ models.py -----------------# Clases Producto y MovimientoStock
├─ database.py ---------------# Funciones CRUD y conexión a SQLite
├─ README.md -----------------# Documentación del proyecto
├─ requirements.txt ----------# Librerías necesarias (Aqui no se necesita, lo puse porque un proyecto grande lo tiene)
└─ .gitignore ----------------# Archivos ignorados en Git
```

## Crear un entorno virtual para la instalacion (opcional pero recomendable):

```bash
python3 -m venv venv
source venv/bin/activate -------- # Linux / macOS
venv\Scripts\activate    -------- # Windows
```

## Ejecutar la aplicación:

python main.py

## GRACIAS POR LA ATENCION =D
