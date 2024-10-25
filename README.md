# PNL-Proyectos
Repositorio que contiene trabajos y notebooks de Procesamiento de Lenguaje Natural

Desafío 1 : Análisis de Similaridad y Clasificación

![Desafío 1](https://drive.google.com/uc?id=1DMK8JXINEEhYCU4h6RkXLdaMihMqsZxc)

En este desafío, se abordaron tres consignas clave: primero, se vectorizaron documentos seleccionando cinco al azar para medir su similaridad con el resto, analizando los cinco documentos más similares y evaluando su coherencia con respecto a su contenido y clasificación. En segundo lugar, se entrenaron modelos de clasificación Naïve Bayes, optimizando los parámetros para maximizar el f1-score macro en el conjunto de test, incluyendo tanto el modelo Multinomial como el ComplementNB. Por último, se transpuso la matriz documento-término para obtener una matriz término-documento y se estudiaron las similitudes entre cinco palabras seleccionadas manualmente, asegurando así la relevancia y la interpretabilidad de los términos analizados.

Desafío 2 : Generación y Análisis de Embeddings con Word2Vec

![Desafío 2](https://drive.google.com/uc?id=1zvOGOPpqpvGLxNFrDNi20xH3MmGk2rgE)

En el Desafío 2, el objetivo fue crear vectores de palabras utilizando Gensim y un dataset del Proyecto Gutenberg. Se exploran las similitudes entre términos, se prueban tests de analogías y se visualizan los embeddings resultantes.

En preprocesamiento_datos.ipynb, se realiza la limpieza y preparación del corpus. En entrenamiento_word2vec.ipynb, se entrena el modelo Word2Vec ajustando parámetros clave. En analisis_similitudes.ipynb, se analizan las similitudes entre palabras en el espacio de embeddings. En tests_analogias.ipynb, se prueban analogías semánticas. Finalmente, visualizacion_embeddings.ipynb presenta la proyección de los embeddings en 2D usando t-SNE o PCA.
El proyecto demuestra cómo los embeddings capturan relaciones semánticas y permite analizarlas visualmente.

Desafío 3 : Modelos de Lenguaje Basados en Tokenización por Palabras y Caracteres

![Desafío 2](https://drive.google.com/uc?id=1m-AOuf9VotQtCmshWsL6QnzAwtHWL7_r)

Este repositorio contiene la solución al desafio 3, dividido en dos partes, donde se implementan modelos de lenguaje basados en tokenización por palabras y por caracteres utilizando redes neuronales recurrentes (RNN). Ambos modelos generan secuencias de texto a partir de secuencias de contexto, explorando diferentes estrategias de búsqueda para la generación.

En la Parte 1, se trabaja con un modelo de lenguaje con tokenización por palabras. El notebook correspondiente realiza el preprocesamiento del corpus, tokeniza el texto por palabras y lo divide en conjuntos de entrenamiento y validación. Luego, se entrenan modelos de RNN con diferentes arquitecturas y se generan nuevas secuencias utilizando greedy search, beam search y beam search estocástico. Además, se analiza cómo la variación de la temperatura afecta la generación de texto en la búsqueda estocástica.

En la Parte 2, se implementa un modelo de lenguaje con tokenización por caracteres. El proceso de tokenización y preprocesamiento se adapta para trabajar con caracteres en lugar de palabras. También se proponen y entrenan RNNs adecuadas para este enfoque. Las secuencias generadas a partir del modelo se obtienen utilizando las mismas estrategias de búsqueda que en la Parte 1, comparando los resultados y observando las diferencias en la generación de secuencias a nivel de caracteres.

Este proyecto permite comparar el comportamiento de los modelos de lenguaje con diferentes enfoques de tokenización, explorando cómo las estrategias de búsqueda y la temperatura influyen en la calidad de las secuencias generadas.

Desafío 4 : Construcción de un BOT Conversacional para Preguntas y Respuestas

Este repositorio contiene la solución al Desafío 4, cuyo objetivo es construir un BOT para responder a preguntas del usuario utilizando los datos del challenge ConvAI2 (Conversational Intelligence Challenge 2). El enfoque se basa en entrenar un modelo de lenguaje capaz de realizar tareas de preguntas y respuestas (QA) en conversaciones en inglés.

El notebook comienza con la carga y exploración del dataset de conversaciones, seguido del preprocesamiento de los datos para estructurarlos de manera adecuada para el entrenamiento. A continuación, se implementa un modelo basado en redes neuronales, optimizado para el contexto de diálogos y respuestas. Se entrenan varios modelos, evaluando su capacidad de generar respuestas coherentes y precisas a partir de las preguntas planteadas.

Posteriormente, se realizan pruebas del BOT utilizando diferentes estrategias de búsqueda, como greedy search y beam search, para generar las respuestas. Finalmente, se evalúa el rendimiento del BOT en términos de fluidez y coherencia en las conversaciones, comparando las diferentes estrategias de generación.

Este desafío explora la creación de un sistema conversacional eficiente para tareas de QA, demostrando cómo los modelos de lenguaje pueden ser aplicados en contextos de interacción con usuarios.

Desafío 5 : Mejoras en un Modelo de Clasificación Multiclase

Este repositorio contiene la solución al Desafío 5, centrado en implementar mejoras a un modelo de clasificación multiclase ajustando su arquitectura y optimización. El objetivo es adaptar el modelo para clasificar textos en cinco clases que representan diferentes grados de polaridad: Muy negativo, Negativo, Neutro, Positivo y Muy positivo.

Las mejoras incluyen el ajuste del parámetro Output_shape de 3 a 5 para reflejar correctamente las cinco categorías de la tarea de clasificación. Se añadieron capas densas adicionales de 128 y 64 neuronas, que permiten al modelo aprender representaciones más abstractas y complejas. Además, se incorporó regularización con Dropout del 30% tras cada capa densa, con el fin de evitar el sobreajuste y mejorar la capacidad del modelo para generalizar en datos no vistos. La capa de salida fue ajustada con activación softmax para generar probabilidades para las cinco clases.

Finalmente, el modelo fue compilado con métricas de accuracy y F1_score, proporcionando una evaluación más equilibrada y robusta de su rendimiento en la clasificación multiclase.

Este desafío aborda las mejoras en la arquitectura y el entrenamiento del modelo para mejorar su precisión y capacidad de generalización en tareas de clasificación con múltiples categorías.






