# <font color=orange>**Challenge Telecom X – Parte 2: Predicción de Cancelación (Churn)**

## Descripción y propósito del proyecto 🎯

- Este proyecto corresponde al tercer desafío del curso de Data Science de la formación Estadisticas y Machine Learning dictado por Allura Latam.
- Consiste en desarrollar un código en Google Colab para ayudar a la empresa TelecomX LATAM a comprender por qué está teniendo una alta tasa de evasión de clientes y hacer recomendaciones en base a los modelos de clasificación utilizados.


## Estado del proyecto 📋

:construction: Proyecto en construcción :construction:

Este proyecto cumple con todos los requisitos solicitados por el desafío de TelecomX II, sin embargo, es un proyecto que aún se puede mejorar para así seguir practicando lo aprendido.

## Estructura del proyecto 🛠️
El proyecto se estructura en 4 grandes áreas:
- `🛠️ Preparación de los Datos`: En esta sección se realiza la extracción del archivo, eliminación de columnas irrelevantes, encoding, verificación de la proporción de cancelación, balanceo y normalización de datos.
- `🎯 Correlación y Selección de Variables`: En esta sección es donde nos encargamos de relizar un análisis de correlación entre las variables numéricas y un análisis dirigido de algunas variables con la cancelación.
- `🤖 Modelado Predictivo`: En esta etapa creamos separamos los datos en conjuntos de entrenamiento y de prueba, luego creamos un modelo base, un modelo RandomForest y un modelo KNN, finalmente realizamos la evaluación de los modelos.
- `📋 Interpretación y Conclusiones`: A partir de todo el trabajo realizado anteriormente, podemos realizar un informe que interprete los resultados del modelo seleccionado y a partir de éstos tomar decisiones acorde al análisis de variables.

## Funcionalidades del proyecto 🔍

- `Funcionalidad 1`: Preparar la base de datos, seleccionando solo aquellas variables que tengan relación con la cancelación del servicio.
- `Funcionalidad 2`: Estudiar la correlación entre las variables explicativas y la variable respuesta.
- `Funcionalidad 3`: Creación y evaluación de modelos predictivos con diferentes estrategias.
- `Funcionalidad 4`: Interpretación de los resultados obtenidos basada en la importancia de variables y la correlación de éstas con la cancelación.

## Insights 🎯
A través del análisis de datos de TelecomX LATAM, logramos descubrir que los insights más relevantes en la evasión de clientes son el tipo de contrato, el medio de pago, tipo de servicio de internet y el tiempo de permanencia en la compañía.