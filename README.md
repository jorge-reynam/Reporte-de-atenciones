# Sistema de Atenciones 2025-2026

## Descripción del Proyecto
Este proyecto analiza un entorno real de registros de atención ciudadana en 8 Centros de Trabajo (Pueblos). El objetivo es demostrar habilidades de **Data Wrangling** y **Análisis Estadístico** mediante un dataset diseñado con desafíos del mundo real: valores nulos, inconsistencias de texto, registros duplicados y tendencias estacionales.

### Objetivos Principales
1.  **Limpieza de Datos (Wrangling):** Normalización de nombres de centros, tratamiento de nulos y eliminación de outliers técnicos.
2.  **Análisis de Fidelidad:** Clasificación de usuarios en "Folios Nuevos", "Repetidos" y "Usuarios Nuevos".
3.  **Visualización de Tendencias:** Implementación de medias móviles para identificar el comportamiento real de la operación.


## Estructura del Repositorio
* `data_generator.py`: Script para generar el archivo Excel con tendencias y ruido.
* `eda_analysis.ipynb`: Notebook principal con el análisis exploratorio y visualizaciones.
* `dataset_realista_EDA_2026.xlsx`: El archivo de datos generado (incluido en el .gitignore si es muy pesado).


## Tecnologías Utilizadas
* **Python:** Lenguaje base.
* **Pandas:** Manipulación y limpieza de estructuras de datos.
* **NumPy:** Manejo de valores nulos y operaciones lógicas.
* **Matplotlib & Seaborn:** Creación de gráficos estadísticos y mapas de calor.
* **Openpyxl:** Motor para la exportación e importación de archivos Excel.


