# PNL-Proyectos
Repositorio que contiene trabajos y notebooks de Procesamiento de Lenguaje Natural

Desafío 1 : Análisis de Similaridad y Clasificación

En este desafío, se abordaron tres consignas clave: primero, se vectorizaron documentos seleccionando cinco al azar para medir su similaridad con el resto, analizando los cinco documentos más similares y evaluando su coherencia con respecto a su contenido y clasificación. En segundo lugar, se entrenaron modelos de clasificación Naïve Bayes, optimizando los parámetros para maximizar el f1-score macro en el conjunto de test, incluyendo tanto el modelo Multinomial como el ComplementNB. Por último, se transpuso la matriz documento-término para obtener una matriz término-documento y se estudiaron las similitudes entre cinco palabras seleccionadas manualmente, asegurando así la relevancia y la interpretabilidad de los términos analizados.

Desafío 2 : Generación y Análisis de Embeddings con Word2Vec

En el Desafío 2, el objetivo fue crear vectores de palabras utilizando Gensim y un dataset del Proyecto Gutenberg. Se exploran las similitudes entre términos, se prueban tests de analogías y se visualizan los embeddings resultantes.

En preprocesamiento_datos.ipynb, se realiza la limpieza y preparación del corpus. En entrenamiento_word2vec.ipynb, se entrena el modelo Word2Vec ajustando parámetros clave. En analisis_similitudes.ipynb, se analizan las similitudes entre palabras en el espacio de embeddings. En tests_analogias.ipynb, se prueban analogías semánticas. Finalmente, visualizacion_embeddings.ipynb presenta la proyección de los embeddings en 2D usando t-SNE o PCA.
El proyecto demuestra cómo los embeddings capturan relaciones semánticas y permite analizarlas visualmente.
