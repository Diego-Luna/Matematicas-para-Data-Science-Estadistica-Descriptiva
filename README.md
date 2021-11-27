# Matematicas-para-Data-Science-Estadistica-Descriptiva

## Medidas de tendencia central

Son medidas que nos ayudan a resumir una gran cantidad de información en un solo numero

*   Media: Es el promedio de todos los datos, puede ser susceptible a valores atípicos
*   Mediana: es el dato central es decir tiene la misa cantidad de datos a su izquierda y derecha, no es lo mismo que la media
*   Moda: es el dato que mas se repite, la moda no aplica para datos numéricos continuos

### Diagrama de frecuencia
Es la representación grafica asociada a la tabla de frecuencia, normalmente todos los estadísticos descriptivos se pueden representar en términos de esta distribución

##Como dato curioso e interesante:
No solo existen esas 3 medidas de tendencias central, hay otras más poco conocidas, pero las abordaremos ahora mismo:

*   Media ponderada: es una medida de tendencia central, que es apropiada cuando en un conjunto de datos cada uno de ellos tiene una importancia relativa (o peso) respecto de los demás datos. Se obtiene multiplicando cada uno de los datos por su ponderación (peso) para luego sumarlos, obteniendo así una suma ponderada; después se divide esta entre la suma de los pesos, dando como resultado la media ponderada.
*   Media armónica: La media armónica es igual al número de elementos de un grupo de cifras entre la suma de los inversos de cada una de estas cifras.

En otras palabras, la media armónica es una medida estadística recíproca a la media aritmética, que es la suma de un conjunto de valores entre el número de observaciones.
Media geométrica: es una cantidad arbitraria de números (por decir n números) es la raíz n-ésima del producto de todos los números; es recomendada para datos de progresión geométrica, para promediar razones, interés compuesto y números índice.

## Diagramas de dispersión en el análisis de datos

[data viz project](https://datavizproject.com/)

## Transformación no lineal
¿Por qué usarlos?
En el caso donde haya datos fuertemente sesgados y no simétricos.
.

### Algunos tipos:

* **Logística**: los valores de la columna se transforman mediante la siguiente fórmula:

<p align="center">
  <img src="./imgs/img_1.png" width="1000" height="auto" alt="accessibility text">
</p>

* **LogNormal**: esta opción convierte todos los valores a una escala logarítmica normal. Los valores1 de la columna se transforman mediante la siguiente fórmula:

<p align="center">
  <img src="./imgs/img_2.png" width="1000" height="auto" alt="accessibility text">
</p>

Aquí μ y σ son los parámetros de la distribución, calculados empíricamente a partir de los datos como estimaciones de máxima verosimilitud, para cada columna por separado.


* **TanH**: todos los valores se convierten a una tangente hiperbólica. Los valores de la columna se transforman mediante la siguiente fórmula:

<p align="center">
  <img src="./imgs/img_3.png" width="1000" height="auto" alt="accessibility text">
</p>

## ¿Cuándo usarlos?
Justo antes de aplicar el escalamiento lineal, las transformaciones no lineales solo son para que nuestros datos queden lineales para luego aplicar la normalización lineal. Siempre se debe aplicar la normalización lineal.

