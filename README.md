Sistema de Detección de Fraude en Pagos Digitales
Este repositorio contiene el desarrollo de un modelo de Machine Learning diseñado para identificar transacciones fraudulentas en tiempo real, superando las limitaciones de los sistemas tradicionales basados en reglas.

 Resumen del Proyecto
El objetivo principal fue elevar el Recall (detección de fraude) desde un 23.52% inicial a un 97.96% final mediante el uso de un modelo Random Forest optimizado y técnicas de ingeniería de variables.

 Estructura del Repositorio

data/: Directorio que debe contener el dataset original Digital_Payment_Fraud_Detection_Dataset.csv.


notebooks/: Jupyter Notebook con el análisis exploratorio (EDA), ingeniería de variables y entrenamiento del modelo.

scripts/: Código Python para la ejecución del modelo y generación de métricas.


 Instrucciones de Ejecución
1. Requisitos Previos
Es necesario tener instalado Python 3.8 o superior. Se recomienda el uso de un entorno virtual:

2. Instalación de Dependencias
Instala las librerías necesarias ejecutando:

3. Ejecución del Modelo
Descarga el dataset desde  y colócalo en la carpeta data/.

Abre el notebook principal:

Ejecuta todas las celdas para reproducir la Ingeniería de Variables, el entrenamiento del Random Forest y la optimización del umbral a 0.198.

 Resultados Obtenidos

Recall Final: 97.96%.


Mejora en Eficiencia: 316% respecto al benchmark de reglas de IP.


Variables Clave: ip_risk_score, amount_ratio y account_age_days.
