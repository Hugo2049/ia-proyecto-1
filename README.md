# Proyecto 1 — Análisis y Clasificación de Tweets de Ciberacoso

Este repositorio contiene un análisis completo de tweets etiquetados por tipo de ciberacoso. El proyecto realiza exploración de datos (EDA), preprocesamiento de texto con técnicas de NLP, visualización de patrones y análisis estadístico para identificar características distintivas de diferentes tipos de ciberacoso en redes sociales. Se incluyen visualizaciones que muestran la distribución de clases, longitud de tweets y patrones de lenguaje para cada tipo de ciberacoso.

## Cómo ejecutar

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/Hugo2049/ia-proyecto-1.git
   cd ia-proyecto-1
   ```

2. Instalar dependencias (requiere Python 3.8+):
   ```bash
   pip install pandas numpy matplotlib seaborn nltk scikit-learn
   ```

3. Ejecutar el análisis:
   ```bash
   jupyter notebook proyecto.ipynb
   ```

4. Las visualizaciones generadas se guardan en la carpeta `imagenes_resultados/`.

## Estructura del Proyecto

- `proyecto.ipynb` — Notebook con el análisis completo
- `cyberbullying_tweets.csv` — Dataset con tweets etiquetados
- `imagenes_resultados/` — Carpeta con gráficas generadas
- `ia_proyecto_1.pdf` — Archivo con explicacion del proyecto y de los resultados obtenidos.
