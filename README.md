
# Proyectos de Ciencia y Análisis de Datos

### [Proyecto 1: Clasificador de Clientes de un E-commerce según patrones de consumo con K-Means](https://github.com/parrac22/clasificador-clientes-ecommerce)
#### Objetivos
* Cargar un data frame con los datos de ordenes, originalmente en formato de una fila por item, y por factura.
* Limpiar y transformar dichos datos para obtener metricas agregadas que representen la totalidad del historial de compras de cada tercero, especialmente el gasto por categoria de producto.
* Generar agrupaciones de clientes a partir de k-means clustering para determinar caracterisitcas comunes entre ellos, y así poder crear estrategias de comunicación y email marketing, con el objetivo de aumentar las ventas.

### Logros
* Creación de una tabla con información agregada por cliente, aplicando técnicas de limpieza de datos y feature engineering; con esto pasamos de más de 5000 observaciones, a un poco más de 1300.
* La categorización de los productos y la creación de las columnas de gasto por categoria con respecto a total gastado demostro ser de alta importancia al ser posible encontrar grupos de clientes marcados según su comportamiento en estas dimensiones.
* El test del puntaje de silueta arroja 10 como el número de clusters optimos, al aplicarlo sobre modelos creados a partir de las columnas de gasto por categoria.
* Las metricas agregadas de fecha y consumo pueden otorgar caracteristicas adicionales de relevancia al momento de crear estrategias de comuniación.
* Se encuentran 10 grupos de clientes claramente diferenciados, donde ninguno de los grupos supera el 18% del total de observaciones, y el top 5 se encuentra en el rango de 10% a 18% de las observaciones.



![tabla_datos_agregados](https://user-images.githubusercontent.com/78557164/124692434-367b0700-dea3-11eb-97fa-b44a32c82cde.png)


![Curva-silueta](https://user-images.githubusercontent.com/78557164/124689286-dcc40e00-de9d-11eb-9b38-7272360d6301.png)

### [Proyecto 2: Predecir el tipo de cobertura de un bosque con un modelo de aprendizaje supervisado (Kaggel dataset, Académico)](https://github.com/parrac22/Cobertura-Bosques-Kaggle)

#### Objetivos
* Predecir la variable Cover_Type para cada una de las filas en el dataset de prueba (565892 observaciones).
* Obtener un puntaje de precisión satisfactorio con algún modelo de clasificación, preferiblemente superior al 80%.

### Logros
* Creación de Violin Plots para cada variable continua dentro del dataset, que permitió observar a mayor detalle las distribuciones de las mismas.
* Sin aplicar técnicas de normalización de datos, se obtuvó un puntaje de precisión del 86% con un modelo Random Forest.

![features 1](https://user-images.githubusercontent.com/78557164/124693336-dc7b4100-dea4-11eb-9ebb-27e78b447539.PNG)

![features 2](https://user-images.githubusercontent.com/78557164/124693342-e00ec800-dea4-11eb-93e9-0f95ce003d10.PNG)

### [Proyecto 3: Aplicación de técnicas de análisis exploratio de datos a datasets de biodiversidad en parques nacionales de USA (Académico)](https://github.com/parrac22/Analisis-Biodiversidad)

#### Objetivos
* Extraer información relevante oculta en dos datasets aplicando diversas técnicas de análisis, basados principalmente en el estado de conservación de las distintas especies. 

### Logros

* Se encuentra que la mayoria de las especies no estaban bajo estado de conservación.
* Los mamiferos y aves tienen el mayor porcentaje de especies bajo protección.
* Aplicando pruebas chi cuadrado, se encuentra que los mamiferos y aves tienen una diferencia estadisticamente significativa en comparación a otras categorias cuando se trata del porcentaje de especies bajo protección.
* Aplicando técnicas de procesamiento de lenguaje natural, se encuentra que el animal mamimefero más recurrente en este dataset es el murcielago, y las observaciones se dieron principalmente en el parque yellowstone.

![biodiversidad 1](https://user-images.githubusercontent.com/78557164/124695208-5fea6180-dea8-11eb-9626-226a689253c1.PNG)

![biodiversidad 2](https://user-images.githubusercontent.com/78557164/124695216-64af1580-dea8-11eb-9e0e-3ea70a0b2ae3.PNG)

