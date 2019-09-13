### El problema 

Se proporciona un dataset con datos transaccionales referidos a ventas de distintos productos. El objetivo es construir un modelo de regresión simple para predecir las ventas por producto de una tienda en particular, que forma parte de una cadena de tiendas, y descubrir cuáles son los principales factores que influencian dicha predicción. 

### Asunciones 
+ La categoría del producto podría tener cierto impacto en las ventas: productos de consumo general se venden más que bebidas alcohólicas. 

+ El tipo de tienda y su ubicación es importante para las ventas. 

+ El tamaño de la tienda puede ser importante (¿la gente va a las tiendas grandes para comprar todo lo que necesita de una sola vez y conseguir mejores precios, o prefiere visitar tiendas pequeñas?) 

Su tarea es comprender los datos y mostrarnos el proceso de razonamiento utilizado para llegar a su resolución. Para ello, deberás: 
* Descargar y analizar los datos 
* Limpieza de datos 
* Gráficos 
* Tablas 
* Procesamiento de datos:
1. Seleccionar variables que consideres importante para el modelo  
2. Feature engineering para variables numéricas, categóricas y datetimes 
* Modelado: 
1. Entrenamiento 
2. Cálculo de métricas apropiadas 
3. Test o Aplicación de modelo en test dataset. 

Tener en cuenta que la solución deberá ser legible, reproducible y eficiente para la resolución del challenge. Se libre de elegir cualquier tipo de gráfico o tabla para mostrar la información del modo que creas conveniente.

### Los datos 
Se proveen dos archivos train y test con la misma estructura: 
* Item_Identifier: nombre o identificador del producto 
* Item_Weight: peso del producto en gramos 
* Item_Fat_Content: clasificación del producto en términos de grasas contenidas en él. 
* Item_Visibility: scoring de visibilidad del producto: medida que hace referencia al conocimiento del producto en el consumidor. ¿Qué tan fácil puede ser encontrado el producto? 
