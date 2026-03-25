# Técnicas de Aprendizaje Automático 2025/2026 

## Prueba de progreso 2: Clustering

Usando conjuntos de datos con información sobre el tráfico en diferentes carreteras de Gipuzkoa, encuentra patrones que permitan perfilar las distribuciones de tráfico por hora y zona. Puedes utilizar cualquier técnica de clustering, pero deberás justificar su elección e interpretar los resultados acorde a ella.

## Datos

El gobierno de España, así como varias administraciones regionales y locales, han estado llevando a cabo varias iniciativas **Open Data** mediante las cuáles hacen disponibles a la población general conjuntos de datos sobre varios ámbitos. La Diputación foral de Gipuzkoa, tiene liberados datos sobre tráfico que registran tanto [volumen](https://www.gipuzkoairekia.eus/es/datu-irekien-katalogoa/-/openDataSearcher/detail/detailView/07c8a249-c1ba-4a77-bed3-d174980f652e) como [velocidad](https://www.gipuzkoairekia.eus/es/datu-irekien-katalogoa/-/openDataSearcher/detail/detailView/8d383e31-562a-4abb-bd78-0c1eb139e203).

Aunque ambos conjuntos hacen alusión a los mismos lugares y tiempos, tienen diferencias de formato relevantes que hay que considerar. Por un lado, los datos de **volumen** se calculan por horas, mientras que los de velocidad se calculan cada media hora. Además, el identificador de la estación de grabación de los datos de **volumen** y **velocidad** son diferentes y para poder establecer la relación entre unos y otros se tendrá que usar la información sobre estaciones recogida en [este otro conjunto](https://www.gipuzkoairekia.eus/es/datu-irekien-katalogoa/-/openDataSearcher/detail/detailView/e3a9c1a7-5705-4af7-a8a0-f59525d61f95), que además incluye información geográfica que puede ser relevante en la interpretación de resultados. A partir de estos datos, se pide establecer perfiles de tipos de tráfico utilizando aproximaciones de clustering.

> **Importante**  
> Cada persona tendrá asignada una sola semana del conjunto de datos sobre la que hacer el análisis, que se distribuirá de manera aleatoria a través de la retroalimentación de la tarea del Campus Virtual.

## Normas y estructura

- Esta tarea se hará **Individualmente**.

- Es recomendable que el código esté alojado en un **repositorio git**, ya sea GitHub, GitLab, Codeberg o cualquier otro y que sea accesible para poder evaluarlo.

- El **envío** consistirá en uno (preferible) o varios cuadernos de **Jupyter Notebook bien documentados**, valorando particularmente el uso combinado de código Python y Markdown.

## Procedimiento

En esta sección se explicitan los pasos a dar necesarios para llevar a cabo la prueba satisfactoriamente. Esto no significa que no puedan darse otros pasos similares en sustitución o complementándolos si crees que son adecuados. El orden de los mismos tampoco tiene por qué ser estrictos.

- **Carga de datos**

    - En este caso, los datos están distribuidos entre varios ficheros, así que será necesario combinarlos de manera apropiada en base a la descripción. Cada persona deberá descargarse los datos de su semana asignada a través de los ficheros de retroalimentación del Campus Virtual.

- **Análisis exploratorio**

    - Estudiad los datos, entre qué valores se mueven, qué significa cada campo, cómo están distribuidos, etc.

- **Preprocesamiento**

    - Buscad si hay errores, valores atípicos o elementos similares en el conjunto de datos para ver si podéis limpiarlos en la medida de lo posible.
    - Utilizando técnicas vistas en clase, os recomiendo que trabajéis en reducir el número de características, ya sea mediante selección o reducción de la dimensionalidad.

- **Elección de algoritmo**

    - Seleccionad un algoritmo de clustering para llevar a cabo la agrupación. 
    
    La elección del algoritmo debe estar justificada.

- **Interpretación de resultados**

    - Una vez generados los grupos, es importante analizar qué representa cada uno. Algunas técnicas para poder hacerlo son:
        - Resúmenes (medias, desviaciones, etc.)
        - Visualización mediante PCA, mapas, etc.
    - Esta es la etapa más fundamental de una tarea de clustering, así que se valorará especialmente.
    - Cómo se interpreten los resultados dependerá del algoritmo seleccionado.

## Evaluación

La valoración final de la prueba está formada por:

- Un **15 %** perteneciente a la **segunda prueba de progreso**.
- Un **8 %** perteneciente a las **prácticas de laboratorio**.

En total hace un **23 %** del total de la asignatura que podrá ser recuperado en la convocatoria extraordinaria.

## Envío

Deberá entregarse en el campus virtual un enlace a la carpeta del repositorio donde se encuentre el **cuaderno de Jupyter** (fichero .ipynb) o el fichero en sí mismo.

La fecha límite para el envío será el **15 de abril de 2026**.