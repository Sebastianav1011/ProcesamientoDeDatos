# Calidad del Agua con PySpark 

Este proyecto desarrolla un análisis de calidad del agua sobre datos de ríos de la India utilizando PySpark para procesamiento distribuido y Keras para modelos de predicción basados en redes neuronales.

Dataset utilizado

El proyecto utiliza el dataset waterquality.csv, el cual contiene registros de monitoreo de calidad del agua recolectados en diferentes ríos y estados de la India. Cada fila representa mediciones ambientales obtenidas en estaciones de monitoreo, incluyendo variables físico-químicas y biológicas relacionadas con la contaminación y el estado del agua.

- Oxígeno Disuelto (DO)
- pH
- Conductividad
- Demanda Bioquímica de Oxígeno (BOD)
- Nitratos y Nitritos
- Coliformes Fecales

El trabajo incluye:
- Limpieza y preprocesamiento de datos ambientales.
- Cálculo del índice Water Quality Index (WQI).
- Visualización y análisis exploratorio de parámetros físico-químicos.
- Análisis de correlación entre variables.
- Modelado predictivo usando redes neuronales.
- Generación de mapas y métricas de evaluación.

Tecnologías principales:
- Python
- PySpark
- Pandas
- Keras / TensorFlow
- Matplotlib
- GeoPandas
