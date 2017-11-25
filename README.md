---
title: "MachineLearning.Rmd"
author: "Pedro Burgo Vázquez"
date: "24/11/2017"
output: html_document
---

SCRIPT: MachineLearning.Rmd

AUTHOR: Pedro Burgo Vázquez

DATE: 24/11/2017


DATA SOURCE: https://raw.githubusercontent.com/rdempsey/dataiku-posts/master/building-data-pipeline-data-science-studio/dss_dirty_data_example.csv


### Descripción de la Práctica

Como Tarea del Módulo 3 del Master de Big Data de Telefónica, vamos a realizar un Análisis explotatorio basado apoyado en algún método no supervisado para posteriormente llevar a cabo la construcción de al menos 2 modelos *machine learning* supervisados y comparar dichos modelos.
El dataset utilizado, es el que se puede encontran en la siguiente url:
https://archive.ics.uci.edu/ml/machine-learning-databases/00320/student.zip
El dataset contiene 2 archivos CSV, uno con datos de alumnos de portugués y otro con datos de alumnos de matemáticas, cada registro consta de los siguientes  atributos: <code>school,sex, age, address, famsize, Pstatus, Medu, Fedu, Mjob, Fjob, reason, guardian, traveltime, studytime, failures, schoolsup, famsup, paid, activities, nursery, higher, internet, romantic, famrel, freetime, goout, Dalc, Walc, health, absences. </code>
Como últimas tres variables de los *datasets* s eencuentran las notas de la materia del curso:G1, G2 y G3, siendo está última la que se esocge como *target*
Las descripciones de estas variables, se  se pueden ver en archivo *student.txt*, alojado en el mismo archivo descargado.

