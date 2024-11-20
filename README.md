# ML-Examen2doIntentoCodingDojo
Segundo Intento 

Examen de certificación – Intento 2
Duración: 25 horas
Fecha límite: 0 Días, 23 Horas
Descripción
Instrucciones para examen
Objetivo: Este examen tiene como objetivo evaluar la capacidad del estudiante para limpiar, explorar, implementar y evaluar modelos de regresión en un dataset de ventas de retail. Utilizaremos el «Retail Sales Dataset» disponible en Kaggle. Los estudiantes deben demostrar habilidades prácticas en la manipulación de datos, creación de visualizaciones y modelado predictivo.

Contexto y Descripción del Dataset

El «Retail Sales Dataset» contiene datos históricos de ventas de retail, incluidos detalles sobre las ventas diarias de diversas categorías de productos. La tarea es predecir las ventas futuras basándose en varias características que describen productos, categorías y fechas de venta.

Diccionario de Datos:

Transaction ID: Un identificador único para cada transacción, que permite el seguimiento y la referencia.
Date: La fecha en que ocurrió la transacción, proporcionando información sobre las tendencias de ventas a lo largo del tiempo.
Customer ID: Un identificador único para cada cliente, que permite un análisis centrado en el cliente.
Gender: El género del cliente (Masculino/Femenino), ofreciendo información sobre patrones de compra basados en el género.
Age: La edad del cliente, facilitando la segmentación y exploración de influencias relacionadas con la edad.
Product Category: La categoría del producto comprado (por ejemplo, Electrónica, Ropa, Belleza), ayudando a entender las preferencias de productos.
Quantity: El número de unidades del producto comprado, contribuyendo a información sobre volúmenes de compra.
Requisitos

Limpieza de Datos:
Identificación y eliminación de valores duplicados: Asegúrate de que no haya registros duplicados que puedan sesgar los resultados del análisis.
Verificación y ajuste de tipos de datos: Verifica que cada columna tenga el tipo de dato correcto (numérico o categórico) y ajusta si es necesario.
Corrección de inconsistencias en valores categóricos: Revisa las categorías de las variables y unifica aquellos valores que puedan estar escritos de diferentes maneras pero que representen lo mismo.
Manejo de valores faltantes adecuadamente: Identifica y maneja los valores faltantes utilizando técnicas apropiadas como la imputación de la mediana, media o moda, según corresponda.
Exploración de Datos:
Visualizaciones univariadas y multivariadas: Crea histogramas, gráficos de barras, diagramas de dispersión y mapas de calor para entender la distribución y las relaciones entre las variables.
Estadísticas descriptivas: Calcula medidas de tendencia central (media, mediana, moda) y de dispersión (rango, desviación estándar) para cada característica del dataset.
Implementación de Modelos:
Modelos de Regresión: Implementa modelos de Decision Tree Regressor y Random Forest Regressor.
Optimización de Modelos: Utiliza GridSearchCV para optimizar los hiperparámetros de los modelos.
Evaluación de Modelos: Evalúa los modelos utilizando métricas como MSE, RMSE, y R^2.
Comparación de Rendimiento: Compara los resultados de ambos modelos y discute cuál es el más adecuado para este dataset.
Entrega

Los estudiantes deben entregar un archivo .ipynb comentado que incluya:

Proceso completo de limpieza y preprocesamiento de datos.
Visualizaciones y estadísticas descriptivas.
Implementación y evaluación de los modelos de regresión.
Análisis comparativo del rendimiento de los modelos.
Además, el archivo debe subirse a GitHub con un tag de liberación (release tag) que permita identificar la entrega final.

Consideraciones Éticas y Tecnológicas

Consideraciones Éticas:

Transparencia y Reproducibilidad: Asegúrate de que todos los pasos del análisis sean claros y reproducibles. Otros investigadores deben poder seguir tus pasos y llegar a los mismos resultados.
Imparcialidad y Sesgo: Revisa si existen sesgos en los datos que puedan afectar la imparcialidad del modelo. Es importante que los modelos no discriminen injustamente entre diferentes grupos de datos.
Consideraciones Tecnológicas:

Herramientas Utilizadas: Utiliza herramientas estándar como Python, Jupyter Notebook, Pandas, Scikit-learn, Matplotlib y Seaborn.
Escalabilidad: Considera cómo las técnicas aplicadas podrían escalarse para manejar conjuntos de datos más grandes y complejos.
Optimización de Modelos: Utiliza técnicas como GridSearchCV para optimizar los hiperparámetros y mejorar el rendimiento de los modelos.
Link del Dataset

Retail Sales Dataset
