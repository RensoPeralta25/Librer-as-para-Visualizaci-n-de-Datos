# 📊 Librerías para Visualización de Datos – ICC-321 Inteligencia de Negocios

**Autor:** Scarlet Abreu y Renso Peralta  
**ID:** 10153953 y 10154062  
**Curso:** ICC-321 Inteligencia de Negocios  
**Profesora:** Lisibonny Beato 
**Fecha:** 26 de noviembre de 2025  
**Semestre:** 1-2025-2026  

---

## 📝 Descripción

Este notebook contiene la resolución de los ejercicios de **visualización de datos** usando Python, enfocados en el uso de las librerías:

- `matplotlib.pyplot`  
- `seaborn`  

El propósito es profundizar en técnicas gráficas para analizar y comunicar información de distintos datasets, explorando relaciones entre variables mediante:

- Gráficos de barras  
- Heatmaps  
- Scatter plots  
- Bubble charts  
- Boxplots  
- Violin plots  
- Mapas geoespaciales  

Cada sección incluye:

1. Limpieza y preprocesamiento de los datos cuando es necesario.  
2. Visualizaciones relevantes según la tarea solicitada.  
3. Comentarios y análisis sobre la interpretación de los gráficos.  

Los datasets utilizados provienen de **Kaggle** y se indican con sus enlaces.

---

## 📂 Contenidos

### 1️⃣ Riesgo de accidente cerebrovascular y hábitos de vida
- **Dataset:** [Stroke Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset)  
- **Variables:** `smoking_status`, `work_type`, `avg_glucose_level` (o `bmi`), `stroke`  
- **Visualizaciones:**
  - Barplot de la media de la variable numérica por combinación de `smoking_status` y `work_type`  
  - Heatmap con la misma información  
- **Análisis:** Comparación de claridad de los gráficos y su utilidad para distintos públicos (p.ej., personal de salud)

---

### 2️⃣ Intención de compra en comercio electrónico
- **Dataset:** [Online Shoppers Purchasing Intention Dataset](https://www.kaggle.com/datasets/imakash3011/online-shoppers-purchasing-intention-dataset)  
- **Variables:** `Revenue` (True/False), variable numérica seleccionada (por ejemplo, `PageValues`)  
- **Visualizaciones:**
  - Boxplot comparando la distribución de la variable numérica según `Revenue`  
  - Violin plot de la misma variable  
- **Análisis:** Interpretación de la distribución de usuarios y determinación de los más “valiosos”

---

### 3️⃣ Felicidad, economía y bienestar en países del mundo
- **Dataset:** [Global Happiness Scores and Factors](https://www.kaggle.com/datasets/sazidthe1/global-happiness-scores-and-factors)  
- **Variables:** `Happiness score`, `Log GDP per capita`, `Healthy life expectancy`  
- **Visualizaciones:**
  - Scatter plot de felicidad vs. desarrollo económico  
  - Bubble chart incluyendo variable de salud como tamaño y color  
- **Análisis:** Identificación de patrones entre riqueza, salud y felicidad; detección de outliers y agrupaciones de países

---

### 4️⃣ Propiedades físico-químicas y calidad del vino
- **Dataset:** [Wine Quality Dataset](https://www.kaggle.com/datasets/yasserh/wine-quality-dataset)  
- **Variables:** 5 propiedades físico-químicas + `quality`  
- **Visualizaciones:**
  - Matriz de correlación  
  - Heatmap con anotaciones de coeficientes de correlación  
- **Análisis:** Relaciones positivas y negativas entre propiedades del vino y calidad; identificación de variables más influyentes

---

### 5️⃣ Caídas de meteoritos en el mundo
- **Dataset:** [Meteorite Landings](https://www.kaggle.com/datasets/nasa/meteorite-landings)  
- **Variables:** `reclat`, `reclong`, `mass`, `year`  
- **Visualizaciones:**
  - Mapa de ubicaciones de meteoritos desde el año 2000  
  - Tamaño/color de los puntos según la masa del meteorito  
- **Análisis:** Observación de patrones geográficos y regiones con mayor concentración de meteoritos

---

## 🛠 Librerías utilizadas

- `pandas` – manejo y preprocesamiento de datos  
- `matplotlib.pyplot` – gráficos básicos  
- `seaborn` – visualizaciones estadísticas  
- `geopandas` – mapas y datos geoespaciales  
- `numpy` – cálculos numéricos básicos  

---

## ⚠️ Notas

- Todas las visualizaciones incluyen celdas **Markdown** explicando los hallazgos.  
- Se recomienda abrir el notebook en **Jupyter Notebook** para una correcta visualización de gráficos y Markdown.  
- Cada sección puede ejecutarse de manera independiente luego de cargar el dataset correspondiente.
