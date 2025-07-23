# Alura Challenge 2

Este proyecto corresponde al segundo challenge de Alura Latam, enfocado en el análisis y predicción del churn de clientes (abandono) mediante técnicas de machine learning.

## Objetivo
Predecir si un cliente abandonará el servicio o no, priorizando la métrica recall para minimizar los falsos negativos (clientes que se van y no son detectados por el modelo).

## Herramientas utilizadas
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## Proceso del proyecto
1. Carga y exploración de datos
2. Limpieza y tratamiento de valores nulos
3. Codificación y normalización de variables
4. Balanceo con SMOTE (oversampling)
5. Entrenamiento del modelo KNN
6. Evaluación con métricas de clasificación
7. Análisis de importancia de variables

## Resultado
El modelo final logró un recall del 76% sobre los datos de prueba, destacando su capacidad para identificar correctamente a los clientes que abandonan.

## Conclusión
El modelo entrenado permitió identificar variables clave que influyen en el abandono del cliente, como tenure, facturación, género masculino, entre otras, lo cual puede ser usado por el negocio para tomar decisiones preventivas.
