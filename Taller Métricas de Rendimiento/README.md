# Laboratorio de Clasificación con PySpark ML

Esta carpeta contiene el desarrollo del laboratorio de clasificación realizado para la clase de **Procesamiento de Alto Volumen de Datos**.

## Descripción

En este laboratorio se trabaja con el dataset **Bank Marketing**, cuyo objetivo es predecir si un cliente bancario suscribirá o no un depósito a plazo fijo. Para esto se utiliza **PySpark ML**, aplicando un flujo básico de procesamiento de datos, preparación de variables, entrenamiento de modelos y evaluación de resultados.

## Contenido de la carpeta

- `Lab_Clasification_Angulo.ipynb`: cuaderno principal del laboratorio.
- Archivos de apoyo o resultados generados durante la ejecución del cuaderno, si aplica.

## Herramientas utilizadas

- Python
- Apache Spark
- PySpark
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Actividades realizadas

- Carga del dataset.
- Exploración inicial de los datos.
- Conversión de tipos de variables.
- Análisis exploratorio de datos.
- Tratamiento de valores atípicos y variables poco informativas.
- Balanceo de la variable objetivo.
- Codificación de variables categóricas.
- Construcción de un pipeline con PySpark ML.
- Entrenamiento de modelos de clasificación.
- Evaluación mediante métricas como Accuracy, Precision, Recall, F1-Score y AUC-ROC.

## Modelos evaluados

- Regresión Logística
- Random Forest
- Árbol de Decisión
- Gradient Boosted Trees
- Support Vector Machine

## Resultado general

El laboratorio permitió comparar diferentes modelos de clasificación y analizar cuál tiene mejor desempeño para predecir la suscripción de un depósito a plazo fijo. El modelo con mejor desempeño general fue **Gradient Boosted Trees**, debido a su capacidad para capturar relaciones no lineales entre las variables.

## Autor

Sebastian Angulo Vergara  
Pontificia Universidad Javeriana  
Procesamiento de Alto Volumen de Datos
