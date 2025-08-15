# Análisis y comparación de modelos para la predicción de patologías a partir de radiografías

En este repositorio se encuentran distintas notebooks y scripts relacionados con el procesamiento y entrenamiento de modelos para el análisis de radiografías.

## 1. `EDA.ipynb`
En esta notebook se realiza un análisis exploratorio del dataset de radiografías:
- Estudio de la estructura del dataset.
- Aplicación de técnicas de *data augmentation*.
- Balanceo de clases para mejorar la distribución de datos.
- Exportación de los datasets procesados en formato `.pt` para su uso en entrenamiento.

## 2. `Baseline.ipynb`
En esta notebook se lleva a cabo:
- Selección de un modelo base: **ResNet18** (preentrenado sobre *ImageNet*).
- Entrenamiento del modelo y evaluación de métricas: *accuracy*, *loss*, *recall* y *F1-score*.
- Presentación de conclusiones.

## 3. `Benchmark_models.ipynb`
En esta notebook se realiza lo siguiente:
- Selección de modelos adicionales (todos preentrenados sobre *ImageNet*).
- Comparación de resultados con el baseline.
- Evaluación con diferentes *learning rates*.
- Descongelado de distintos números de capas para analizar el impacto en la performance.
- Comparación de métricas a nivel de entrenamiento (*accuracy* y *loss*) y en test (*recall*, *F1-score* y la métrica presentada).  
- Presentación de conclusiones y comparaciones finales.

---

## Presentación Final
[Enlace a la presentación (en proceso)](https://docs.google.com/presentation/d/1GWRU1OKkmZsF65p9SG8CCbN_5kFRfw7LJa9zsj6W8Gg/edit?slide=id.p#slide=id.p)



