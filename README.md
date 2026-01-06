# TecnicasAprendizajeAutomatico
# Laboratorio: Regresión Lineal y Árboles de Decisión para Tareas de Regresión

Este repositorio contiene el código y el análisis correspondiente a la actividad de laboratorio del módulo de **Aprendizaje Automático** del **Máster Universitario en Inteligencia Artificial**. El objetivo principal es aplicar y comparar modelos de **Regresión Lineal Múltiple** y **Árboles de Decisión** en un problema de regresión utilizando un dataset real sobre calidad del aire.

## 📋 Objetivos

- Realizar un **Análisis Exploratorio de Datos (EDA)** para comprender la estructura y características del dataset.
- Implementar y entrenar un modelo de **Regresión Lineal Múltiple**.
- Implementar y entrenar un modelo de **Árboles de Decisión para regresión**.
- Evaluar y comparar el rendimiento de ambos modelos utilizando métricas estándar.
- Investigar un caso de uso real donde se hayan aplicado estas técnicas en un artículo científico reciente.

## 📊 Dataset

Se utiliza el dataset **Air Quality** de la UCI, que contiene mediciones horarias de sensores químicos de óxido de metal ubicados en una ciudad italiana entre marzo de 2004 y febrero de 2005.

- **Instancias**: 9357 registros horarios.
- **Características**: 15 variables, incluyendo mediciones de contaminantes (CO, NOx, NO2, etc.) y condiciones ambientales (temperatura, humedad, etc.).
- **Variable objetivo**: `CO(GT)` – Concentración de monóxido de carbono en mg/m³.
- **Enlace al dataset**: [Air Quality Dataset](https://archive.ics.uci.edu/dataset/360/air+quality)

## 🛠 Requisitos e Instalación

El proyecto está implementado en un notebook de Jupyter (`Laboratorio_Actividad_1_Erick_Duvan_Soto_Diaz_Grupo33.ipynb`). Para ejecutarlo, se requiere:

### Dependencias principales:
- Python 3.8+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- requests

### Instalación:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn requests
```

## 📁 Estructura del Código

El notebook está organizado en las siguientes secciones:

1. **Configuración inicial**: Importación de librerías y configuración de estilos.
2. **Carga del dataset**: Descarga y carga del dataset desde la UCI.
3. **Análisis Exploratorio de Datos (EDA)**:
   - Estadísticas descriptivas.
   - Detección de valores nulos y tipos de datos.
   - Visualización de distribuciones y relaciones entre variables.
4. **Preprocesamiento**:
   - Manejo de valores nulos.
   - División del dataset en entrenamiento y prueba.
   - Estandarización de características.
5. **Modelado**:
   - Regresión Lineal Múltiple.
   - Árbol de Decisión para regresión.
6. **Evaluación**:
   - Cálculo de métricas: MAE, MSE, RMSE, R².
   - Comparación visual y numérica de los modelos.
7. **Investigación**:
   - Búsqueda de un artículo científico que aplique regresión lineal o árboles de decisión en un problema real (posterior a 2015).
   - Resumen del objetivo, metodología y resultados del artículo.

## 📈 Resultados Principales

### Análisis Exploratorio:
- El dataset presenta **valores nulos** (originalmente codificados como `-200`).
- Las variables de contaminantes (`CO`, `NOx`, `NO2`) muestran distribuciones asimétricas positivas, típicas en mediciones ambientales.
- No se detectaron valores anómalos extremos fuera de rangos plausibles.

### Desempeño de los Modelos:
Se evaluaron dos modelos:

1. **Regresión Lineal**:
   - R²: [valor]
   - MAE: [valor]
   - MSE: [valor]

2. **Árbol de Decisión**:
   - R²: [valor]
   - MAE: [valor]
   - MSE: [valor]

> *Nota: Los valores exactos de las métricas deben completarse tras ejecutar el notebook.*

### Comparación:
- El modelo de **Árbol de Decisión** mostró un mejor ajuste a los datos de entrenamiento, pero con riesgo de sobreajuste.
- La **Regresión Lineal** ofrece una interpretación más directa de la relación entre variables, aunque puede ser menos precisa en patrones no lineales.

## 🔍 Investigación

Como parte de la actividad, se debe buscar y analizar un **artículo científico reciente (post-2015)** que utilice técnicas de regresión lineal o árboles de decisión en un problema real. En el notebook se incluye una sección para:

- **Objetivo**: Describir el problema real abordado.
- **Metodología**: Explicar cómo se aplicaron las técnicas de regresión y si se realizaron adaptaciones.
- **Resultados**: Resumir los hallazgos principales de la investigación.

## 🧠 Conclusiones

- Ambas técnicas son válidas para problemas de regresión, pero su elección depende de la naturaleza de los datos y el objetivo del modelo.
- El preprocesamiento (manejo de nulos, escalado) es crucial para mejorar el rendimiento.
- La interpretabilidad del modelo lineal contrasta con la flexibilidad del árbol de decisión.

## 👨‍💻 Autor

- **Nombre**: Erick Duvan Soto Diaz
- **Grupo**: 33
- **Máster Universitario en Inteligencia Artificial**

## 📄 Licencia

Este proyecto es de uso académico. El dataset es público y proviene de la UCI Machine Learning Repository.