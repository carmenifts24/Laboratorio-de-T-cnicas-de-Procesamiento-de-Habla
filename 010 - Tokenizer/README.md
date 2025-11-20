# Procesamiento de Lenguaje Natural con Transformers y Modelos de Lenguaje

Este repositorio contiene una colección de notebooks orientados a introducir, explorar y aplicar los conceptos fundamentales y avanzados del procesamiento de lenguaje natural (NLP) mediante el uso de modelos de lenguaje y arquitecturas basadas en transformers.

Los contenidos se organizan de forma progresiva, desde la motivación y estructura de los modelos de lenguaje, hasta aplicaciones concretas como generación de texto y resumen automático.

---

## 📁 Estructura del repositorio

### 1. Fundamentos de los Modelos de Lenguaje
- **01_Introduccion_Modelos_Lenguaje.ipynb**  
  Introducción al concepto de modelos de lenguaje, historia, evolución, y motivaciones teóricas. Se abordan temas como la modelización probabilística del lenguaje y los primeros modelos estadísticos.

- **02_Tokens_y_Embeddings.ipynb**  
  Explicación detallada del proceso de tokenización (WordPiece, Byte Pair Encoding, etc.) y las representaciones vectoriales (embeddings) como Word2Vec, GloVe, y contextualizados (BERT, GPT).

### 2. Arquitectura Transformer y Aplicaciones
- **03_Arquitectura_Transformer.ipynb**  
  Descripción del modelo Transformer propuesto por Vaswani et al. Se explican conceptos clave como atención, multi-head attention, codificadores-decodificadores, y auto-atención.

- **04_Aplicaciones_Transformers.ipynb**  
  Casos prácticos con Transformers preentrenados aplicados a tareas como clasificación, traducción, reconocimiento de entidades y más.

### 3. Aplicaciones Avanzadas
- **05_Generacion_Texto_Avanzada.ipynb**  
  Exploración de técnicas de generación de texto (greedy, beam search, top-k, nucleus sampling), y su implementación con modelos como GPT y T5.

- **06_Sumarizacion_Aplicada.ipynb**  
  Aplicación de modelos preentrenados para la tarea de sumarización automática de textos extensos. Se incluyen comparaciones entre extractive y abstractive summarization.

### 4. Recursos Complementarios
- **Guia_Token_HuggingFace.md**  
  Guía paso a paso para generar, almacenar y utilizar tu token de autenticación personal de Hugging Face para acceder a modelos, datasets o usar APIs en notebooks.

- **Guia_Token_HuggingFace.ipynb**  
  Versión interactiva en notebook que implementa los pasos de la guía anterior directamente desde Python.

- **intro-llms-texto-con-texto.ipynb**  
  Demostración práctica de cómo los LLMs pueden utilizarse para tareas complejas a partir de instrucciones textuales. Ejemplos con transformers aplicados directamente a problemas reales.

- **tlon-uqbar-orbis-tertius.txt**  
  Texto de referencia literaria ("Tlön, Uqbar, Orbis Tertius" de Borges), utilizado en ejemplos de procesamiento y generación de texto. Útil para tareas de inferencia semántica, análisis de estilo, y generación basada en corpus literario.

---

## 🧠 Objetivos del proyecto

- Comprender el funcionamiento interno de los modelos de lenguaje y su evolución.
- Aprender a aplicar modelos preentrenados de Hugging Face a diversas tareas de NLP.
- Desarrollar habilidades prácticas en generación de texto, clasificación, y resumen automático.
- Reflexionar sobre el impacto de estos modelos en la representación del conocimiento textual.

---

## ⚙️ Requisitos técnicos

- Python 3.8+
- `transformers`
- `huggingface_hub`
- `datasets`
- `torch` o `tensorflow` (según el modelo)
- `gradio` (opcional para visualizaciones interactivas)

Instalación recomendada:

```bash
pip install -U transformers huggingface_hub datasets gradio
