# TAPAS

Este proyecto implementa un modelo de procesamiento de lenguaje natural llamado TAPAS para dar respuesta a preguntas basadas en tablas (_Table Question Answering_). El objetivo principal es desplegar la versión ya entrenada de TAPAS en WikiTableQuestions y permitir que el modelo haga inferencias sobre tablas proporcionadas por el usuario. Además, se evaluará el desempeño del modelo utilizando un conjunto de datos de prueba de WikiTableQuestions, comparando los resultados obtenidos con los reportados en la publicación original del modelo.

## Datos y Tecnologías Utilizadas

- **Modelo**: TAPAS finetuned en WikiTableQuestions.
- **Librerías**: 
  - `transformers` para el modelo y el tokenizador.
  - `pandas` para la manipulación de datos tabulares.
- **Evaluación**: Se utiliza la métrica de accuracy para evaluar el desempeño del modelo en el conjunto de datos de prueba.
- **Infraestructura**: Implementación eficiente utilizando dataloaders e inferencia en batches para mejorar el rendimiento y la eficiencia del proceso.
