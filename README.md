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
Para el desarrollo del modelo, se eligió la plataforma Detectron2, que es reconocida por su eficacia en tareas de detección y segmentación de objetos. Esta herramienta facilitó el reconocimiento preciso de los tomates, permitiendo su posterior etiquetado en tres categorías: "Inmaduros", "Semi-maduros" y "Maduros".

En el proceso de entrenamiento, se decidió emplear un total de 2700 épocas, junto con una tasa de aprendizaje de 0.001. Estos parámetros fueron seleccionados tras realizar múltiples pruebas, y se observó que proporcionaron los mejores resultados en términos de precisión y eficiencia en la clasificación de los tomates. Este enfoque permitió optimizar el rendimiento del modelo y mejorar la calidad de las predicciones.

## Referencias

[1] Tsironis V., Bourou S., Stentoumis C. (2020). tomatOD: Evaluation of object detection algorithms on a new real-world tomato dataset. In ISPRS - International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences. Available from https://github.com/up2metric/tomatOD 

[2] Tomato Dataset. (2024). Roboflow Universe. Available from https://universe.roboflow.com/project-qmlqn/tomato-sex1q
