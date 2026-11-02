# UDENARDBMS – Motor de bases de datos con integración de inteligencia artificial

Proyecto académico desarrollado en Java que consiste en la creación de un motor de bases de datos propio, capaz de interpretar y ejecutar sentencias SQL para gestionar información mediante operaciones CRUD. Además, integra un módulo de inteligencia artificial desarrollado en Python para el reconocimiento y clasificación de imágenes.

## Características principales

- Creación de tablas mediante `CREATE TABLE`.
- Operaciones SQL: `INSERT`, `SELECT`, `UPDATE` y `DELETE`.
- Procesamiento de sentencias SQL mediante JSQLParser.
- Gestión y persistencia de información en archivos.
- Integración de un módulo de inteligencia artificial para clasificación de imágenes.
- Comunicación entre los componentes Java y Python mediante sockets TCP.

## Arquitectura del proyecto

El proyecto está organizado en los siguientes componentes:

| Componente | Descripción |
|---|---|
| **UDENARDBMS** | Motor encargado de recibir y procesar las sentencias SQL. |
| **CRUDParser** | Interpreta las consultas y ejecuta las operaciones correspondientes. |
| **FileManager** | Gestiona la estructura y persistencia de los datos. |
| **UDENAR_IA** | Componente de inteligencia artificial desarrollado en Python. |
| **IA** | Gestiona la comunicación entre Java y el servicio de inteligencia artificial. |
| **UDENARSQL** | Aplicación cliente con interfaz gráfica desarrollada en Java Swing. |

## Tecnologías utilizadas

- Java
- Python
- JSQLParser
- TensorFlow y Keras
- OpenCV
- Java Swing
- Maven
- Jupyter Notebook

## Estructura del proyecto

```text
ProyectoDeGrado/
│
├── UDENARDBMS/
│   └── src/main/java/com/mycompany/udenardbms/
│       ├── UDENARDBMS.java
│       ├── CRUDParser.java
│       ├── FileManager.java
│       └── IA.java
│
├── UDENARSQL/
│   └── src/main/java/com/mycompany/udenarsql/
│       └── UDENARVIEW.java
│
├── UDENAR_IA/
│
├── Modelo/
│   └── entrenamientoPruebaModelo.ipynb
│
└── Imagenes-de-funciones-UDENARSQL/
```

## Mi participación

Participé en el desarrollo de los componentes principales del proyecto, enfocándome en:

- Desarrollo del motor de bases de datos en Java.
- Procesamiento e interpretación de sentencias SQL.
- Implementación de operaciones CRUD.
- Gestión y persistencia de la información.
- Desarrollo del módulo de inteligencia artificial.
- Integración y comunicación entre los componentes Java y Python mediante sockets.

La interfaz gráfica fue desarrollada por otro integrante del equipo.

## Estado del proyecto

Proyecto académico desarrollado como trabajo de grado. Algunas funcionalidades de modificación de estructura de tablas se encuentran incompletas.

## Reconocimientos

Este repositorio corresponde a una contribución derivada del proyecto original desarrollado en equipo: [HaroldAvila24/ProyectoDeGrado](https://github.com/HaroldAvila24/ProyectoDeGrado).
