# 4. Modelado con Machine Learning
Esta etapa se encuentra en el núcleo del Proceso de Ciencia de Datos y se inicia una vez que los datos han sido preparados y están listos para análisis. El modelado con Machine Learning (ML) incluye una serie de pasos diseñados para crear, evaluar y optimizar modelos que puedan extraer patrones útiles y hacer predicciones o clasificaciones precisas. A continuación, se detalla el proceso dentro de esta etapa.

Proceso del Modelado con Machine Learning


## 1. Definición del Problema
- Objetivo: Establecer claramente el tipo de problema que se abordará con ML (por ejemplo, clasificación, regresión, clustering, etc.).
- Acciones clave:
    - Determinar si el problema es supervisado (etiquetas conocidas) o no supervisado (sin etiquetas).
    - Identificar las métricas de evaluación relevantes (precisión, recall, F1-score, MAE, RMSE, etc.).
    - Establecer los límites de desempeño deseado basados en las necesidades del negocio.

 
## 2. Selección del Modelo
- Objetivo: Escoger un algoritmo de ML adecuado para el tipo de problema y los datos disponibles.
- Modelos existentes:
    - [Supervised Learning](data-science/004-modelado/supervised-learning.md)
    - [Unsupervised Learning](data-science/004-modelado/unsupervised-learning.md)
- Acciones clave:
    - Revisar los algoritmos disponibles, como:
        - Clasificación: Regresión logística, árboles de decisión, SVM, redes neuronales, etc.
        - Regresión: Regresión lineal, árboles de decisión, gradient boosting, etc.
        - Clustering: K-means, DBSCAN, etc.
        - Reducción de Dimensionalidad: PCA, t-SNE.
        - Considerar el tamaño del dataset, el balance de clases, la complejidad del modelo y las limitaciones computacionales.
- Resultado esperado: Una lista inicial de modelos candidatos.


## 3. División del Conjunto de Datos
- Objetivo: Crear conjuntos de datos para entrenamiento, validación y prueba, asegurando un análisis objetivo.
- Acciones clave:
    - Dividir los datos en proporciones comunes, como 70% entrenamiento, 15% validación y 15% prueba.
    - Si los datos están desbalanceados, emplear técnicas como sobremuestreo (oversampling) o submuestreo (undersampling).
- Resultado esperado: Conjuntos de datos correctamente particionados.


## 4. Entrenamiento del Modelo
- Objetivo: Ajustar los parámetros del modelo a los datos de entrenamiento para que aprenda patrones significativos.
- Acciones clave:
    - Aplicar técnicas como validación cruzada para mejorar la robustez del modelo.
    - Optimizar el rendimiento en el conjunto de entrenamiento sin sobreajustar (overfitting).
- Resultado esperado: Un modelo ajustado inicial.


## 5. Optimización de Hiperparámetros
- Objetivo: Mejorar el rendimiento ajustando los hiperparámetros del modelo.
- Acciones clave:
    - Usar enfoques como búsqueda en cuadrícula (grid search) o búsqueda aleatoria (random search).
    - Aplicar técnicas modernas como optimización bayesiana o algoritmos genéticos.
- Resultado esperado: Un modelo con hiperparámetros optimizados.


## 6. Evaluación del Modelo
- Objetivo: Validar el desempeño del modelo en el conjunto de prueba para asegurar generalización.
- Acciones clave:
    - Evaluar métricas clave específicas al problema:
        - Clasificación: Precisión, recall, F1-score, curva ROC-AUC.
        - Regresión: Error cuadrático medio (MSE), error absoluto medio (MAE), R².
        - Clustering: Índice de Silueta, coeficiente de correlación.
    - Realizar análisis de error para identificar debilidades del modelo.
- Resultado esperado: Un informe detallado sobre el rendimiento del modelo.


## 7. Interpretación del Modelo
- Objetivo: Asegurarse de que el modelo y sus predicciones sean comprensibles para los stakeholders.
- Acciones clave:
    - Aplicar técnicas de interpretabilidad como SHAP (Shapley Additive Explanations) o LIME (Local Interpretable Model-Agnostic Explanations).
    - Comunicar hallazgos de forma clara y visual.
- Resultado esperado: Una interpretación sólida del modelo y sus decisiones.


## 8. Selección del Modelo Final
- Objetivo: Escoger el modelo que mejor cumpla con los requisitos del negocio y los criterios técnicos.
- Acciones clave:
    - Comparar el rendimiento de los modelos candidatos.
    - Balancear el rendimiento técnico con la simplicidad y escalabilidad.
- Resultado esperado: Un modelo final listo para ser implementado.

## Resumen de la Etapa
El modelado con Machine Learning es un proceso iterativo que combina teoría, experimentación y optimización. Una vez que el modelo final es seleccionado, este se valida extensivamente para asegurar que sea adecuado para la etapa de Despliegue.