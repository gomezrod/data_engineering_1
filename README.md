# Ingesta y manejo de datos desde API

Este repositorio contiene un notebook de Jupyter (Google Colab) donde se desarrolla una solución para extraer y almacenar datos desde la [API Aviationstack](https://aviationstack.com/), la cual ofrece información sobre vuelos, aeropuertos, y temáticas relacionadas.

## 🚀 Descripción

El objetivo de este proyecto es obtener datos relacionados a los vuelos de diversos aeropuertos. A través de este notebook, se realizan procesos de limpieza de datos, ingeniería de variables y almacenamiento para su posterior utilización.

## 🛠️ Tecnologías Utilizadas

* **Python 3.x**
* **Pandas & NumPy:** Para la manipulación y análisis de datos.
* **Requests:** Para manejo de peticiones a la API.
* **Deltalake:** Para el almacenamiento en formato open table.
* **Pyarrow:** Para permitir funcionalidades merge.
* **Faker:** Para generar datos falsos de prueba. 
* **Google Colab:** Entorno de desarrollo en la nube.

## 📋 Contenido del Notebook

1.  **Carga de Datos:** Importación de datasets y exploración inicial.
2.  **Preprocesamiento:** Limpieza de valores nulos, codificación de variables categóricas y normalización.
3.  **Almacenamiento en distintas capas:** Según el nivel de procesamiento.

## ⚙️ Cómo ejecutar el Notebook

Puedes ver y ejecutar este proyecto directamente en Google Colab haciendo clic en el siguiente enlace:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1KM88iUGaVvH4GGHEXixrOiLl_urrBI5F)

Deberás cargar un archivo .env con tu API Key, usa como ejemplo el archivo [.env.example](.env.example)

*Nota: Asegúrate de tener una cuenta de Google activa para poder ejecutar las celdas.*

## 📌 Autor

* **Rodrigo Gómez** - [GitHub](https://github.com/gomezrod)