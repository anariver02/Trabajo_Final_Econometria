# Trabajo_Final_Econometria

## Predicción de la eficiencia energética de edificios residenciales

Este repositorio contiene los materiales asociados al trabajo final de Econometría sobre la predicción de la carga de calefacción (*heating load*) en edificios residenciales.

El objetivo del trabajo es comparar el rendimiento predictivo y la interpretabilidad de cinco modelos: MCO, Lasso, Eco-RETINA, Random Forest y Red Neuronal, utilizando la misma partición train/test para todos ellos.

## Contenido actual

- `Base_Datos_Descripcion_Ana_Rivera.pdf`: documento descriptivo de la base de datos y del tratamiento de variables.
- `vs3_MLG_MCO_Claude.ipynb`: notebook de Google Colab correspondiente al modelo lineal general estimado por MCO.
- `README.md`: descripción del repositorio.

## Contenido previsto

El repositorio se irá completando con:

- Documento final del trabajo en PDF.
- Resumen en inglés.
- Base de datos original en formato CSV.
- Muestras `train` y `test` utilizadas en todos los modelos.
- Notebooks de Google Colab para:
  - MCO
  - Lasso
  - Eco-RETINA
  - Random Forest
  - Red Neuronal
- Artículo de referencia de Tsanas y Xifara (2012).

## Modelos estimados

- Mínimos Cuadrados Ordinarios
- Lasso
- Eco-RETINA
- Random Forest
- Red Neuronal

## Reproducibilidad

Todos los modelos se estiman utilizando la misma partición aleatoria de la muestra: 75% para entrenamiento y 25% para test. Esto permite comparar de forma homogénea las métricas de predicción fuera de muestra entre algoritmos.

La base de datos y las particiones utilizadas se incluirán en formato CSV para facilitar la replicación de los resultados.
