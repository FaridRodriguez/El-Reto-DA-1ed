# El Reto DA - Primera edición
Este repositorio contiene información para el desarrollo del primer Reto DA.

## Reglas:
1.	Los participantes desarrollarán un modelo de predicción del ingreso per cápita de los hogares usando las variables de la Enaho 2017 tal que sea replicable con la información del Censo de Población y Vivienda del mismo año.
2.	La predicción será para la región de Lima y Callao (trataremos a estas dos regiones como una sola).
3.	La base está dispuesta en este repositorio junto con indicaciones adicionales en la [siguiente ruta](https://github.com/FaridRodriguez/El-Reto-DA-1ed/tree/master/Bases).
4.	La base tendrá el mismo set de variables para todos los participantes pero cada uno es libre de hacer su propia selección de variables o construcción de features a partir de dicho set.
5.	Cada participante realizará la predicción de manera independiente y subirá al GitHub la versión final de su modelo.
6.	Los pasos para la predicción deberán seguir los lineamientos de modelamiento vistos en la última hackaton (construcción de features, creación de bases training and testing, aplicación del modelo, cross-validation, resultados).
7.	El jurado utilizará como base de validación una muestra aleatoria con el 25% de observaciones (hogares) de la base original.
8.	El código será escrito en su totalidad en R (formato **.R**). El modelo final deberá ser guardado en formato **.rda** y subido a la carpeta del equipo respectivo en la [siguiente ruta](https://github.com/FaridRodriguez/El-Reto-DA-1ed/tree/master/Resultados).
9.	La evaluación se llevará a cabo en la Hackaton del 11 de Abril.

## El ganador es:
El equipo que obtenga un mejor resultado en la predicción sobre la base de prueba del jurado. En este caso, dado que variable a proyectar es  continua (ingreso per cápita) se usará como medida de precisión el error cuadrático medio sobre la base de prueba (*test MSE*); es decir, gana quien obtenga un menor *test MSE* durante la evaluación.

## Premio:
1/2 día libre y un **premio especial sorpresa**.

<br/>

### ¡Ánimos a todos!

<br/>

***
**PD:** Si tienes cualquier sugerencia, comentario o consulta, por favor crea un nuevo issue en el [siguiente link](https://github.com/FaridRodriguez/El-Reto-DA-1ed/issues) de manera que el resto de participantes y el jurado puedan ravisarlo y resolverlo lo más pronto posible.
