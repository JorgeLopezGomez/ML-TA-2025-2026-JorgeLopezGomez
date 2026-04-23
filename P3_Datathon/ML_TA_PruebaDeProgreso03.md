# Técnicas de Aprendizaje Automático 2025/2026 

## Prueba de progreso 3: Competición de datos sobre predecir el daño de terremotos

Una **Datathon** es una competición de análisis de datos en la que habitualmente suele haber rankings e incluso premios. Participa en la Datathon sobre el impacto que tienen los terremotos en edificios de la plataforma [DrivenData](https://www.drivendata.org/competitions/57/nepal-earthquake/) (esta no tiene premio) y documenta el proceso usando un **cuaderno de Jupyter**. Parte de la evaluación dependerá de la puntuación alcanzada en la competición.

## Procedimiento

En esta práctica no tendréis una serie de pasos indicada para llevar a cabo el análisis, pero sí que tenéis que seguir una serie de pasos para poder participar en la competición:

1. [Crearse una cuenta en DrivenData](https://www.drivendata.org/accounts/signup/) y unirse a la [competición](https://www.drivendata.org/competitions/57/nepal-earthquake/) pulsando el botón de "Compete".

2. (Opcional, pero muy recomendado) Consultar la [descripción del problema](https://www.drivendata.org/competitions/57/nepal-earthquake/page/136/) para entender bien cómo trabajar con estos datos. En general es recomendable que miréis bien todas las secciones de la competición.

3. [Descargar los datos](https://www.drivendata.org/competitions/57/nepal-earthquake/data/). Tenéis datos de entrenamiento, datos de prueba y un ejemplo del formato de envío.

4. Entrenar un modelo y **generar una predicción** sobre los datos de prueba.

5. **Realizar el envío** de los datos a través de la plataforma usando el formato explicado en la misma. Tened en cuenta que podéis hacer hasta 3 envíos al día, por lo que es recomendable que no hagáis envíos que no creáis que puedan mejorar lo anterior. Aquí tendréis que iterar continuamente entre los pasos 4 y 5.

## Consejos

A continuación tenéis una serie de consejos que os pueden ayudar a enfrentar la competición:

- Es un conjunto de datos con **bastantes filas y columnas**, por lo que, para entrenar rápido a los modelos y poder iterar ágilmente, habrá que reducir características o parametrizar modelos para que sean más eficientes.

- **Probad** varios tipos de modelos para conseguir buenos resultados.

    - Documenta (al menos en Markdown) los modelos que has ido probando y descartando.

- **Evaluad el modelo** en local antes de llevar a cabo la predicción.

    - Es una forma de hacer pruebas en local que no están limitadas, al contrario que los envíos que solo pueden hacerse 3 al día.
    - Tened en cuenta que es muy probable que haciendo particiones de los datos de entrada funcione mejor que con las etiquetas a predecir o que el modelo mejore con los datos de prueba extraídos del dataset original, pero empeore con los datos objetivo.

- Considera que se trata de un problema de **clasificación ordinal** (como el de los vinos) por lo que es posible solucionarlo usando tanto técnicas de regresión como de clasificación.

## Normas y estructura

- Esta tarea se hará **Individualmente**.

- Es recomendable que el código esté alojado en un **repositorio git**, ya sea GitHub, GitLab, Codeberg o cualquier otro y que sea accesible para poder evaluarlo.

- El **envío** consistirá en uno (preferible) o varios cuadernos de **Jupyter Notebook bien documentados**, valorando particularmente el uso combinado de código Python y Markdown.

  - Será necesario indicar el usuario y posición en el ranking al principio del cuaderno.

## Evaluación

La valoración final de la prueba está formada por:

- Un **27,5 %** perteneciente a la **tercera prueba de progreso**.
- Un **9 %** perteneciente a las **prácticas de laboratorio**.

En total hace un **36,5 %** del total de la asignatura que podrá ser recuperado si hace falta.

## Envío

Deberá entregarse en el campus virtual un enlace a la carpeta del repositorio donde se encuentre el **cuaderno de Jupyter** (fichero .ipynb) o el fichero en sí mismo.

La fecha límite para el envío será el **18 de mayo de 2026**.