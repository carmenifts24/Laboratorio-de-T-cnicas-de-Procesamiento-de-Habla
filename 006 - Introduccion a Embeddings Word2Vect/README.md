Análisis de NLP: De Bag of Words a Word Embeddings
Descripción

Esta clase está dedicada a explorar los distintos métodos de representación de texto utilizados en el Procesamiento del Lenguaje Natural (NLP), con un enfoque progresivo que va desde los enfoques clásicos como Bag of Words (BoW) y TF-IDF, hasta técnicas más avanzadas basadas en Word Embeddings (Word2Vec, FastText, GloVe) y su visualización.
El objetivo principal es comprender cómo los distintos modelos representan el significado de las palabras y cómo esto impacta en la capacidad de análisis semántico del lenguaje.

Se analizaron corpus de ejemplo, se compararon modelos de representación, se evaluó la similitud semántica entre palabras y documentos, y se trabajó con visualizaciones de alta dimensión reducidas mediante técnicas como PCA o t-SNE.

Información del Corpus

Tipo: Digital / Educativo

Tamaño: Documentos de prueba con múltiples frases y corpus de demostración.

Fuentes principales: Corpus generados o descargados desde fuentes de prueba educativas y librerías.

Período temporal: No aplica (corpus de ejemplo)

Criterios de selección: Textos representativos para demostrar el uso y comparación entre técnicas de representación de texto.

Técnicas de NLP Aplicadas

Preprocesamiento de texto (limpieza, tokenización, lematización, stemming)

Vectorización clásica: Bag of Words (BoW) y TF-IDF

Embeddings: Word2Vec, FastText y GloVe

Visualización de embeddings (PCA, t-SNE)

Comparación de similitud semántica

Análisis integrador con notebooks de síntesis y ejercicios prácticos

Principales Hallazgos

BoW y TF-IDF son útiles para tareas basadas en frecuencia pero no capturan el significado semántico.

Word Embeddings permiten representar relaciones semánticas complejas entre palabras.

Visualizar los embeddings ayuda a entender agrupamientos y similitudes conceptuales.

FastText mejora la representación de palabras raras o mal escritas al incorporar subpalabras.

GloVe destaca por su capacidad de representar relaciones globales entre términos.

Tecnologías Utilizadas

Python 3.x

pandas, numpy

scikit-learn

spaCy

gensim

matplotlib, seaborn

nltk

plotly

sklearn.decomposition (PCA)

sklearn.manifold (t-SNE)

Instrucciones de Reproducción

Clonar este repositorio

Instalar las dependencias: pip install -r requirements.txt

Ejecutar los notebooks en orden recomendado:

01_Fundamentos_BoW_TFIDF.ipynb

02_Preprocesamiento_Stemming_Lemmatization.ipynb

03_Embeddings_Word2Vec.ipynb

04_FastText_GloVe.ipynb

05A_Sintesis_Integracion.ipynb

05B_Ejercicios_Similitud.ipynb

L1-embeddings-intro.ipynb

L3-visualizing-embeddings.ipynb

Limitaciones y Trabajo Futuro

Los corpus utilizados son limitados en tamaño y contexto; aplicar a corpus reales permitiría generalizar mejor los resultados.

No se abordaron embeddings contextuales (como BERT), que podrían enriquecer aún más el análisis semántico.

Faltan experimentos con tareas reales de NLP (clasificación, clustering, resumen, etc.).

Autor

Carmen Rodríguez
Trabajo de Clase – Representaciones Vectoriales en PLN
Fecha: Septiembre 2025