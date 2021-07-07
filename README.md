# Proyectos de Ciencia y Análisis de Datos

### [Proyecto 1: Clasificador de Clientes de un E-commerce según patrones de consumo con K-Means](https://github.com/parrac22/clasificador-clientes-ecommerce)
#### Objetivos
* cargar un data frame con los datos de ordenes en formato de una fila por cada item de una factura.
* limpiar y transformar dichos datos para obtener metricas agregadas que representen la totalidad del historial de compras del un tercero, especialmente el gasto por categoria de producto.
* generar agrupaciones de clientes a partir de k-means clustering para determinar caracterisitcas comunes entre ellos, y así poder crear estrategias de comunicación e email marketing con el objetivo de aumentar las ventas.

### Logros
* creación de una tabla con información agregada por cliente, aplicando técnicas de limpieza de datos y feature engineering; con esto pasamos de más de 5000 observaciones, a un poco más de 1300.
* La categorización de los productos y la creación de las columnas de gasto por categoria con respecto a total gastado demostro ser de alta importancia al ser posible encontrar grupos de clientes marcados según su comportamiento en estas dimensiones.
* El test del puntaje de silueta arroja 10 como el número de clusters optimos al aplicarlo sobre modelos creados a partir de las columnas de gasto por categoria.
* Las metricas agregadas de fecha y consumo pueden otorgar caracteristicas adicionales de relevancia al momento de crear estrategias de comuniación.
* Se encuentran 10 grupos de clientes claramente diferenciados, donde ninguno de los grupos supera el 18% del total de observaciones, y el top 5 se encuentra en el rango de 10% a 18% de las observaciones.


![](https://github.com/parrac22/Portafolio-Carlos-Parra/blob/main/images/Curva-silueta.png)
