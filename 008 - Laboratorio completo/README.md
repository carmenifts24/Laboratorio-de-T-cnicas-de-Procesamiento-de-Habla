Clasificación de Texto con Técnicas de PLN y Deep Learning
Descripción

Este proyecto reúne una serie de notebooks desarrollados durante una clase avanzada de Procesamiento del Lenguaje Natural (PLN), con el objetivo de explorar distintas técnicas de clasificación de texto. A lo largo del recorrido, se abordan tanto métodos tradicionales basados en representaciones como TF-IDF y modelos de machine learning clásicos, como también enfoques más avanzados mediante redes neuronales profundas y modelos preentrenados como Transformers.

Los notebooks están diseñados con fines educativos y cubren desde el preprocesamiento del texto y la ingeniería de características, hasta el uso de herramientas como PyTorch, Keras y Hugging Face para construir y entrenar modelos de clasificación.

Contenidos Incluidos

01_Clasificación_con_Sklearn_y_TF-IDF.ipynb
Introducción a la clasificación de texto con modelos clásicos como Regresión Logística y SVM, utilizando TF-IDF como representación vectorial.

02_Naive_Bayes_y_Pipelines.ipynb
Implementación de un clasificador Naive Bayes junto con Pipeline de Scikit-learn para automatizar el flujo de procesamiento y entrenamiento.

03_Perceptrón_Simple_desde_Cero.ipynb
Construcción manual de un perceptrón simple desde cero para comprender su lógica de funcionamiento paso a paso.

04_Red_Neuronal_Multicapa_PyTorch.ipynb
Desarrollo de una red neuronal multicapa (MLP) utilizando PyTorch para tareas de clasificación.

05_LSTM_con_Keras_Secuencias.ipynb
Implementación de una red neuronal recurrente LSTM con Keras para el tratamiento de secuencias de texto.

06_Transformers_Preentrenados_HuggingFace.ipynb
Uso de modelos preentrenados (como BERT) de la biblioteca Hugging Face Transformers para clasificación de texto con embeddings contextuales.

gradio_intro.ipynb
Introducción al uso de la herramienta Gradio para construir interfaces gráficas simples de inferencia y visualización de modelos de PLN.

LABORATORIO_DESARROLLO_1_HABLA.ipynb
Actividad de laboratorio orientada al desarrollo práctico de modelos e interfaces conversacionales, integrando componentes del procesamiento del lenguaje.

Técnicas de PLN Aplicadas

Preprocesamiento de texto (limpieza, tokenización)

Vectorización con CountVectorizer y TF-IDF

Clasificadores supervisados clásicos (Naive Bayes, SVM, Logistic Regression)

Redes neuronales (Perceptrón, MLP, LSTM)

Transfer Learning con Transformers preentrenados

Implementación de interfaces interactivas con Gradio

Tecnologías Utilizadas

Python 3.x

pandas, numpy, scikit-learn

PyTorch, Keras (TensorFlow backend)

Hugging Face Transformers

Gradio

Matplotlib, Seaborn (para visualización)

Instrucciones de Uso

Clonar este repositorio.

Instalar las dependencias necesarias:

pip install -r requirements.txt


Ejecutar cada notebook individualmente en Jupyter Notebook, Jupyter Lab o Google Colab.