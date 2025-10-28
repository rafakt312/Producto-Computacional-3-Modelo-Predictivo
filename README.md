# Producto Computacional 3: Modelamiento Predictivo con Datos MHEALTH

## Objetivo General

Aplicar técnicas de Machine Learning o Deep Learning para construir y validar modelos capaces de reconocer actividades humanas a partir de los sensores del dataset MHEALTH, evaluando su desempeño mediante métricas apropiadas.

## Contexto

En las etapas anteriores exploraste, limpiaste y visualizaste los datos del conjunto MHEALTH Dataset, comprendiendo la estructura temporal y las variables asociadas a distintas actividades físicas. En esta etapa, tu misión es entrenar modelos predictivos supervisados para clasificar las actividades.

## Requerimientos del Proyecto

### 1. Preparación de los datos
- Seleccionar un subconjunto de variables o realizar ingeniería de características si es necesario.
- Dividir los datos en entrenamiento (70%) y validación/prueba (30%), manteniendo la representativad de las clases.
- Aplicar técnicas de normalización o estandarización según corresponda.

### 2. Construcción de modelos
Deberás implementar al menos **dos modelos** de aprendizaje supervisado. Puedes elegir entre:

* **Machine Learning clásico:** K-Nearest Neighbors (KNN), Support Vector Machine (SVM), Decision Tree / Random Forest, Logistic Regression, XGBoost o LightGBM.
* **Deep Learning:** Red Neuronal Densa (MLP), CNN o LSTM (para series temporales).

### 3. Validación
- Utilizar validación cruzada (k-fold) o train/test split.
- Reportar matriz de confusión y métricas como:
    * Accuracy
    * Precision
    * Recall
    * F1-score

### 4. Visualización de resultados
- Graficar curvas de aprendizaje.
- Mostrar la matriz de confusión como mapa de calor.
- Comparar modelos en una tabla resumen de métricas.

### 5. Interpretación
- Analizar cuál modelo tuvo mejor desempeño y por qué.
- Discutir posibles fuentes de error y oportunidades de mejora.

## Entrega Esperada

Un notebook en Python (Jupyter o Google Colab) que contenga:

1.  Carga y preprocesamiento de los datos.
2.  Entrenamiento y evaluación de al menos dos modelos.
3.  Visualizaciones de resultados y discusión.
4.  Conclusiones claras sobre el desempeño comparativo.
