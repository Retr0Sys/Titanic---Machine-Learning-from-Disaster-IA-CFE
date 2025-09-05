# Titanic---Machine-Learning-from-Disaster-IA-CFE
## Modelo de IA simple para la predicción de posibles supervivientes del Titanic
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
![200w](https://github.com/user-attachments/assets/48a6993c-6408-4bfa-a7cd-0f881bad3db0)
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Este proyecto presenta un modelo de inteligencia artificial para predecir la supervivencia de los pasajeros del Titanic. Se utiliza un enfoque de entrenamiento de K-Nearest Neighbors, en el que el modelo se entrena con un conjunto de datos histórico para identificar patrones y relaciones entre las características de los pasajeros y su destino final.

## 1. Preprocesamiento de datos
   
La fase inicial del proyecto se centra en el preprocesamiento del conjunto de datos de entrenamiento, "train.csv". Se aplican las siguientes técnicas:

Limpieza de datos: Se identifican y gestionan los valores nulos, atípicos y duplicados para asegurar la calidad y consistencia del conjunto de datos.

Ingeniería de características: Se eliminan las columnas irrelevantes que no aportan valor predictivo al modelo.

Análisis de datos por gráficas: Se realiza un análisis visual mediante gráficos para comprender la distribución de las variables y su relación con la supervivencia. En particular, se presta atención a la distribución de edades, acotando los rangos para eliminar valores que se desvían de los rangos demográficos esperados.

## 2. Desarrollo del modelo
Se utiliza un modelo de clasificación para predecir la variable dependiente "Survived". Se seleccionan las siguientes variables independientes, por su alta correlación demostrada con la supervivencia:

Age: Edad del pasajero.

Sex: Género del pasajero.

Pclass: Clase de boleto.

La elección de estas variables se justifica por su capacidad para capturar factores clave que influyeron en la supervivencia, como las políticas de rescate de "mujeres y niños primero" y la asignación de botes salvavidas basada en la clase social.

## 3. Evaluación y predicción

Una vez entrenado el modelo, se utiliza el conjunto de datos de prueba "test.csv" para generar las predicciones de supervivencia. Los resultados se formatean en un archivo de salida que se carga en la plataforma de la competición de Kaggle para su evaluación y validación.

## Resultados
El rendimiento del modelo se valida a través de la competición de Kaggle "Titanic - Machine Learning from Disaster", que proporciona una medida objetiva de su capacidad predictiva y permite comparar su desempeño con otras soluciones.

<img width="994" height="279" alt="image" src="https://github.com/user-attachments/assets/8014c9b5-cce0-4b0c-8fe7-14025da51ead" />
