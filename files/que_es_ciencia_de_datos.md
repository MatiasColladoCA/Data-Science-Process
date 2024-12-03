# Introducción

## Necesidad de Data Science

Producimos 2.5 quintillones de datos por día.

La ciencia de datos es un proceso útil que analiza y extrae información importante de los datos.

Las etapas de learn/optimize y aggregate/label son fundamentales en la industria.

En una **startup**, al carecer de recursos, se tendría tal vez un solo Data Scientist encargado de todas las tareas de:

- Learn/optimize
- Aggregate/label
- Explore
- Move
- Collect

Configuraremos toda la infraestructura de datos y hasta escribiremos el código.

Para **medianas empresas** con mas recursos, podemos separar Data Engineer y Data Science. La etapa de recolección de datos estaría en manos del Software Engineer, la parte de Explore/Transform y Move/Store a cargo del Data Engineer. Finalmente el Data Scientist estaría a cargo de:

- Learn/optimize
- Aggregate/label

Incluyendo las etapas con IA y Deep Learning, lo que requiere un conocimiento técnico mas avanzados como los que presentan personas con doctorados o maestrías.

Para **compañías grandes, l**a etapa de recolección de datos estaría en manos del Software Engineer, la parte de Explore/Transform y Move/Store a cargo del Data Engineer. Finalmente el Data Science Analytics estaría a cargo de:

- Learn/optimize
- Aggregate/label

Donde las etapas con IA y Deep Learning estarían a cargo del Research Scientist/Data Science Core respaldados por los Machine Learning Engineer.

## Conceptos relacionados

LoRA: forma adaptativa de rankear con pocos parámetros el entrenamiento de un modelo de lenguaje.

Base de datos vectorial: agarramos muchos datos y los volvemos números de proximidad para que los datos de la compañía puedan interpretarse dentro de un modelo de lenguaje.

RaG: otra técnica para insertar datos privados dentro de un modelo de lenguaje.

LLM: Large Language Model. Son parte de la IA, no la IA en sí.

## Diferencias y roles de un Data Scientist

La ciencia de datos, el análisis de datos y la ingeniería de datos son tres roles distintos dentro del ámbito del Big Data, pero están estrechamente relacionados y a menudo se superponen.

