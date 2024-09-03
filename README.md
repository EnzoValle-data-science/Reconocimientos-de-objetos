# Reconocimiento de Objetos en Imágenes de Supermercado

## Descripción
Este proyecto tiene como objetivo desarrollar un sistema de reconocimiento de objetos en imágenes de productos de supermercado. Utilizando técnicas de Deep Learning y redes neuronales convolucionales (CNN), se entrenaron modelos para identificar y clasificar al menos 12 clases de productos dentro del supermercado. Se utilizaron modelos preentrenados como MobileNetV2, DenseNet169 y ResNet50.

## Objetivo General:
Desarrollar un modelo de reconocimiento de objetos que permita identificar productos de supermercado en imágenes, utilizando redes neuronales convolucionales y técnicas avanzadas de Machine Learning.

## Objetivos Específicos:
1. Crear y etiquetar un dataset personalizado con imágenes de productos de supermercado.
2. Implementar técnicas de preprocesamiento y aumento de datos para mejorar la calidad del entrenamiento del modelo.
3. Ajustar y entrenar modelos preentrenados, aplicando técnicas de transfer learning, para obtener los mejores resultados en precisión y rendimiento.
4. Evaluar el rendimiento de los modelos entrenados utilizando métricas como accuracy, loss, y F1-score.

## Proceso:
1. **Creación del dataset**: Se generó un dataset con más de 12 clases de productos de supermercado, utilizando makesense.ai para el etiquetado de las imágenes.
2. **Preprocesamiento de datos**: Se aplicaron técnicas de aumento de datos (data augmentation) para mejorar la generalización del modelo y se empleó One-Hot Encoding para las etiquetas.
3. **Entrenamiento de modelos**: Se utilizaron modelos preentrenados como MobileNetV2, DenseNet169 y ResNet50, ajustando hiperparámetros y aplicando transfer learning.
4. **Evaluación**: MobileNetV2 fue el mejor modelo, obteniendo un equilibrio óptimo entre precisión y eficiencia en la clasificación de objetos.

## Resultados:
- **Mejor Modelo**: MobileNetV2, con un val accuracy del 97%, val loss del 10% y un F1-score de 97%.
  
| **Gráfico Accuracy MobileNetV2**        | **Matriz de Confusión MobileNetV2**   |
|-----------------------------------------|---------------------------------------|
| ![Accuracy MobileNetV2](./accuracy%20mobilenetv2.PNG) | ![Matriz de Confusión MobileNetV2](./matriz%20de%20confusion%20mobilenetv2.PNG) |

| **Resultados MobileNetV2**              |
|-----------------------------------------|
| ![Resultados MobileNetV2](./resultados%20mobilenetv2.PNG) |


## Duración del proyecto
El proyecto fue completado en el transcurso de tres semanas. La dedicación de horas-hombre varió según mi disponibilidad a lo largo de este período.
