# Bank loans analysis (Python)

## Project Overview
- Se requiere saber que factores influyen en la entrega de un prestamo
- Se necesita buscar alguna oportunidad de aumentar los activos del banco
- Se encontro que aparte de los ingresos, el tamaño de la familia es un factor importante
- Las librerias usadas fueron pandas, numpy, matplotlib.pyplot, seaborn y scipy
- Puede acceder a la Jupiter Notebook en este enlance ENALCE

## Objetivos
Pregunta central:

**Cual es el factor mas importante para la entrega de un prestamo**

Otras preguntas:
* Que relacion hay entre la educacion y los prestamos
* Como es la distribucion de la poblacion de los clientes
* Que tipos de cuentas y seguros poseen nuestros clientes
* Que relacion hay entre los ingresos y los prestamos
* Que relacion hay entre la hipoteca y los prestamos

## Limpieza y preparacion de datos
Despues de importar las librerias se prepararon los datos para el analisis
- Elminacion de valores negativos and useless columns
- Exploration of the correlation of data and outliers: Existe una gran relacion entre la edad y la experiencia
IMAGEN DEL HEAT MAP

- Analisis de la distribucion de los datos: Se encontro una gran cantidad de valores anormales en los ingresos
IMAGEN DE LOS HISTOGRAMAS Y BOXPLOT

## EDA
El analisis exploratorio de datos se hizo pensando en las preguntas objetivo. Se obtuvieron varias conclusiones las cuales seran presentadas a continuacion

- Distribucion de la educacion de los clientes: La mayoria de los clientes no son graduados pero parece que la educacion no tiene una relacion directa con los prestamos
IMAGEN
- Analisis del tipo de cuenta de los clientes: La gran mayoria de los clientes no cuentan con una cuenta de seguridad ni de credito, podria generar algunos activos extra si encontramos la manera de insentivarlos a buscar uno

- Prestamos en relacion con otros factores: Parece ser que el factor mas importante para un prestamo son los ingresos, esto no es ninguna sorpresa. Otro factor realmente inportante es la cantidad de familiares en la familia

## Conclusiones
- Los valores que mas influyen son los ingresos y el tamaño de la familia
- Los valores que menos influyen es la edad y experiencia 
- Es recomendable incentivar a los clientes a crear una cuenta de credito y un seguro
- Puede acceder al codigo en este enlace ENLACE
