Personal AI Data Analyst

Aplicación interactiva de análisis de datos asistido por IA construida con Python y Streamlit, que permite cargar datasets y generar análisis exploratorios, visualizaciones e insights automáticamente.

El objetivo de este proyecto es demostrar cómo los Modelos de Lenguaje (LLM) pueden asistir el flujo de trabajo de análisis de datos, permitiendo explorar datasets y obtener insights rápidamente.

Demo del Proyecto

Aplicación Web:(https://reinaldo-agp-ai-data-analyst-app-erjode.streamlit.app/)

Repositorio: (https://github.com/reinaldo-agp/ai-data-analyst)

Descripción del Proyecto

Esta aplicación permite a los usuarios cargar datasets y realizar Análisis Exploratorio de Datos (EDA) de manera automática.

Formatos de archivos soportados:

CSV

Excel (XLSX)

JSON

Parquet

Una vez cargado el dataset, la aplicación puede generar automáticamente:

Resumen del dataset

Análisis estadístico

Visualizaciones

Análisis de series temporales

Detección de anomalías

Insights generados por IA

Además, el proyecto integra modelos de lenguaje ejecutados localmente usando Ollama para generar explicaciones y sugerencias de análisis.

¿Por qué usar Ollama?

El proyecto utiliza Ollama para ejecutar modelos de lenguaje de forma local.

Principales ventajas:

Privacidad: los datos permanecen en tu máquina

Sin costos de API

Menor latencia

Posibilidad de trabajar sin conexión

Ideal para entornos empresariales

Esto permite crear herramientas de análisis de datos basadas en IA sin enviar información sensible a servicios externos.

Tecnologías Utilizadas

Python
Streamlit
Pandas
NumPy
Matplotlib
DuckDB (opcional)
Ollama (integración con modelos LLM locales)

Arquitectura de la Aplicación

Carga del Dataset por el Usuario
↓
Procesamiento de Datos con Pandas / DuckDB
↓
Análisis Exploratorio de Datos (EDA)
↓
Generación de Visualizaciones
↓
Análisis opcional con IA usando Ollama
↓
Dashboard interactivo con Streamlit
