#  Inteligencia Artificial - Visión
##  Qué es?
Es un campo de la ciencia relacionado con la creación de computadoras y máquinas que pueden razonar, aprender y actuar de una manera que normalmente requeriría inteligencia humana o que involucra datos cuya escala excede lo que los humanos pueden analizar.

## Como funicona?
Este proceso de aprendizaje suele implicar algoritmos, que son conjuntos de reglas o instrucciones que guían el análisis y la toma de decisiones de la IA. En el aprendizaje automático, un subconjunto popular de la IA, los algoritmos se entrenan con datos etiquetados o no etiquetados para hacer predicciones o categorizar información.

## Visión 
La visión artificial es un campo de la IA que permite que las computadoras y los sistemas obtengan información significativa de imágenes digitales, videos y otras entradas visuales, y tomen acciones o hagan recomendaciones basadas en esa información.

## OpenCV
Es una libreria de código abierto que contiene implementaciones que abarcan más de 2500 algoritmos. Además, está especializada en el sistema de visión artificial y machine learning

## MediaPipe
Es un framework para desarrollar pipelines de ML que permitan procesar series temporales de datos como vídeos o audios. Mediante este framework, se han desarrollado distintas soluciones como detectores de pose, manos, o caras; detección de objetos o segmentación de personas, etc

## Numpy
El término NumPy es la abreviatura de "Numerical Python". Es una libreria de código abierto en Python. Se utiliza para la programación científica en Python, en particular, para la programación en Data Science, la ingeniería, las matemáticas o la ciencia

## Diferencias entre IA Visión, IA NPL e IA LLM
||IA Visión | IA NPL |IA LLM
|--|--|--|--|
| **Objetivo** | permitir que las máquinas interpreten y comprendan imágenes y videos |interacción entre las computadoras y los lenguajes humanos|grandes modelos de lenguaje entrenados en enormes conjuntos de datos de texto
| **Aplicaciones** | detección facial, análisis de imágenes, vigilancia por cámaras, etc |traducción automática, análisis de sentimientos, clasificación de textos, etc|resúmenes automáticos, codificación automática, generación de artículos, etc
| **Técnicas** | procesamiento de imágenes, segmentación de imágenes y detección de bordes |análisis sintáctico, análisis semántico y embeddings de palabras|preentrenamiento y ajuste en grandes cantidades de datos textuales

## Sobre el proyecto


### Función
palm_centroid(coordinates_list): esta funcion calcula el centro de la palma de la mano que se capture por comara

### Captura de video por camara
cap = cv2.VideoCapture(0, cv2.CAP_DSHOW): 