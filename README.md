
El trabajo presente en el archivo notebook busca cumplir con el siguiente objetivo:

"Crear un modelo que debe predecir la **categorización** de las propiedades entre baratas o caras, considerando como criterio el valor promedio de los precios (la media)."

Se cuenta con dos datasets (uno de train, otro de test) con información de anuncios inmobiliarios de Colombia.

Etapas:

# 1- EDA / PREPROSESAMIENTO DE DATOS

El Análisis Exploratorio de Datos en resumen es una forma de entender, visualizar y extraer información relevante del set de datos para poder decidir cuál será la ruta o técnica más adecuada para su posterior procesamiento, donde se busca optimizarlos antes de entregarlos al modelo para que las predicciones que genere tengan sentido. Tener en cuenta que sin datos preprocesados ​​correctamente, no importará cuán avanzado y elegante sea el modelo, en última instancia, será ineficiente e inexacto.

Pasos realizados en:

EDA:

- Conocer las distintas características de los datos

- Determinar registros duplicados, valores nulos, valores atípicos, etc.

- Visualizar las relaciones entre variables.


Preprosesamiento de datos:

- Brindar solución a valores faltantes, atípicos y registros duplicados

- Codificar variables categóricas

- Seleccionar atributos relevantes/ reducción de dimensionalidad



## 2- Resolución del problema

Una vez realizadas las etapas anteriores se procedió a seleccionar un modelo. Como el objetivo es clasificar decidí utilizar "Random Forest" del módulo sklearn. Optimicé el modelo buscando los hiperparámetros que dieran el mejor ajuste, para ello empleé "GridSearCV". Además apliqué técnicas de cross validation, en éste caso "Stratified K-fold", con el objetivo de garantizar que el resultado del modelo no está relacionado a la técnica utilizada para dividir el set de datos en conjunto de train y test, "Statified K-fold" es una variante mejorada de "K-fold" que tiene la ventaja de mantener equilibradas las clases cuando hace los splits.Para finalizar, evalué el modelo con las métricas de accuracy y recall.

## Resultado:

Resultados verificados al realizar la predicción sobre el set de test (objetivo).

                                  RECALL        ACCURACY 
                                  0.7477401314	0.9025564686








