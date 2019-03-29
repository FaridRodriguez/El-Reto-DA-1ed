# El Reto DA - Primera edición
Este repositorio contiene la información necesaria para el desarrollo del primer Reto DA.

## Reglas:
1.	Los participantes realizarán un modelo de predicción del ingreso per cápita de los hogares usando las variables de la Enaho 2017 tal que sea replicable con la información del Censo de Población y Vivienda de dicho año.
2.	La predicción será para la región de Lima y Callao (trataremos a estas dos regiones como una sola).
3.	La base estará dispuesta en este repositorio junto con indicaciones adicionales.
4.	La base tendrá el mismo set e variables para todos los participantes pero cada uno es libre de hacer su propia selección de variables o construcción de features a partir de dicho set.
5.	Cada participante realizará la predicción de manera independiente y subirá al Git Hub la versión final de su modelo.
6.	Los pasos para la predicción deberán seguir los lineamientos de modelamiento vistos en la última hackaton (construcción de features, creación de bases training and testing, aplicación del modelo, cross-validation, resultados).
7.	El jurado utilizará como base de validación una muestra aleatoria con el 25% de observaciones (hogares) de la base original.
8.	El código será escrito en su totalidad en R.
9.	La presentación de los resultados será en la Hackaton del 11 de Abril.

## El ganador es:
El participante que obtenga un mejor resultado en la predicción sobre la base testing del jurado. En este caso, dado que variable a proyectar es aleatoria continua (el ingreso) se usará como medida de precisión el error cuadrático medio sobre la base de validación (test MSE); es decir, gana quien obtenga un menor test MSE durante la evaluación.

## Premio:
1/2 día libre y un premio especial sorpresa.

<br/>

### ¡Ánimos a todos!

<br/>

***
**PD:** Si tienes cualquier sugerencia, comentario o consulta, por favor crea un nuevo issue en el [siguiente link](https://github.com/FaridRodriguez/El-Reto-DA-1ed/issues) de manera que el resto de participantes y el jurado puedan ravisarlo y resolverlo lo más pronto posible.
