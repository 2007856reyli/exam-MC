# Análisis del Dataset Auto MPG

## Descripción

Este proyecto tiene como objetivo analizar el rendimiento y las características mecánicas de diferentes vehículos utilizando el dataset **Auto MPG**.

Se aplican técnicas de limpieza de datos, transformación y visualización usando Python.

---

## Objetivo

Utilizar las librerías:

* Pandas
* NumPy
* Matplotlib

Para procesar, limpiar y extraer información valiosa del conjunto de datos.

---

## Dataset

El dataset fue obtenido desde:
https://raw.githubusercontent.com/mwaskom/seaborn-data/master/mpg.csv

Incluye información como:

* mpg (rendimiento)
* horsepower (caballos de fuerza)
* weight (peso)
* acceleration (aceleración)
* origin (origen del vehículo)

---

## Limpieza de Datos

Se realizaron los siguientes procesos:

* Identificación de valores nulos en la columna `horsepower`
* Reemplazo de valores nulos con la mediana
* Creación de una nueva variable:

  * `relacion_peso_potencia = weight / horsepower`

---

## Análisis y Visualización

Se generaron las siguientes gráficas:

### Histograma

* Distribución de la aceleración de los vehículos

### Gráfico de dispersión

* Relación entre desplazamiento (`displacement`) y caballos de fuerza (`horsepower`)

### Gráfico de barras

* Promedio de rendimiento (`mpg`) por país de origen (`origin`)

---

## Tecnologías utilizadas

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib

---

## Cómo ejecutar el proyecto

1. Abrir el archivo `.ipynb` en Google Colab
2. Ejecutar todas las celdas
3. Visualizar resultados y gráficas

---

## Resultados

El análisis permite:

* Identificar patrones en el rendimiento de vehículos
* Comparar eficiencia según el origen
* Analizar la relación entre variables mecánicas

---

##  Autor

REYLI ISAAC MORALES ZARAZUA 2007856

---
