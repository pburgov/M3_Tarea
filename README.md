---
title: "MachineLearning.Rmd"
author: "Pedro Burgo Vázquez"
date: "24/11/2017"
output: html_document
---

SCRIPT: MachineLearning.Rmd

AUTHOR: Pedro Burgo Vázquez

DATE: 24/11/2017


### Descripción de la Práctica

Como Tarea del Módulo 3 del Master de Big Data de Telefónica, se realiza un Análisis explotatorio apoyado en algún método no supervisado para posteriormente llevar a cabo la construcción de al menos 2 modelos *machine learning* supervisados y comparar dichos modelos.
El dataset utilizado, es el que se puede encontran en la siguiente url:
https://archive.ics.uci.edu/ml/machine-learning-databases/00320/student.zip

El dataset contiene 2 archivos CSV, uno con datos de alumnos de portugués y otro con datos de alumnos de matemáticas, cada registro consta de los siguientes  atributos: <code>school,sex, age, address, famsize, Pstatus, Medu, Fedu, Mjob, Fjob, reason, guardian, traveltime, studytime, failures, schoolsup, famsup, paid, activities, nursery, higher, internet, romantic, famrel, freetime, goout, Dalc, Walc, health, absences. </code>

Como últimas tres variables de los *datasets* s eencuentran las notas de la materia del curso: <code>G1, G2 y G3 </code>, siendo está última la que se esocge como *target*
Las descripciones de estas variables, se  se pueden ver en archivo *student.txt*, alojado en el mismo archivo descargado.
La tarea consta de los siguientes puntos:
<ol>
<li> Introducción </li>
</ol>

## 2. Carga de los Datos y Análisis Descriptivo
### 2.1 Carga del dataset original
###2.2 Inspección Inicial de los datos
###2.3 Analizamos la distribución de algunas variables
###2.4 Matriz de correlación
###2.5 Análisis más detallado de algunas variables
##3. Análisis exploratorio apoyado en algún método NO Supervisado
##4. Construcción de 2 o más modelos de Machine Learning supervisados
###4.1 Selección de variables
###4.2 Construcción de modelos
##5. Comparación de modelos

