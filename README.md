# Curso introducción a Machine Learning.

Temario:

- Clase 1:

  - **Presentación:** Introducción a ML, tipos de ML, diferencia entre IA, ML, DL. Modelos supervisados vs no supervisados: diferencias y para qué sirve cada uno. Clasificación vs regresión: diferencias y para qué sirve cada uno, ejemplos de modelos de ambos. Hiper parámetros. Qué es overfitting, técnincas para evitarlo y detectarlo. División el dataset en train y test.

  - **Práctica:** Notebook en Colab, trabajar con datos arificiales en dos dimensiones. División en train y test, probar diferentes modelos utilizando Scikit-learn, comparar (graficar) y entender métricas de un modelo. Detectar overfitting y el impacto de los hiper parámetros.

- Clase 2:

  - **Presentación:** Pipeline de ML, focalización en manejo/preparación de los datos. Pipeline de pre-procesamiento de datos, feature engineering. Cómo trabajar features numéricas y features categóricas. Resolver problemas como missing values, One Hot Encoding.

  - **Práctica:** Notebook en Colab, utilizar el dataset de California Housing Prices para generar un modelo que prediga el valor de una casa. Trabajo de features y exploratory data analysis. Comparación de diferentes modelos y ejemplo de hyperparameter tunning con XGBoost.

- Clase 3:

  - **Presentación:** Presentación deep learning: DL como subconjunto de ML. Concepto de redes neuronales, preceptrón, funciones de activación, capas ocultas, nuevos hiper parámetros. Descenso del gradiente, loss functions, cómo afectan los hiper-parámetros. Redes multi capas y cómo se entrenan.

  - **Práctica:** Notebook en Colab, armado de una red neuronal utilizando Tensorflow y Keras para detección de dígitos escritos a mano. Definir arquitectura de la red, enterenarla, hacer gráficos para visualizar las métricas de evaluación en función de epochs. Comparación de diferentes hiper parámetros: cambiar cantidad de hidden layers, learning rate.

- Clase 4:

  - **Presentación:** Repaso e introducción a algunas arquitecturas complejas de redes neuronales: Convolucionales, recurrentes, autoencoders, transformers. Qué es feature extraction y cómo funcionan las redes convolucionales que lo reemplazan. Qué es fine tunning y como nos puede ayudar para utilizar modelos más potentes.

  - **Práctica:** Notebook en Colab, hacer fine tunning en un modelo YOLO para que detecte la etiqueta food en imagenes. Para armar el dataset de entrenamiento se utiliza el modelo GroundingDINO sobre un dataset de imagenes de comida para generar las etiquetas. Comparación entre el modelo YOLO pre entrenado y el modelo con fine tunning.
