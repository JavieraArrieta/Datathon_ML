# Datathon Machine Learning - PI_02 Henry


## Descripción del problema
​
Usted ha sido contactado de una importante empresa inversora dentro del rubro de la inmobiliaria en Colombia, con el fin de que implemente un modelo de clasificación que permita clasificar el precio de las propiedades en venta, utilizando los datos que se han puesto a su disposición correspondientes al año 2020.

## Objetivo
Predecir la **categorización** de las propiedades entre baratas o caras, considerando como criterio el valor promedio de los precios (la media). 


## Pasos aplicados

 - Preprocesamiento de el dataset **properties_colombia_train.csv**<br>
 Lo encontramos en el archivo  **prep_train.ipynb** donde finalmente obtenemos el archivo **data_prep.csv**

- Luego si nos ubicamos en el archivo **modelos.ipynb** podemos ver el procedimiento del modelo que en este caso usamos el metodo de vecinos mas cercanos.<br>
Al final de este archivo encontramos la aplicacion del modelo al **data_test.csv** al cual lo preparamos previamente en el archivo **prep_test.ipynb**.<br>
- Una vez aplicado el modelo al **data_test.csv** guardamos las prediciones en el dataset **JavieraArrieta.csv**