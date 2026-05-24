# Laboratorio de Clasificación con PySpark ML

Esta carpeta contiene el desarrollo del laboratorio de clasificación realizado para la clase de **Procesamiento de Alto Volumen de Datos**.

## Descripción

En este laboratorio se trabaja con el dataset **Bank Marketing**, cuyo objetivo es predecir si un cliente bancario suscribirá o no un depósito a plazo fijo. Para esto se utiliza **PySpark ML**, aplicando un flujo de procesamiento de datos, preparación de variables, entrenamiento de modelos y evaluación de resultados.

## Dataset

El dataset utilizado contiene información de campañas de marketing bancario. Cada registro representa un cliente contactado por el banco durante una campaña. La variable objetivo es `y`, que indica si el cliente suscribió (`yes`) o no suscribió (`no`) un depósito a plazo fijo.

### Variables del dataset

| Variable | Rol | Tipo | Descripción | Valores faltantes |
|---|---|---|---|---|
| `age` | Feature | Integer | Edad del cliente | No |
| `job` | Feature | Categorical | Tipo de trabajo del cliente | No |
| `marital` | Feature | Categorical | Estado civil del cliente | No |
| `education` | Feature | Categorical | Nivel educativo del cliente | No |
| `default` | Feature | Binary | Indica si el cliente tiene crédito en mora | No |
| `balance` | Feature | Integer | Balance anual promedio en euros | No |
| `housing` | Feature | Binary | Indica si el cliente tiene crédito hipotecario | No |
| `loan` | Feature | Binary | Indica si el cliente tiene préstamo personal | No |
| `contact` | Feature | Categorical | Tipo de medio de comunicación utilizado para contactar al cliente | No |
| `day_of_week` | Feature | Date | Último día de contacto de la semana | No |
| `month` | Feature | Date | Último mes de contacto del año | No |
| `duration` | Feature | Integer | Duración del último contacto en segundos. Esta variable no se conoce antes de realizar la llamada | No |
| `campaign` | Feature | Integer | Número de contactos realizados durante la campaña actual | No |
| `pdays` | Feature | Integer | Días transcurridos desde el último contacto en campaña anterior. El valor `-1` indica que no fue contactado previamente | Sí |
| `previous` | Feature | Integer | Número de contactos realizados antes de esta campaña | No |
| `poutcome` | Feature | Categorical | Resultado de la campaña anterior | Sí |
| `y` | Target | Binary | Indica si el cliente suscribió un depósito a plazo fijo | No |

## Contenido de la carpeta

- `Lab_Clasification_Angulo.ipynb`: cuaderno principal del laboratorio.
- `bank-full.csv`: dataset utilizado para el entrenamiento y evaluación.
- Archivos de apoyo o resultados generados durante la ejecución del cuaderno, si aplica.

## Herramientas utilizadas

- Python
- Apache Spark
- PySpark
- PySpark ML
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Actividades realizadas

- Carga del dataset.
- Exploración inicial de los datos.
- Conversión de tipos de variables.
- Análisis exploratorio de datos.
- Revisión de la variable objetivo.
- Tratamiento de valores atípicos y variables poco informativas.
- Balanceo de la variable objetivo.
- Codificación de variables categóricas.
- Construcción de un pipeline con PySpark ML.
- Entrenamiento de modelos de clasificación.
- Evaluación de resultados mediante métricas de clasificación.

## Modelos evaluados

- Regresión Logística
- Random Forest
- Árbol de Decisión
- Gradient Boosted Trees
- Support Vector Machine

## Métricas utilizadas

- Accuracy
- Precision
- Recall
- F1-Score
- AUC-ROC
- Matriz de confusión

## Resultado general

El laboratorio permitió comparar diferentes modelos de clasificación para predecir la suscripción de un depósito a plazo fijo. El modelo con mejor desempeño general fue **Gradient Boosted Trees**, debido a su capacidad para capturar relaciones no lineales entre las variables.

## Autor

Sebastian Angulo Vergara  
Pontificia Universidad Javeriana  
Procesamiento de Alto Volumen de Datos
