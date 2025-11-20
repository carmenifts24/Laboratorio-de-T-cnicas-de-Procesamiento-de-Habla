# Análisis de NLP: Extracción de Lenguaje y Web Scraping

## Descripción

Este repositorio agrupa los notebooks y materiales desarrollados durante la primera clase del laboratorio de Procesamiento de Lenguaje Natural (NLP). El enfoque principal está puesto en la recolección y preparación de datos textuales desde la web, así como en técnicas de preprocesamiento inicial que permiten abordar corpus multilingües.

A lo largo de esta actividad, se trabajó en la detección automática de idiomas, la extracción de contenido desde sitios web mediante BeautifulSoup y Trafilatura, y la creación de interfaces simples para facilitar el proceso de scraping y análisis.

## Contenido del Proyecto

El repositorio incluye:

- **000_LangExtract.ipynb**: Detección de idioma a partir de textos multilingües utilizando `langdetect` y `langid`.
- **001_Gradio_BeautifulS.ipynb**: Construcción de una interfaz interactiva con Gradio para realizar scraping de sitios web.
- **002_Web_Scraping_BeautifulS.ipynb** y **003_Web_Scraping_BeautifulS2.ipynb**: Extracción de texto desde HTML usando selectores con `BeautifulSoup`.
- **004_Trafilatura.ipynb**: Extracción avanzada de contenido relevante usando `Trafilatura`.
- **Clase 1 - Web Scraping BeautifulSoup.pptx**: Presentación teórica de apoyo sobre técnicas de scraping.
- **Clase 1 - Flujo de Trabajo.pptx** y **Clase 1 - Int al Laboratorio.pptx**: Material de introducción y metodología general del laboratorio.

## Objetivos de Aprendizaje

- Comprender la importancia de la detección de idioma en NLP.
- Realizar extracción de datos desde fuentes no estructuradas (web scraping).
- Familiarizarse con herramientas modernas como `BeautifulSoup`, `Trafilatura` y `Gradio`.
- Establecer un flujo de trabajo reproducible para adquisición de corpus.

## Tecnologías Utilizadas

- Python 3.x
- `langdetect`, `langid`
- `requests`, `beautifulsoup4`
- `gradio`
- `trafilatura`
- `jupyter notebook`

## Instrucciones de Uso

1. Cloná este repositorio:
   ```bash
   git clone https://github.com/tu-usuario/rodriguez-carmen-clase1-nlp.git
   cd rodriguez-carmen-clase1-nlp
