# Deteccion Lenguaje Ofensivo Python

Sistema de detección de ofensividad que reciba como entrada un texto y que devuelva como salida la clase que el sistema haya obtenido de acuerdo a una escala basada en dos valores: ofensivo y no ofensivo.

- [Deteccion Lenguaje Ofensivo Python](#deteccion-lenguaje-ofensivo-python)
  - [Introducción](#introducción)
  - [Tecnologías utilizadas](#tecnologías-utilizadas)
  - [Manual de utilización del sistema](#manual-de-utilización-del-sistema)
  - [Resultados obtenidos](#resultados-obtenidos)

## Introducción

Se ha desarrollado un sistema de detección de lenguaje ofensivo en redes sociales basado en aprendizaje supervisado utilizando la técnica de clasificación, con el objetivo de establecer una relación entre los datos a predecir y los grupos predefinidos. En nuestro caso definiremos 2 grupos para los comentarios:

1. **“OFF”**: Grupo que representa a los comentarios ofensivos.
2. **“NON”**: Grupo que representa a los comentarios no ofensivos.
Para realizar el sistema se ha partido de un corpus con comentarios clasificados(OffendES) para poder entrenar el modelo.

## Tecnologías utilizadas

- Python

## Manual de utilización del sistema

## Resultados obtenidos

El script scorer.py evaluará los resultados según las métricas:

- **Precisión**:Con la métrica de precisión podemos medir la calidad del modelo de machine learning en tareas de clasificación.
- **Recall**: La métrica de exhaustividad nos va a informar sobre la cantidad que el modelo de machine learning es capaz de identificar.
- **F1_SCORE**: El valor F1 se utiliza para combinar las medidas de precisión y recall en un sólo valor. Esto es práctico porque hace más fácil el poder comparar el rendimiento combinado de la precisión y la exhaustividad entre varias soluciones.

|  | Sin Lexicón | Con Lexicón |
| ------------- | ------------- | ------------- |
| maf  |   | |
| map  |   | |
| mar  |   | |
| mif  |   | |
| mip  |   | |
| mir  |   | |
| avgf  |   | |
| avgp  |   | |
| avgr  |   | |
