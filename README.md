<h1 align="center">Proyecto final de cursada</h1>
<h2 align="center">Análisis del dataset: Clasificación según su estilo de vida 🩺📊</h2>
<h5 align="center">Curso: Data Science II de Coderhouse</h5>
<h6>Profesores: Gustavo Benitez, Guillermo Mallo.</h6>
<h6>Alumna: Débora Landa.</h6>
<h6>Año: 2025</h6>

Archivos:
[Carpeta en Google Drive](https://drive.google.com/drive/folders/1Bn2gcBVJh_kO482aFS8Wl-1pvD6dQ1WT?usp=drive_link)
>[Health lifestyle CSV](https://drive.google.com/file/d/1_MAq74dISL3u6c0CA4LKtluo7O9fzT51/view?usp=drive_link)
>[Dataset en Kaggle](https://www.kaggle.com/datasets/mahdimashayekhi/disease-risk-from-daily-habits/data)
>[Health Style GoogleColab](https://drive.google.com/file/d/1ZOF0VwGzh3fVqvr_CF3-wdtDZhGnErvZ/view?usp=drive_link)
>[Story Telling](https://docs.google.com/presentation/d/15bl0rYm2fo8O5il8C6MXWMCp0erK2zkY/edit?slide=id.p1#slide=id.p1)


>📝 Descripción del Proyecto

Este proyecto se centra en el análisis de un conjunto de datos sobre el estilo de vida con el objetivo de predecir una variable target que identifica si el individuo es saludable. 
En este trabajo se limpiaron y se prepararon datos, para luego ser utilizados en modelos de Machine Learning.

>🎯 Objetivo

Obtener las mejores predicciones evaluando modelos de Machine Learning con la variable target.
>🤝Público objetivo:

Instituciones: Hospitales, clínicas médicas, médicos, licenciados en nutrición, personal trainers, gimnasios, profesores de educación física, kinesiólogos.

Equipos y tomadores de decisión: médicos, staff médico, gimnasios.

>📊 Datos

El análisis se realizó sobre el conjunto de datos [Health lifestyle CSV](https://drive.google.com/file/d/1_MAq74dISL3u6c0CA4LKtluo7O9fzT51/view?usp=drive_link)  que contiene información detallada sobre 100,000 individuos, incluyendo:

Datos demográficos: Edad, género, nivel educativo, tipo de trabajo.

Métricas de salud: IMC, presión arterial, frecuencia cardíaca, colesterol, etc.

Hábitos de estilo de vida: Horas de sueño, consumo de alcohol y tabaco, actividad física, dieta, etc.

>🛠 Metodología
La metodología se estructuró en las siguientes fases:

[Health Style GoogleColab](https://drive.google.com/file/d/1ZOF0VwGzh3fVqvr_CF3-wdtDZhGnErvZ/view?usp=drive_link)

```
Limpieza y transformación de datos
Verificación de Valores Nulos
Verificación de Valores duplicados
Transformación (Errores de tipeo)
Tratamiento de valores outliers
Análisis Exploratorio de datos
Feature Engineering
Feature Selection
Preprocesamiento de datos
Modelos
Optimización de modelos
Conclusiones Finales
```

>📈 Resultados
 *El modelo que predijo mejor fue Regresión logística, ya  que los otros modelos como Random forest hubo overfitting en los resultados.
 *Se realizó un balanceo de clases con Smote, Validación cruzada y Lasso. Mejoraron el modelo pero igual dieron overfitting.




>💻 Tecnologías y Librerías

Lenguaje: Python 

**Librerías:**
Pandas, NumPy, Scikit-learn , Seaborn,  Numpy, MatplotLib, Xgboost.

