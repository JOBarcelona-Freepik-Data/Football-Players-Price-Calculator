# Football-Players-Price-Calculator

Entrega para la final de la hackathon JOBarcelona22 por parte del equipo de Data Science de Freepik.

## Desafío
No ha sido desapercibido que el contexto actual es muy delicado en el mundo del fútbol. La
audiencia y la falta de un 2020 sin la venta de entradas ha hecho que muchos clubes
tengan una postura económica muy delicada. Para ello se nos encomienda una tarea de
suma responsabilidad, crear un sistema que permita asignar precios a jugadores de forma
objetiva, evitando la especulación. El objetivo es poder predecir los precios de los futbolistas de una manera precisa.

## Exploración de datos
La exploración inicial de los datos se encuentra en el fichero "EDA.ipynb"

## Solucion
El modelo final se encuentra en el fichero "FinalSolution.ipynb". Hemos realizado un preprocesado de los datos filtrando los outliers y sacando variables poco importantes. Las variables categóricas las hemos codificado usando Target Encoding. Hemos usado un modelo CatBoosting para la regresión.
