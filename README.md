🌦️ Análisis Predictivo de Precipitación - Oaxaca (2011-2021)
Este repositorio contiene el desarrollo integral de un modelo de Machine Learning diseñado para predecir la probabilidad de lluvia en municipios específicos del estado de Oaxaca, México. El proyecto destaca por la integración de Big Data proveniente de sensores remotos y estaciones terrestres, permitiendo un análisis multivariable sobre el impacto del cambio climático y la contaminación regional.

🚀 Puntos Clave del Proyecto
Data Fusion Multifuente: Consolidación de un dataset de 858,888 registros mediante la unión de datos de CONAGUA (Precipitación), NASA POWER (Radiación y Temperatura) y SEMARNAT (Contaminantes PM10).

Ingeniería de Características: Implementación de binarización de objetivos, análisis de retardo (Lags) para radiación y tratamiento de vacíos mediante interpolación lineal.

Evaluación de Modelos: Comparativa de rendimiento entre Regresión Logística, Árbol de Decisión, Random Forest y XGBoost, logrando un F1-Score de 0.98.

Visualización Avanzada: Uso de Folium para la generación de mapas de calor interactivos y Seaborn para el análisis de importancia de variables.

🛠️ Stack Tecnológico
Lenguaje: Python 3.14.3 (Desplegado en entorno local con VS Code).

Librerías Principales: Pandas, NumPy, Scikit-Learn, XGBoost, Folium y Matplotlib.

Gestión de TI: El proyecto incluye documentación sobre la resolución de incompatibilidades técnicas (Sustitución de LSTM por Árbol de Decisión) y optimización de lectura de archivos CSV con codificación compleja.

📊 Hallazgos Principales (Insights)
Estacionalidad: El mes del año es el predictor dominante con un 64% de importancia.

Influencia Ambiental: Se validó que la Radiación Solar y los Contaminantes PM10 tienen un impacto significativo (aprox. 10% cada uno), actuando como variables activas en la formación de lluvia.

Mejor Modelo: De acuerdo con la Curva ROC, el modelo Random Forest (AUC=0.77) demostró la mayor capacidad de discriminación frente a modelos lineales tradicionales.
