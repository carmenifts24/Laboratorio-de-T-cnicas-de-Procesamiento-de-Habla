# Análisis de NLP: Representación y Vectorización de Texto en Español

## Descripción
Esta clase se centró en la introducción y aplicación de técnicas fundamentales de **vectorización de texto** dentro del campo del Procesamiento del Lenguaje Natural (NLP), con especial atención a textos en español. A través de notebooks interactivos, exploramos métodos como **Bag of Words (BoW)**, **TF-IDF**, y analizamos cómo representar documentos textuales de forma numérica para su posterior análisis automatizado.

Uno de los ejes principales fue el análisis de los cuentos del escritor argentino **Hernán Casciari**, lo que permitió aplicar conceptos sobre corpus reales, observar patrones léxicos y temáticos, y visualizar la evolución del contenido textual. También se realizó una introducción a la preparación conceptual necesaria para análisis más avanzados.

## Información del Corpus
- **Tipo**: Literatura (cuentos breves)
- **Tamaño**: Aproximadamente 20 textos, más de 10.000 palabras en total
- **Fuentes principales**: Producción literaria de Hernán Casciari
- **Período temporal**: Cuentos publicados entre 2003 y 2020
- **Criterios de selección**: Cuentos representativos del autor disponibles en línea, utilizados como base para análisis de frecuencia y estilo.

## Técnicas de NLP Aplicadas
- Limpieza básica de texto y normalización
- **Vectorización con Bag of Words**
- **Cálculo de TF-IDF**
- Visualización de vectores y matrices de frecuencia
- Análisis comparativo entre términos frecuentes y distintivos
- Exploración cualitativa de vocabulario por documento

## Principales Hallazgos
- El modelo BoW permite identificar rápidamente los temas más recurrentes en los textos del corpus, como relaciones familiares, nostalgia y vida cotidiana.
- TF-IDF reveló palabras clave distintivas por documento, que no son necesariamente frecuentes, pero sí representativas del contenido.
- Las técnicas muestran cómo difieren los estilos y enfoques narrativos en distintos cuentos, facilitando análisis comparativos y agrupamientos temáticos.

## Tecnologías Utilizadas
- Python 3.x
- pandas, numpy
- scikit-learn
- matplotlib, seaborn
- spaCy
- Jupyter Notebook

## Instrucciones de Reproducción
1. Clonar este repositorio.
2. Instalar las dependencias necesarias:
   ```bash
   pip install -r requirements.txt
