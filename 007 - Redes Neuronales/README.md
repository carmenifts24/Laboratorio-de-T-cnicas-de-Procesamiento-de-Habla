Clasificación de Texto con Técnicas de Aprendizaje Automático y Profundo
Descripción

Este proyecto explora diferentes enfoques para la clasificación automática de texto utilizando técnicas de procesamiento de lenguaje natural (NLP) y aprendizaje automático, comenzando con modelos clásicos como TF-IDF + Naive Bayes y evolucionando hacia modelos más complejos como redes neuronales y transformers preentrenados. A través de esta progresión, se busca comprender las capacidades predictivas de cada enfoque y su aplicabilidad a problemas reales de clasificación textual.

Los notebooks incluidos conforman una ruta de aprendizaje gradual que permite comparar modelos simples vs complejos, evaluar métricas de desempeño y observar cómo el uso de embeddings y modelos de lenguaje avanzados puede mejorar significativamente los resultados de clasificación.

Contenido

El proyecto está compuesto por los siguientes notebooks:

01_Clasificacion_con_Sklearn_y_TF-IDF.ipynb
Introducción al modelo clásico de clasificación con TF-IDF y clasificadores de scikit-learn.

02_Naive_Bayes_y_Pipelines.ipynb
Uso de pipelines para combinar procesamiento y modelado, aplicación del clasificador Naive Bayes y análisis de desempeño.

03_Perceptron_Simple_desde_Cero.ipynb
Implementación desde cero de un perceptrón simple para tareas básicas de clasificación binaria.

04_Red_Neuronal_Multicapa_PyTorch.ipynb
Introducción a PyTorch, implementación de una red neuronal multicapa para clasificación, entrenamiento y evaluación.

05_LSTM_con_Keras_Secuencias.ipynb
Modelado de secuencias de texto con redes LSTM utilizando Keras, ideal para capturar relaciones temporales o dependencias en secuencia.

06_Transformers_Preentrenados_HuggingFace.ipynb
Uso de modelos de lenguaje preentrenados (como BERT) de HuggingFace para clasificación de texto con embeddings contextuales.

Objetivos del Proyecto

Explorar diversas técnicas de clasificación de texto.

Comparar el rendimiento de modelos clásicos vs redes neuronales.

Introducir modelos de última generación como BERT y su impacto en NLP.

Comprender el flujo completo de un proyecto de clasificación textual: desde el preprocesamiento hasta la evaluación final.

Tecnologías Utilizadas

Python 3.x

scikit-learn

pandas, numpy, matplotlib, seaborn

NLTK y spaCy

PyTorch

Keras y TensorFlow

HuggingFace Transformers

Instrucciones de Uso

Clona este repositorio.

Instala las dependencias necesarias (ver archivo requirements.txt).

Abre cada notebook en orden y ejecútalo paso a paso.

Personaliza el dataset o hiperparámetros si deseas experimentar.