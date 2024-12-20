# **Unsupervised Learning**

El aprendizaje no supervisado es una rama del aprendizaje automático utilizada principalmente para identificar patrones y agrupamientos en datos que no tienen etiquetas ni un objetivo definido (*target*). En lugar de predecir una salida específica, el aprendizaje no supervisado explora las relaciones entre los datos basándose en semejanzas o diferencias.

---

**Características Principales**
- Agrupa filas de un conjunto de datos (*dataset*) sin etiquetas.
- Identifica patrones ocultos o estructuras inherentes en los datos.
- No se aplica a problemas de regresión o clasificación debido a la ausencia de un *output* objetivo para los datos de entrada.

**Ventajas**
- Puede descubrir patrones desconocidos en los datos sin intervención humana.
- Útil para reducir dimensionalidad o preprocesar datos antes de aplicar modelos supervisados.
- Aplica técnicas avanzadas como *clustering* o análisis de asociaciones en grandes volúmenes de datos.

**Desventajas**
- Es intrínsecamente más difícil que el aprendizaje supervisado debido a la ausencia de etiquetas para validar el resultado.
- Los resultados pueden ser menos precisos porque los algoritmos no conocen el *output* exacto de antemano.
- Requiere experiencia para interpretar correctamente los resultados obtenidos.

---

## **Métodos Principales de Aprendizaje No Supervisado**

### **1. Clustering (Agrupamiento)**
El objetivo del *clustering* es agrupar datos en función de sus similitudes o diferencias. Los grupos (o clústeres) resultantes son internamente homogéneos, pero heterogéneos entre sí.

#### **Técnicas Comunes de Clustering**
1. [**K-Means Clustering**](data-science/004-modelado/k-means-clustering.md)
   Divide los datos en *k* clústeres predefinidos. Cada clúster se define en torno a un centroide, y los puntos se asignan al clúster con el centroide más cercano.
   
2. [**K-Nearest Neighbors (KNN)**](data-science/004-modelado/knn.md)
   Asigna puntos a clústeres en función de la proximidad a sus vecinos más cercanos. Aunque suele usarse para problemas supervisados, tiene aplicaciones no supervisadas.

3. [**Hierarchical Clustering**](data-science/004-modelado/hierarchical-clustering.md)
   - Asume que cada punto de datos es inicialmente un clúster individual.  
   - Agrupa puntos en función de su proximidad, formando una estructura jerárquica.  
   - Finaliza con todos los puntos agrupados en un solo clúster.

4. [**Anomaly Detection**](data-science/004-modelado/anomaly-detection.md)
   Identifica puntos de datos que no se ajustan al patrón general (anomalías).

5. [**Redes Neuronales (Autoencoders)**](data-science/004-modelado/autoencoders.md)
   Se utilizan para descubrir patrones latentes, especialmente en grandes conjuntos de datos.

6. [**Principal Component Analysis (PCA)**](data-science/004-modelado/pca.md)
   Reduce la dimensionalidad de los datos manteniendo la mayor varianza posible. Ideal para simplificar datos complejos.

7. [**Independent Component Analysis (ICA)**](data-science/004-modelado/ica.md)
   Separa datos en componentes independientes, útil en señales como audio o imágenes.

8. [**Apriori Algorithm**](data-science/004-modelado/apriori-algorithm.md)
   Identifica relaciones frecuentes entre elementos en un conjunto de datos, comúnmente usado en análisis de asociaciones.

9. [**Singular Value Decomposition (SVD)**](data-science/004-modelado/svd.md)
   Descompone matrices de datos en componentes fundamentales para reducir dimensionalidad.

---

### **2. Association (Asociación)**
Busca descubrir reglas que relacionen elementos dentro de un conjunto de datos. Este enfoque es especialmente útil en estrategias de marketing y análisis de transacciones.

#### **Ejemplo Común: Análisis de Cesta de Compras**  
- Si un cliente compra pan, es probable que también compre mantequilla o mermelada.
- Identifica patrones frecuentes que pueden optimizar la toma de decisiones estratégicas.

---

### **Resumen**
El aprendizaje no supervisado es esencial para descubrir patrones y estructuras en datos sin etiquetas. Sus métodos principales, *clustering* y asociación, ofrecen herramientas versátiles para resolver problemas complejos, como segmentación de clientes, detección de anomalías, o reducción de dimensionalidad. Aunque presenta desafíos inherentes, sus aplicaciones abarcan desde análisis de datos exploratorio hasta soporte en la toma de decisiones estratégicas.