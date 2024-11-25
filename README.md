![Casa](images/foto_casa.jpg)

# Proyecto: Predicción de Precios de Casas 🏠

## Introducción

La predicción de precios de bienes inmuebles es un área clave en la intersección de los negocios y la ciencia de datos. En este proyecto, abordarás el desafío de estimar el precio de las casas. Trabajaras con un conjunto de datos real, que contiene información detallada sobre propiedades en Madrid, como su tamaño, ubicación, número de habitaciones, tipo de propiedad, y más. El objetivo principal del proyecto es predecir el precio de una casa, 

## Contexto del Problema

El mercado inmobiliario es dinámico y está influenciado por múltiples variables, como la ubicación, las características de la propiedad y las condiciones económicas. Un modelo predictivo preciso puede ser una herramienta poderosa para agentes inmobiliarios, compradores y vendedores. Este proyecto te sumergirá en la complejidad de estos factores y te enseñará cómo transformarlos en conocimiento útil para la toma de decisiones.

## Pasos para el Desarrollo 

1. **EDA y tratamiento de nulos**

   - Seleccion de datos solo de madrid
    
   - Analisis exploratorio de los datos.
    
   - Eliminación de duplicados
     
   - selección de columnas numéricas y categóricas para el analisis
     
   - Identificación de nulos
     
   - Imputacion de nulos
   
2. **Preprocesamiento de Datos**

   - Encoding con One_Hot_Encoding y Target_Encoder

   - Estandarización de variables con RobustScaler.

   - Identificación de outliers univariados y multivariados.
  
   - Imputación de outliers con la mediana
     
  3. **Construcción del Modelo**

   - Test con DecisionTreeRegressor, RandomForestRegressor, RandomForestRegressor, XGBRegressor.

   - Modelo 1: Regresion Lineal

   - Modelo 2: KFold

   - Modelo 3: DecisionTreeRegressor

   - Modelo 4: RandomForestRegressor

   - Modelo 5: GradientBoostingRegressor

   - Modelo 6: XGBRegressor

     
#### Propuestas de Mejora:

   - Tratar de mejorar el modelo, seleccionando algunas columnas distintas en el prerprocesamiento.

   - Corregir tendencia al overfitting

   - Variar el orden en el preprocesamiento, haciendo la gestión de outliers y la estandarización antes del encoding.
     
   - Mejorar la calidad de algunas visualizaciones.

   - Generar más modelos predictivos

   - Mejorar la organización de los notebooks del repositorio.

  
## Construido con 🛠️

* [Pyhton](https://www.python.org/) - Lenguaje utilizado
* [Numpy](https://numpy.org/doc/stable/) - Numpy
* [seaborn](https://seaborn.pydata.org/tutorial.html) - Seaborn
* [matplotlib](https://matplotlib.org/stable/users/index) - matplotlib
* [pandas](https://pandas.pydata.org/docs/) - pandas
* [Visual Studio Code](https://code.visualstudio.com/) - IDE desarrollo
  
## Autor ✒️

* **Rafael Castellot de Miguel** - [rcm89](https://github.com/Rcm89)

