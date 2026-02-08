🏙️ Análisis de Alquileres de Propiedades – CDMX

Hemos sido contratados como científicos de datos por una empresa inmobiliaria. Nuestra principal función es brindar soporte al equipo de Aprendizaje Automático (Machine Learning) y al equipo de Desarrollo, aportando análisis, limpieza de datos y generación de insights que faciliten la construcción de modelos predictivos y el desarrollo de productos basados en datos.

Para atender estas demandas, se nos ha proporcionado las tareas del proyecto, así como una base de datos que utilizaremos como insumo principal para el desarrollo del análisis.

La base de datos contiene información sobre diferentes tipos de propiedades en Ciudad de México (CDMX), tales como departamentos, casas, locales comerciales, entre otros. Incluye tanto variables económicas como características físicas de cada inmueble.

🎯 Objetivos del Proyecto

Preparar y limpiar la base de datos para su uso en modelos de Machine Learning

Analizar los precios de alquiler de propiedades en CDMX

Explorar la relación entre características del inmueble y el valor del alquiler

Generar insights para apoyar decisiones del equipo de negocio

Proporcionar un dataset listo para consumo del equipo de Desarrollo

Facilitar la creación de modelos predictivos de precios de alquiler

📁 Fuente de Datos

Base de datos (CSV):
🔗 https://gist.githubusercontent.com/ahcamachod/a572cfcc2527046db93101f88011b26e/raw/ffb13f45a79d31223e645611a119397dd127ee3c/alquiler.csv

Variables incluidas (ejemplos):

Valor de alquiler

Costo de condominio

Impuesto inmobiliario

Tipo de propiedad (departamento, casa, local, etc.)

Número de habitaciones

Número de suites

Número de garajes

Otras características relevantes del inmueble

🛠️ Tecnologías y Herramientas

Python

Pandas – Manipulación y análisis de datos

NumPy – Operaciones numéricas

Matplotlib / Seaborn – Visualización de datos

Jupyter Notebook / Google Colab

Trello – Gestión de tareas del proyecto

🚀 Cómo Ejecutar el Proyecto
Opción 1: Google Colab (Recomendado)

Abre el notebook en Google Colab

Descarga el archivo alquiler.csv desde el enlace proporcionado

Súbelo a la sesión de Colab

Ejecuta las celdas en orden

Opción 2: Local (Jupyter Notebook)
git clone https://github.com/tu-usuario/real-estate-cdmx-analysis.git
cd real-estate-cdmx-analysis
pip install -r requirements.txt
jupyter notebook

📊 Análisis a Realizar

Limpieza de datos (valores nulos, outliers, formatos incorrectos)

Análisis exploratorio (EDA)

Distribución de precios de alquiler

Comparación de precios por tipo de propiedad

Relación entre número de habitaciones, suites, garajes y precio

Análisis de costos adicionales (condominio e impuestos)

Preparación del dataset para modelos predictivos

🔧 Problemas Comunes

Error: No module named 'pandas'

pip install pandas numpy matplotlib seaborn


Los gráficos no se muestran

%matplotlib inline


Problemas de carga del CSV

Verifica tu conexión a internet

Descarga el archivo manualmente desde el enlace y colócalo en la carpeta data/


📝 Notas

Los datos se utilizan con fines educativos y de práctica en ciencia de datos

El proyecto forma parte de un flujo de trabajo colaborativo con equipos de ML y Desarrollo

La planificación y tareas se gestionan mediante Trello
