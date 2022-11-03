
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

Una vez realizadas las etapas anteriores se procedió a seleccionar un modelo. Como el objetivo es clasificar decidí utilizar Random Forest del módulo sklearn. Busqué los hiperparámetros que dieran el mejor ajuste y evalué el modelo con las métricas de accuracy y recall.






