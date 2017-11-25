---
title: "Modelo Machine Learning"
author: "Pedro Burgo"
date: "24 de noviembre de 2017"
output:
  html_document:
    highlight: tango
    theme: cerulean

---

SCRIPT: MachineLearning.Rmd

AUTHOR: Pedro Burgo Vázquez

DATE: 24/11/2017

<style type="text/css">
OL { counter-reset: item }
LI { display: block }
LI:before { content: counters(item, ".") " "; counter-increment: item }
</style>
### Descripción de la Práctica

Como Tarea del Módulo 3 del Master de Big Data de Telefónica, se realiza un Análisis explotatorio apoyado en algún método no supervisado para posteriormente llevar a cabo la construcción de al menos 2 modelos *machine learning* supervisados y comparar dichos modelos.
El dataset utilizado, es el que se puede encontran en la siguiente url:
https://archive.ics.uci.edu/ml/machine-learning-databases/00320/student.zip

El dataset contiene 2 archivos CSV, uno con datos de alumnos de portugués y otro con datos de alumnos de matemáticas, cada registro consta de los siguientes  atributos: <code>school,sex, age, address, famsize, Pstatus, Medu, Fedu, Mjob, Fjob, reason, guardian, traveltime, studytime, failures, schoolsup, famsup, paid, activities, nursery, higher, internet, romantic, famrel, freetime, goout, Dalc, Walc, health, absences. </code>

Como últimas tres variables de los *datasets* s eencuentran las notas de la materia del curso: <code>G1, G2 y G3 </code>, siendo está última la que se escoge como *target*
Las descripciones de estas variables, se  se pueden ver en archivo *student.txt*, alojado en el mismo archivo descargado.
La tarea consta de los siguientes puntos:

<ol type="1">
<li> Introducción </li>
<li> Carga de los Datos y Análisis Descriptivo
<ol type="1">
<li> Carga del dataset original</li>
<li> Inspección Inicial de los datos</li>
<li> Analizamos la distribución de algunas variables</li>
<li> Matriz de correlación</li>
<li> Análisis más detallado de algunas variables</li>
</ol>
</li>
<li>Análisis exploratorio apoyado en algún método NO Supervisado</li>
<li> Construcción de 2 o más modelos de Machine Learning supervisados
<ol type="1">
<li> Selección de variables</li>
<li> Construcción de modelos</li>
</ol>
</li>
<li> Comparación de modelos</li>
</ol>

El resultado se puede ver en [Rpubs](http://rpubs.com/pburgov/M3_Tarea),los archivos se encuentran en [GitHUB](https://github.com/pburgov/M3_Tarea)