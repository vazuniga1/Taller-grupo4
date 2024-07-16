# Repositorio de Grupo 4 - Taller de Proyectos Tecnologicos EL6101-4

## Tema: Reconocimiento de maduración de fruta mediante el procesamiento de imágenes.

## Integrantes: Diego Bartolucci, Carlos Faundez y Valentina Zúñiga

Implementar un programa de reconocimiento de la maduración de la fruta para cosecha optima, lo cual puede llegar a ser implementado en:

* Sector industrial
* Aplicación móvil 

## Datasets

Se combinan dos datasets ([1], [2]), por lo que el dataset se conforma por un total de 640 imagenes de cultivos, las que contienen 2418 imagenes de tomate. Luego se realiza la siguiente división:

* Conjunto de entrenamiento (75%): Abarca 476 imagenes, obteniendo 6879 tomates en total. Esto tiene 4619 de tomates inmaduros, 1059 semi-maduros y 1201 maduros.
* Conjunto de validación (9%): Abarca 55 imágenes, teniendo 466 tomates en total.
* Conjunto de test (16%): Abarca 109 imágenes, sin embargo, este conjunto no es utilizado ya que se realizan pruebas sobre imagenes propias. 

## Modelo

## Referencias

[1] Tsironis V., Bourou S., Stentoumis C. (2020). tomatOD: Evaluation of object detection algorithms on a new real-world tomato dataset. In ISPRS - International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences. Available from https://github.com/up2metric/tomatOD 

[2] Tomato Dataset. (2024). Roboflow Universe. Available from https://universe.roboflow.com/project-qmlqn/tomato-sex1q