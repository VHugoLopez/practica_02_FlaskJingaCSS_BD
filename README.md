# Práctica 02 — Flask + Jinja + CSS + SQLite

**Asignatura:** Programación Web
**Tecnología principal:** Python (Flask)
**Persistencia:** SQLite

## Objetivo
Construir una aplicación web con Flask que capture datos de un alumno mediante un formulario HTML, los almacene en una base de datos SQLite y permita consultar y listar los registros utilizando una plantilla Jinja.

## Rutas
| Ruta | Función | Plantilla | Propósito |
|---|---|---|---|
| /  | inicio() | index.html | Mostrar formulario |
| /saludar | f_saludar() | saludar.html | Guardar y confirmar registro |
| /alumnos | listar_alumnos() | listar_alumnos.html | Consultar y mostrar alumnos |

## Ejecución local
Ejecutar: python app.py
Abrir en el navegador: http://127.0.0.1:5000

## Despliegue
Aplicación publicada en Render: https://practica-02-flaskjingacss-bd-9q74.onrender.com