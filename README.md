# Práctica 6: Realidad Aumentada en Unity3D

Este proyecto implementa una aplicación básica de Realidad Aumentada utilizando **Unity** y el motor **Vuforia Engine**.

### Funcionamiento
La aplicación utiliza la webcam para detectar dos "Image Targets" distintos y renderizar un objeto 3D diferente sobre cada uno:

* **Objetivo 1 (Astronauta):** Al detectar la imagen, muestra un **Cubo**.
* **Objetivo 2 (Batman):** Al detectar la imagen, muestra una **Esfera**.

### Configuración Realizada
* Importación de la base de datos de objetivos (Target Database).
* Configuración de la **ARCamera** y clave de licencia de Vuforia.
* Asociación de los modelos 3D primitivos como hijos de cada *ImageTarget*.

### Requisitos
* Unity (con soporte Vuforia activado).
* Webcam funcional.