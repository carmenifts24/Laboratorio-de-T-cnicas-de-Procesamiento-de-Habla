Análisis de NLP: spaCy en el Procesamiento del Lenguaje Natural
Descripción

Este proyecto corresponde a una clase dedicada al uso de la biblioteca spaCy para realizar tareas fundamentales de procesamiento del lenguaje natural (PLN) en español. A través de ejemplos prácticos, se introducen herramientas clave como la tokenización, lematización, etiquetado gramatical (POS tagging), análisis de dependencias sintácticas y reconocimiento de entidades nombradas (NER). Se exploran los fundamentos teóricos y se aplican directamente sobre textos reales en español, permitiendo una comprensión progresiva de cómo funciona un pipeline de NLP moderno.

El propósito de esta clase es que los y las estudiantes comprendan el funcionamiento interno de un modelo entrenado como es_core_news_sm, puedan visualizar la estructura gramatical de un texto, y adaptar el pipeline de spaCy para tareas personalizadas, como lematización manual de entidades no reconocidas por defecto.

Información del Corpus

Tipo: Digital (textos sintéticos y ejemplos de spaCy)

Tamaño: Varios ejemplos cortos procesados dinámicamente

Fuentes principales: Sentencias manuales, ejemplos provistos por spaCy

Período temporal: No aplica

Criterios de selección: Textos breves, representativos y variados para demostrar las funcionalidades de spaCy en español

Técnicas de NLP Aplicadas

Preprocesamiento de texto con spaCy

Tokenización, lematización y POS tagging

Análisis de dependencias sintácticas (dependency parsing)

Reconocimiento de entidades nombradas (NER)

Chunking (identificación de noun phrases)

Personalización del pipeline de spaCy

Principales Hallazgos

Se demostró la capacidad de spaCy para analizar texto en español con alta precisión, reconociendo entidades, lemas y estructuras gramaticales automáticamente.

El análisis sintáctico permite comprender las relaciones profundas entre los elementos de una oración (quién hace qué, a quién, cuándo, etc.).

La personalización del pipeline permite adaptar el análisis a casos particulares, como reconocer que "Baires" es equivalente a "Buenos Aires".

Tecnologías Utilizadas

Python 3.x

spaCy
 (es_core_news_sm)

collections.Counter

Visualización con displacy