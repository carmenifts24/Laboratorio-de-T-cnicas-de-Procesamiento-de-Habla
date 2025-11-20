Laboratorio de PLN Multimodal con n8n, Ollama y Docker
Descripción

Este laboratorio se enfoca en la implementación de soluciones de Procesamiento de Lenguaje Natural (PLN) utilizando herramientas modernas de código abierto, integrando modelos de lenguaje (LLMs), flujos de trabajo automatizados con n8n, y la ejecución local de modelos con Ollama. Además, se abordan tareas como transcripción de audio y video, análisis de sentimientos, extracción de entidades nombradas (NER), captioning de imágenes, y la creación de asistentes NLP personalizados con Docker + n8n + LLMs.

El objetivo de esta clase es brindar experiencia práctica en el diseño, despliegue y uso de pipelines de PLN que incluyan entradas textuales, visuales y de audio, combinando APIs locales y servicios basados en contenedores. También se exploran aspectos de trabajo colaborativo con Git y GitHub.

Contenido del Proyecto

000_Git_GitHub_Trabajo_Equipo.ipynb: Introducción a buenas prácticas con Git y GitHub para trabajo colaborativo.

001_Audio_Transcripcion_Resumen.ipynb: Flujo de trabajo completo para cargar audio, transcribirlo y generar un resumen.

001A_Transcripcion_Audio_Simple.ipynb: Transcripción básica de archivos de audio usando Whisper.

001B_Transcripcion_Video_Simple.ipynb: Transcripción básica de videos a texto.

002_NER_Transformers_Gemini.ipynb: Extracción de entidades nombradas con modelos de Transformers y Gemini.

003_Image_Captioning_Basico.ipynb: Descripción automática de imágenes mediante modelos preentrenados.

004_Image_Captioning_Avanzado.ipynb: Captioning multimodal avanzado utilizando modelos de visión y lenguaje.

005_Asistente_NLP_Docker_n8n_Ollama.ipynb: Creación de un asistente NLP funcional combinando n8n, Docker y Ollama.

asistente-nlp.json: Archivo de configuración de flujo de trabajo para importar en n8n.

guia-n8n-ollama-docker.txt: Guía detallada para la configuración de Docker, n8n y Ollama.

Técnicas y Tecnologías Utilizadas

Procesamiento de Audio: Whisper/OpenAI para transcripción.

Modelos de Lenguaje: Hugging Face, Ollama, Gemini.

Visión por Computadora: Captioning de imágenes con modelos como BLIP2 y similares.

Tareas de NLP: Análisis de sentimiento, NER, clasificación de texto, extracción de palabras clave.

Docker: Orquestación de servicios con docker-compose.

n8n: Automatización de flujos de trabajo con nodos visuales.

LLMs locales: Integración de Ollama para procesamiento en entorno local sin necesidad de APIs externas.

Git/GitHub: Control de versiones y trabajo colaborativo.

Instrucciones de Uso

Clona este repositorio:

git clone https://github.com/tu_usuario/nombre_repositorio.git
cd nombre_repositorio


Instala las dependencias necesarias (según el notebook que quieras ejecutar):

pip install -r requirements.txt


Levanta el entorno de procesamiento si vas a usar Docker:

docker-compose up -d


Abre los notebooks en Jupyter:

jupyter notebook


Importa el flujo asistente-nlp.json en tu instancia de n8n.

Requisitos Técnicos

Docker y Docker Compose instalados

Python 3.9 o superior

Jupyter Notebook

Git (opcional para clonar el proyecto)

Posibles Extensiones

Incluir interfaz Gradio para visualización interactiva.

Añadir más tareas NLP como traducción automática o respuesta a preguntas.

Expandir el asistente para aceptar archivos adjuntos (PDFs, imágenes, etc.).

Crear una API REST con FastAPI que integre los modelos y tareas disponibles.