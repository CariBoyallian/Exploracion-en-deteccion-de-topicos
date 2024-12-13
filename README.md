# TextMining2024
# Exploración en topic detection\modeling.

La detección de temas en conjuntos de documentos es un área activa en procesamiento del lenguaje natural (NLP), con aplicaciones que van desde la organización automática de textos hasta el análisis de grandes volúmenes de datos en investigación y negocios. Tradicionalmente, métodos como el Latent Dirichlet Allocation (LDA)  han sido utilizados para identificar temas en textos, agrupando documentos en función de tópicos compartidos. Con los avances en aprendizaje automático, han surgido enfoques que combinan embeddings de palabras y documentos con modelos neuronales para mejorar la precisión y coherencia de los temas identificados. La evaluación de estos métodos  a distintos conjuntos de datos sigue siendo un desafío  en la optimización de técnicas de detección de temas.

Presentamos los resultados de una prueba de factibilidad en detección de temas, evaluando la  de cinco tipos de embeddings —TF-IDF, LSA, Doc2Vec , DistilBERT  y LDA— en combinación con técnicas de clustering y modelos avanzados de detección de temas. Para el estudio se utiliza el conjunto de datos 20Newsgroups,(https://archive.ics.uci.edu/dataset/113/twenty+newsgroups), una referencia común en NLP por su estructura organizada en múltiples categorías temáticas.

# Hipótesis Inicial

Como hipótesis inicial esperabamos que embeddings avanzados como LDA, Doc2Vec o DistilBERT superaran a TF-IDF en términos de calidad de clustering, dado que estos modelos están diseñados para capturar relaciones semánticas profundas entre palabras y documentos.

# Conclusion

Los métodos tradicionales como TF-IDF mostraron mejor desempeño en términos de pureza y coherencia en clustering básico, mientras que entre los em-
beddings neuronales  se destacó DistilBertcon con el modelo ETM. Sin embargo, el rendimiento global de estos modelos sigue siendo bajo con re-
specto al Benchmarck Topic Models on 20NewsGroups.( https://paperswithcode.com/sota/topic-models-on-20newsgroups).


