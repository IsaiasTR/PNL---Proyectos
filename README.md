# PNL-Proyectos
Repositorio que contiene trabajos y notebooks de Procesamiento de Lenguaje Natural

Desafío 1 : Análisis de Similaridad y Clasificación

En este desafío, se abordaron tres consignas clave: primero, se vectorizaron documentos seleccionando cinco al azar para medir su similaridad con el resto, analizando los cinco documentos más similares y evaluando su coherencia con respecto a su contenido y clasificación. En segundo lugar, se entrenaron modelos de clasificación Naïve Bayes, optimizando los parámetros para maximizar el f1-score macro en el conjunto de test, incluyendo tanto el modelo Multinomial como el ComplementNB. Por último, se transpuso la matriz documento-término para obtener una matriz término-documento y se estudiaron las similitudes entre cinco palabras seleccionadas manualmente, asegurando así la relevancia y la interpretabilidad de los términos analizados.

Desafío 2 : Generación y Análisis de Embeddings con Word2Vec

En el Desafío 2, el objetivo fue crear vectores de palabras utilizando Gensim y un dataset del Proyecto Gutenberg. Se exploran las similitudes entre términos, se prueban tests de analogías y se visualizan los embeddings resultantes.

En preprocesamiento_datos.ipynb, se realiza la limpieza y preparación del corpus. En entrenamiento_word2vec.ipynb, se entrena el modelo Word2Vec ajustando parámetros clave. En analisis_similitudes.ipynb, se analizan las similitudes entre palabras en el espacio de embeddings. En tests_analogias.ipynb, se prueban analogías semánticas. Finalmente, visualizacion_embeddings.ipynb presenta la proyección de los embeddings en 2D usando t-SNE o PCA.
El proyecto demuestra cómo los embeddings capturan relaciones semánticas y permite analizarlas visualmente.

Desafío 3 : Modelos de Lenguaje Basados en Tokenización por Palabras y Caracteres

Este repositorio contiene la solución al desafio 3, dividido en dos partes, donde se implementan modelos de lenguaje basados en tokenización por palabras y por caracteres utilizando redes neuronales recurrentes (RNN). Ambos modelos generan secuencias de texto a partir de secuencias de contexto, explorando diferentes estrategias de búsqueda para la generación.

En la Parte 1, se trabaja con un modelo de lenguaje con tokenización por palabras. El notebook correspondiente realiza el preprocesamiento del corpus, tokeniza el texto por palabras y lo divide en conjuntos de entrenamiento y validación. Luego, se entrenan modelos de RNN con diferentes arquitecturas y se generan nuevas secuencias utilizando greedy search, beam search y beam search estocástico. Además, se analiza cómo la variación de la temperatura afecta la generación de texto en la búsqueda estocástica.

En la Parte 2, se implementa un modelo de lenguaje con tokenización por caracteres. El proceso de tokenización y preprocesamiento se adapta para trabajar con caracteres en lugar de palabras. También se proponen y entrenan RNNs adecuadas para este enfoque. Las secuencias generadas a partir del modelo se obtienen utilizando las mismas estrategias de búsqueda que en la Parte 1, comparando los resultados y observando las diferencias en la generación de secuencias a nivel de caracteres.

Este proyecto permite comparar el comportamiento de los modelos de lenguaje con diferentes enfoques de tokenización, explorando cómo las estrategias de búsqueda y la temperatura influyen en la calidad de las secuencias generadas.

Desafío 4 :
