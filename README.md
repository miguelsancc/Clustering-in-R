# Clustering-in-R

## Descripción del proyecto

Este proyecto forma parte de una práctica de la asignatura de Minería de Datos de la carrera. El objetivo es aplicar y comparar distintos métodos de clustering sobre un conjunto de datos de automóviles. Se emplean tanto el método jerárquico aglomerativo como el método de k-means para agrupar los datos y analizar los resultados.

Este repositorio contiene dos archivos principales:

1. `autos.csv`: Un archivo CSV que contiene datos sobre automóviles. Las variables incluidas son el año de fabricación, el modelo, la potencia, la cilindrada, entre otros.
2. `Clustering.Rmd`: Un archivo en formato R Markdown (`.Rmd`) donde se realiza un análisis de clustering utilizando distintos métodos en R.

### Contenido del archivo `autos.csv`

El archivo CSV contiene las siguientes variables:
- `year`: Año de fabricación
- `model`: Modelo del automóvil
- `power`: Potencia del motor
- `displacement`: Cilindrada del motor
- `other variables...`

### Análisis de Clustering

#### Método Jerárquico Aglomerativo

Se aplica el método jerárquico aglomerativo utilizando el enlace simple (single linkage). Los pasos incluyen:
1. Cálculo de la matriz de distancias euclídeas.
2. Aplicación del método de clustering jerárquico.
3. Visualización mediante un dendrograma.
4. Análisis de los clusters formados con diferentes valores de `k`.

#### Método k-means

Se aplica el método de k-means clustering:
1. Selección del número de clusters `k`.
2. Aplicación del algoritmo k-means.
3. Análisis de los centroides y los grupos formados.

## Objetivos del Proyecto

- Mostrar el uso de distintas funciones y librerías en R para realizar análisis de clustering.
- Comparar los resultados de diferentes métodos de clustering aplicados al mismo conjunto de datos.

## Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue o envía un pull request para contribuir a este proyecto.



