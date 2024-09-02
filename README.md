### 2. Reconocimiento de Objetos en Imágenes
- **Descripción**: Desarrollé un modelo CNN/DL para el reconocimiento de artículos de supermercado en imágenes. El dataset fue etiquetado utilizando makesense.ai, y trabajé con técnicas de EDA, ajuste fino y aumento de datos.
- **Objetivo**: Crear un sistema eficiente de reconocimiento de objetos que pudiera identificar con precisión diversas clases de artículos en imágenes de supermercado.
- **Proceso**:
  - Creación de un dataset con al menos 12 clases etiquetadas.
  - Implementación de preprocesamiento con one hot encoding y técnicas de aumento de datos.
  - Utilización de modelos preentrenados como MobileNetV2, DenseNet169, VGG19, InceptionV3 y ResNet50 con pesos de ImageNet.
  - Ajuste de hiperparámetros para optimizar el rendimiento del modelo.
- **Resultados**:
  - **MobileNetV2** fue el mejor modelo, con un **97% de val accuracy**, **10% de val loss** y un **F1-score de 97%**. 
  - MobileNetV2 demostró un buen equilibrio entre precisión y exhaustividad, logrando excelentes resultados gracias al ajuste fino y a la arquitectura eficiente de capas densas que facilita el aprendizaje de patrones complejos.

![Accuracy MobileNetV2](./accuracy%20mobilenetv2.PNG)
