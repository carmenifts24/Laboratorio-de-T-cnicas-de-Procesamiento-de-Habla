Análisis de Sentimiento con Modelos de Aprendizaje Automático y Profundo
Descripción

Este proyecto reúne una serie de notebooks que exploran distintas técnicas y arquitecturas para la clasificación de sentimientos en textos. Se parte desde modelos tradicionales como el Perceptrón Simple y Naive Bayes, pasando por redes neuronales multicapa y redes LSTM, hasta llegar a modelos de Transformers preentrenados con HuggingFace. El objetivo es comparar cómo varía el rendimiento y la capacidad de generalización de los modelos a medida que se aumenta la complejidad del enfoque.

Cada notebook se centra en una arquitectura específica, explicando su implementación, entrenamiento, evaluación y visualización de resultados, lo que permite obtener una visión comparativa clara del desempeño de cada técnica en tareas de procesamiento de lenguaje natural.

Estructura del Proyecto

001_Clasificador de sentimientos con un Perceptrón simple.ipynb: Clasificador lineal básico entrenado desde cero.

002_Clasificación de Sentimientos con una Red Neuronal Multicapa.ipynb: Introducción al uso de redes neuronales densas con Keras.

003_Análisis de Sentimiento con una Red LSTM usando Keras.ipynb: Clasificación secuencial usando LSTM para capturar dependencias contextuales.

004_Análisis de Sentimiento con Modelos Preentrenados de HuggingFace.ipynb: Uso de Transformers preentrenados para análisis de sentimiento, con mínima necesidad de entrenamiento adicional.

EJERCICIOS.ipynb: Ejercicios complementarios para afianzar conceptos vistos en clase.

LABORATORIO_DESARROLLO_1_HABLA.ipynb: Actividades exploratorias para análisis de sentimiento aplicados a corpus hablados o transcritos.

gradio_intro.ipynb: Introducción al uso de Gradio para desplegar modelos de PLN en aplicaciones web simples.

Objetivos del Análisis

Entender cómo funcionan distintos modelos para tareas de clasificación de texto.

Comparar arquitecturas simples y complejas en términos de precisión, interpretabilidad y eficiencia.

Experimentar con frameworks modernos de NLP como HuggingFace Transformers y herramientas de visualización como Gradio.

Requisitos Técnicos

Python 3.8+

TensorFlow y Keras

scikit-learn

pandas, numpy

matplotlib, seaborn

Gradio

transformers (HuggingFace)

Puedes instalar las dependencias con:

pip install -r requirements.txt

Instrucciones de Ejecución

Clona este repositorio.

Instala las dependencias.

Abre los notebooks en Jupyter o Google Colab.

Ejecuta cada celda en orden para entrenar y evaluar los modelos.

Resultados Esperados

Visualización clara del impacto de distintas arquitecturas sobre el análisis de sentimientos.

Identificación de ventajas y desventajas de cada enfoque.

Base práctica para seleccionar modelos según el tipo de tarea, volumen de datos y recursos disponibles.