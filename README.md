# 🤖 AI Data Analyst — Análisis de Datos Asistido por IA

Aplicación interactiva que combina el poder de los Modelos de Lenguaje (LLM) con análisis de datos en tiempo real. Carga cualquier dataset y obtén análisis exploratorios, visualizaciones e insights automáticamente — sin escribir una sola línea de código.

## 🎯 ¿Qué hace esta app?

Permite a cualquier persona (técnica o no) explorar un dataset en lenguaje natural y obtener análisis estadísticos y visualizaciones de forma inmediata.

Flujo de uso:
1. Carga tu dataset (CSV)
2. Haz preguntas en lenguaje natural: *"¿Cuáles son las variables con mayor correlación?"*, *"Muéstrame la distribución de ventas por región"*
3. El LLM genera el análisis, las visualizaciones y los insights automáticamente

## 🛠️ Stack Tecnológico

| Capa | Tecnología |
|------|-----------|
| Interfaz / UI | Streamlit |
| Orquestación LLM | LangChain |
| Análisis de datos | Pandas · NumPy |
| Visualizaciones | Plotly · Matplotlib · Seaborn |
| Lenguaje | Python 3.10+ |

## 🚀 Cómo ejecutarlo

### Requisitos previos
- Python 3.10+
- API Key de OpenAI o modelo local con Ollama

### Instalación

```bash
# 1. Clona el repositorio
git clone https://github.com/reinaldo-agp/ai-data-analyst.git
cd ai-data-analyst

# 2. Instala las dependencias
pip install -r requirements.txt

# 3. Configura tu API key
cp .env.example .env
# Edita .env con tu OPENAI_API_KEY

# 4. Ejecuta la app
streamlit run app.py
```

Luego abre tu navegador en `http://localhost:8501`

## 💬 Ejemplos de preguntas que puedes hacer

- *"Dame un resumen estadístico de todas las variables numéricas"*
- *"¿Hay valores nulos en el dataset? ¿En qué columnas?"*
- *"Muéstrame un heatmap de correlaciones"*
- *"¿Cuáles son los 5 registros con mayor valor en la columna ventas?"*
- *"Identifica posibles outliers en el dataset"*

## 🧠 Conceptos clave demostrados

- Agentes de análisis de datos con LangChain
- Generación automática de código Python para visualizaciones
- Ingeniería de prompts para análisis estadístico
- Interfaz conversacional para exploración de datos

## 🔭 Posibles extensiones

- Soporte para archivos Excel y bases de datos SQL
- Exportación de reportes automáticos en PDF
- Memoria conversacional para análisis multi-turno
- Deploy en Streamlit Cloud o Hugging Face Spaces

## 👤 Autor

Reinaldo Guerrero — Data Scientist Jr.
[LinkedIn](https://www.linkedin.com/in/reinaldo-guerrero-payares) · [GitHub](https://github.com/reinaldo-agp)

## 📄 Licencia

Licencia MIT — siéntete libre de usar y adaptar este proyecto.
