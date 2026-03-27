# 📚 Proyecto de Base de Datos: Sistema Académico

Este repositorio contiene los scripts SQL necesarios para estructurar y poblar una base de datos diseñada para un sistema académico.

## 📂 Archivos del Proyecto

El proyecto está dividido en dos archivos principales para separar la estructura de la base de datos de los datos de prueba:

### 1. `Academico.sql` (Estructura / DDL)
Este archivo contiene el Lenguaje de Definición de Datos (DDL). Se encarga de construir la arquitectura de la base de datos.
* **Función:** Crea la base de datos, las tablas, las claves primarias, las claves foráneas y las restricciones (constraints).

### 2. `Datos.sql` (Población / DML)
Este archivo contiene el Lenguaje de Manipulación de Datos (DML). Se utiliza para insertar datos de prueba iniciales en las tablas creadas previamente.
* **Función:** Ejecuta sentencias `INSERT` para llenar la base de datos con información ficticia (o real) que permite probar el sistema.
* **Nota:** Depende directamente de la estructura creada en `Academico.sql`.

---
