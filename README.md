Proyecto de Clasificación de Estilos de Vida Saludables : https://drive.google.com/drive/folders/1Bn2gcBVJh_kO482aFS8Wl-1pvD6dQ1WT?usp=drive_link
Dataset: https://www.kaggle.com/datasets/mahdimashayekhi/disease-risk-from-daily-habits/data

📝 Descripción del Proyecto
Este proyecto se centra en el análisis de un conjunto de datos sobre salud y estilo de vida con el objetivo de predecir una variable target, que clasifica a los individuos en categorías de bienestar. A través de este trabajo, se exploran las características que influyen en los estilos de vida saludables, se limpian y preparan los datos, y se utiliza un modelo de Machine Learning para realizar predicciones.

🎯 Objetivo
El objetivo principal es construir un modelo de clasificación capaz de predecir la etiqueta target de un individuo basándose en un conjunto de variables demográficas, biométricas y de estilo de vida.

📊 Datos
El análisis se realizó sobre el conjunto de datos health_lifestyle_classification.csv, que contiene información detallada sobre 100,000 individuos, incluyendo:

Datos demográficos: Edad, género, nivel educativo, tipo de trabajo.

Métricas de salud: IMC, presión arterial, frecuencia cardíaca, colesterol, etc.

Hábitos de estilo de vida: Horas de sueño, consumo de alcohol y tabaco, actividad física, dieta, etc.

🛠 Metodología
La metodología se estructuró en las siguientes fases:

Análisis Exploratorio de Datos (EDA): Identificación de tipos de datos, valores nulos y distribución de las variables.

Preprocesamiento y Limpieza de Datos:

Imputación de valores nulos utilizando la mediana para variables numéricas.

Eliminación de columnas con varianza cero (electrolyte_level, environmental_risk_score), ya que no aportaban información útil.

Codificación de variables categóricas a numéricas (Label Encoding para variables ordinales y la variable target, y One-Hot Encoding para variables nominales).

Análisis de Correlación: Se calculó una matriz de correlación para entender la relación lineal entre las variables. Se encontró que la correlación lineal entre las características y el target era baja, lo que indicaba la necesidad de un modelo de Machine Learning más avanzado para capturar relaciones no lineales y complejas.

Modelado Predictivo:

Los datos se dividieron en conjuntos de entrenamiento y prueba.

Se utilizó un modelo de Random Forest Classifier, conocido por su robustez y capacidad para manejar la no linealidad, para predecir la variable target.

📈 Resultados
La correlación lineal simple entre las características y el target es muy baja.

A pesar de la baja correlación lineal, el modelo de Random Forest fue capaz de identificar patrones en los datos para realizar predicciones con una precisión de [Insertar Métrica de Precisión del Modelo].

💻 Tecnologías y Librerías
Python 3.x

Pandas: Para la manipulación y análisis de datos.

NumPy: Para operaciones numéricas eficientes.

Scikit-learn: Para el preprocesamiento de datos y la construcción del modelo de Machine Learning.

Seaborn & Matplotlib: Para la visualización de datos.
