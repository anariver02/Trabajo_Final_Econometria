# Trabajo_Final_Econometria

## Predicción de la eficiencia energética de edificios residenciales

Repositorio asociado al trabajo final de Econometría sobre la predicción de la carga de calefacción (*heating load*) en edificios residenciales.

El objetivo es comparar el rendimiento predictivo y la interpretabilidad de cinco modelos: MCO, Lasso, Eco-RETINA, Random Forest y Red Neuronal, utilizando la misma partición train/test para todos ellos.

## Estructura del repositorio

- `docs/`: documentos del trabajo.
- `data/`: base de datos original y particiones train/test.
- `notebooks/`: códigos de Google Colab utilizados para estimar los modelos.
- `paper/`: artículo de referencia de Tsanas y Xifara (2012).

## Contenido

### `docs/`

- Descripción de la base de datos.
- Trabajo final en PDF.
- Resumen en inglés.

### `data/`

- Base de datos original.
- Muestra de entrenamiento.
- Muestra de test.

### `notebooks/`

- `01_MCO.ipynb`
- `02_Lasso.ipynb`
- `03_Eco_RETINA.ipynb`
- `04_Random_Forest.ipynb`
- `05_Red_Neuronal.ipynb`

### `paper/`

- Artículo de referencia utilizado para la base de datos.

## Reproducibilidad

Todos los modelos se estiman utilizando la misma partición aleatoria de la muestra: 75% para entrenamiento y 25% para test. Esto permite comparar de forma homogénea las métricas de predicción fuera de muestra entre algoritmos.

La base de datos y las particiones utilizadas se incluyen en formato CSV para facilitar la replicación de los resultados.