- Data Scientist: se encarga de diseñar y construir nuevos procesos para el análisis de datos, modelar los datos y crear algoritmos para extraer información útil o conocimientos a partir de esos datos. Deben entender el desafío del negocio ofreciendo la mejor solución usando el procesamiento y analisis de datos. Deben ser capaces de desempeñar análisis predictivos a partir de identificar tendencias y patrones para mejorar la toma de decisiones. (es laboralmente preferible tener un grado en matemáticas o ingeniería de la computación.
- Data Analyst. examina los grandes conjuntos de datos para detectar tendencias, desarrollar gráficos y crear representaciones visuales de los datos, además de buscar formas de utilizar esos datos para ayudar a la empresa a entender cómo mejorar sus operaciones. Es responsable de visualización, procesamiento de una cantidad masiva de datos y optimización y debe ser capaz de realizar consultas en bases de datos. Por medio de la optimización crean y modifican algoritmos que pueden ser usados para extraer información de las DB sin corromper los datos. Se deben manejar tecnologías como SQL, SAS y Python. Se requiere una buena capacidad de resolución de problemas.
- Data Architect: crea los planos para la gestión de los datos permitiendo que la DB sea fácilmente integrable centralizada y protegida con las mejores medidas de seguridad.
- Data Engineer: construye y testea ecosistemas de big data escalables. Se centra en la arquitectura de los datos, construyendo sistemas que permitan a los analistas y científicos de datos hacer su trabajo. Poseen las mejores herramientas y sistemas con los que trabajar. Es requerida experiencia en almacenamiento de Datos, modelación, extracción, transformacción y carga. Un ingeniero de datos maneja tecnologías como Hadoop, SQL, Python, SAS, PostgreSQL, MongoDB, Hive(?), noSQL, R, Ruby, Java, C++, Matlab, APIs, herramientas ETL y sistemas de almacenamiento de datos. Son responsables de mejorar la eficiencia de la base de datos.
- Estadístico: Requiere conocimientos de teorías estadísticas y organización de datos. Extraen insights valiosos y crean nuevas metodologías para que los ingenieros apliquen. Se requiere lógica, SQL Data Mining, Tecnologias de ML y conocimiento de conceptos de ML.
- Administrador de Base de Datos: Responsables del funcionamiento apropiado de todas las bases de datos. Responsables del acceso y backup de las DB. Se requiere conocimiento de backups, recuperación, seguridad, diseño y modelado de datos.
- Business Analyst: Se centran en como los datos se pueden conectar a insights de negocio accionables. Se centran en el crecimiento del negocio. Son una conexión entre el Data Engineer y los ejecutivos de gestión (managements Executives). Se requiere conocimiento en finanzas de negocio, Business-Intelligence, modelado de daots, herramientas de visualización de datos, etc.
- Gerente de Datos y Análisis: Responsable de las operaciones de ciencia de datos. Su principal ocupación es supervisar las operaciones de ciencia de datos. Asigna deberes  según habilidades y experiencia. Se requiere conocimiento de SAS, SQL, y habilidades de gestión o gerencia. Habilidades sociales, cuaidades de liderazgo y capacidad para pensar fuera de la caja. Conocimiento de las tecnologias implicadas (java, Python, etc).

En cuanto a cómo se relacionan cronológicamente, generalmente, la ingeniería de datos se realiza primero para establecer la infraestructura y los sistemas de datos. Una vez que estos sistemas están en su lugar, los científicos y analistas de datos pueden realizar su trabajo para analizar los datos y extraer información útil.

# Data Science

## Definición

Data Science consiste en usar datos para hacer el mayor impacto posible en nuestra compañía en forma de *insights*, *data products* o *product recomendations.* Para el *Journal of Data Science*, “se trata de todo lo que tiene que ver con datos: recolectar, analizar, modelar. Sin embargo, lo mas importante son sus aplicaciones”. No se trata sobre que tan avanzado es un modelo sino sobre el impacto que puede generar nuestro trabajo, consistente en resolver un problema dificil y hasta ambiguo, ser un estratega.

El Data Science dice que hacer con el producto. Los *analytics* permiten saber los *insights*, las *metrics* permiten conocer lo que pasa con el producto (exito o perdida); *A/B testing y experimentation* permiten conocer las mejores versiones de un producto.

Tambien se puede definir como el proceso de extraer conocimiento y insights de datos usando métodos científicos (programación+estadística+negocios)

Un Data Scientist es una persona capaz de ver los datos a través de unos lentes cuantitativos. Para eso requiere **matemáticas** (para los modelos predictivos basados en matemáticas), buen manejo de **tecnología** y **negocios** (siendo el científico de datos un consultor de negocios táctico).

## Habilidades

- Estadística: distribuciones, estimadores de máxima verosimilitud, teoría de probabilidad, estadística descriptiva, entre otros.
- Lenguajes de programación: Python, R, SAS, SQL, PostgreSQL, Matlab, etc.
- Datos: extracción y procesamiento y herramientas como mySQL, MongoDB, almacenando los datos en una estructura y formatos apropiados.
- Manipulación de datos: limpiar los datos, lidiar con valores faltantes, formatos inconsistentes, etc. Es la tarea que mas tiempo consume.
- Exploración de datos: buscamos el sentido de los datos buscando patrones, tendencias, outliers y resultados inesperados.
- Machine Learning: para compañías grandes, compañías data driven o grandes set de datos. No se puede procesar tantos datos con métodos tradicionales por lo que se necesitan algoritmos de ML como KNN, Random Forest, K-Mean, etc.
- Big Data processing frameworks: los datos generados a tratar y explorar pueden ser estructurados o no estructurados. En las cantidades de datos manejadas no podemos usar sistemas de procesamiento tradicionales. Para esto se usan frameworks como Hadoop y Spark para manipular big data.
- Data Visualization: Es importante presentar los datos y el conocimiento extraido de manera entendible y visualmente atractivo. Se usan tecnologías como Tableau, PowerBI, Matplotlib, Seaborn y QlikView.
- Enfoque de resolución de problemas tipo data-driven y creatividad.

También (encontrado fuera del curso que resumo acá)

- Entornos de trabajo
- Git y Github
- Terminal Linux y Linea de Comandos
- *~~Matemáticas~~*
- *~~Bases de datos SQL y PostgreSQL~~*
- *~~Visualización de datos con Matplotlib y Seaborn~~*
- *~~Análisis y manipulación de datos con Python~~*
- Habilidades blandas (para cualquier ámbito laboral)
- Visualización de datos para Business Intelligence (data science y data analist para empresas)

## Ciclo de vida de los datos

1. Requisitos de negocio: Entender el problema, identificar objetivos centrales, identificar variables a predecir
2. Adquisición de datos: ¿Qué datos necesito para el proyecto? ¿Cuáles son las fuentes de datos? ¿Cómo puedo obtener los datos? ¿Cuál es la forma mas eficiente de almacenar y acceder a los datos?
3. Procesamiento de datos: transformarlos a un formato deseado.
    
    Limpieza de datos:
    
    - Valores faltantes
    - Datos corruptos
    - Remover los datos innecesarios
4. Exploración de datos: Entender los patrones de los datos, recuperar ideas útiles, formar hipótesis. El brainstorming del análisis de datos Se pueden usar histogramas, color visualizaciones/turn interactivas, etc. Exploramos los distintos modelos aplicables a nuestros datos.
5. Modelado: Determinar características óptimas de datos para el modelo de ML. Crear un modelo que prediga el objetivo mas precisamente. Evaluar y testear la eficiencia del modelo. 
6. Despliegue: Verificar el entorno de despliegue para problemas de dependencia. Desplegar el modelo en un entorno de preproducción/prueba (test). Nosotros evaluamos y el usuario valida el desempeño del modelo. Los problemas del modelo deben repararse en esta etapa.

## Proceso de Data Science

1. Entender el problema de negocio
    
    Se acuerda una entrevista con el cliente al que se le harán preguntas relevantes.
    
2. Adquisición de Datos
    
    Se obtendrán datos desde multiples fuentes como Web Servers, Logs, Databases, API’s, Online Repositories.
    
3. Preparación de los datos
    
    Limpieza (datos inconsistentes, atributos mal escritos, valores perdidos o duplicados) y transformación de los datos (definiendo mapping rules entendiendo mejor la estructura de datos)
    
4. Analisis exploratorio de datos *(el paso mas importante)*
    
    Se define y refina la selección de variables de características que se utilizarán en el desarrollo del modelo.
    
5. Modelación de datos
    
    Se aplican algoritmos como KNN, Naive Bayes, Decision Trees, etc a los datos para identificar el modelo que mejor se ajusta a los requerimientos del negocio. *(Se utiliza Python, R y/o SAS)*
    
6. Visualización y comunicación
    
    Se reencuentra con el cliente para comunicar los hallazgos de negocio de una manera simple y efectiva para convencer los stakeholders *(Se usa tableau, Power BI, QlikView creando reportes poderosos y dashboards)*
    
7. Deploys y mantenimiento del modelo
    
    Se testea el modelo en un entorno preproducido y luego en un entorno de producción. Una ves  desplegado el modelo, se usan reportes y dashboards para obtener analíticas en tiempo real. También se monitorea y mantiene el desempeño del modelo
    

## Proceso de Data Science aplicado a un caso de Machine Learning

1. Un problema de Data Science empieza con una pregunta bien definida *(e. ¿Cual es la probabilidad de que esta transacción sea falsa?)*
2. Analizamos datos *(e. Transacciones anteriores etiquetadas como “fraudulentas” o “validas”)*
3. Un nuevo set de datos en el cual usar nuestro algoritmo *(e. nuevas transacciones de tarjetas de crédito)*

## Estadística y Probabilidad

Contenidos

1. ¿Qué son los datos?
2. Categorías de los datos
3. ¿Qué es la estadística?
4. Terminología básica en estadística.
5. Técnicas de Sampling/muestreo
6. Tipos de estadística
7. Estadística Descriptiva
8. Probabilidad
9. Estadística Inferencial

### ¿Qué son los datos?

Pueden ser un conjunto de números, un documento.

Los datos se refieren a hechos y estadísticas recopilados conjuntamente para referencia o análisis.

Un **dato** es una pieza cruda, sin procesar y descontextualizada de información, como un simple hecho o número. No tiene significado en sí mismo hasta que se procesa y se coloca en un contexto.

Por otro lado, la **información** es un conjunto de datos que se han procesado de tal manera que tienen un significado y valor para quien los recibe. La información proporciona contexto, interpretación, comprensión y, por lo general, tiene un propósito o relevancia.

En resumen, los datos son la materia prima, mientras que la información es el resultado del procesamiento de estos datos.

Los datos pueden ser recolectados, almacenados, medidos, analizados y visualizados mediante modelo estadísticos

Categorías:

Cualitativa: características y descriptores no medibles fácilmente pero pueden observarse subjetivamente

Ordinal: Serie ordenada. *(posiciones en una carrera)*

Nominal: sin orden inherente o rango. Ejemplo *(sexo, edad)*

Cuantitativa: Lidia con números y cosas que pueden ser medidas objetivamente.

Discreta: Discreta o categórica, puede tomar finitos valores posibles. *(número de estudiantes en clases)*

Continua: Datos que pueden tomar infinitos valores posibles. *(peso de una persona)*

Las variables pueden ser dependientes o independientes.

### Estadística

Área de matemáticas aplicadas concernientes a la recolección, análisis, interpretación o presentación de datos.

Población: colección de un conjunto de individuos, objetos o eventos cuyas propiedades serán analizadas.

Muestra: Subconjunto de la población. Una muestra bien elegida contendrá la mayoría de la información sobre un parámetro particular de la población.

**Estadística Descriptiva**

Usa los datos para proveer descripciones de la población, ya sea a través de cálculos numéricos, gráficos o tablas. Se centra en las características de los datos. Provee un resumen gráfico de los datos.

**Medidas de tendencia central**

Media: Promedio de valores

Mediana: Medida del valor central de la muestra. Para datos impares, se calcula la media entre los dos valores del medio.

Moda: El valor mas recurrente/mas repetido.

**Medidas de variabilidad (dispersión)**

Rango: medida de que tan dispersos están los valores. $Range = Max(x_i) - Min(x_i)$

Rango Inter Cuartil: Dispersión de los datos según la división de los datos en 4. A cada división le corresponde un nombre: Cuartil 1 = Q1, etc. El rango Inter cuartil es igual a Q3 menos Q1. $IQR = Q3-Q1$

Varianza: 

Desviación Estándar:

**Estadística Inferencial**

Realiza inferencias y predicciones sobre la población basada en una muestra de datos tomada de la población. Generaliza un data set grande y aplica probabilidad para sacar una conclusión infiriendo parámetros de los datos.

### Muestreo

![Screenshot_20240326-082822.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f0a778ed-4d37-4d94-8eef-32a143a027dd/b9248846-1419-48fa-afa1-adc2f0c6d639/Screenshot_20240326-082822.png)

Método estadístico que lidia con la selección de observaciones individuales dentro de una población. Su objetivo es inferir conocimiento estadístico sobre la población evitando estudiar a la población entera.

**Muestreo probabilístico**

Técnica que extrae muestras de poblaciones grandes usando la teoría de la probabilidad.

**Random Sampling:** En este método caca miembro tiene una chance similar de ser elegidos en la muestra.

**Systematic Sampling:** Cada enésimo registro (cada segundo, tercer o quinto grupo) es elegido desde la población para ser parte de la muestra.

**Stratified Sampling:** Un estrato es un subconjunto de la población que comparte al menos una característica en común. La población se divide en estratos y posteriormente se aplica random sampling en cada estrato. *El estrato podría ser el género, rango de edades o cantidad de ejercicio físico.*

###