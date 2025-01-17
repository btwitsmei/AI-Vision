#  Inteligencia Artificial - Visión

## Desarrollo conceptual
La Inteligencia Artificial aplicada a Visión le permite a las computadoras a interpretar y procesar imágenes y videos para obtener información significativa y tomar decisiones basadas en esa información. Es una rama de la IA que simula la percepción visual humana a través de algoritmos de aprendizaje automático y técnicas de procesamiento de imágenes. En este caso, no depende de una plataforma o proveedor de servicios de nube, lo que facilita su implementación en cualquier entorno, ya sea local o en la nube.


###  Qué es?
Es un campo de la ciencia relacionado con la creación de computadoras y máquinas que pueden razonar, aprender y actuar de una manera que normalmente requeriría inteligencia humana o que involucra datos cuya escala excede lo que los humanos pueden analizar.


### Como funicona?
Este proceso de aprendizaje suele implicar algoritmos, que son conjuntos de reglas o instrucciones que guían el análisis y la toma de decisiones de la IA. En el aprendizaje automático, un subconjunto popular de la IA, los algoritmos se entrenan con datos etiquetados o no etiquetados para hacer predicciones o categorizar información.


### Visión 
La visión artificial es un campo de la IA que permite que las computadoras y los sistemas obtengan información significativa de imágenes digitales, videos y otras entradas visuales, y tomen acciones o hagan recomendaciones basadas en esa información.


### Beneficios 

- **automatizacion avanzada**: La IA de visión permite la automatización de tareas que requieren análisis visual, como control de calidad, vigilancia, reconocimiento facial, etc.

- **precision**: algoritmos pueden detectar patrones o irregularidades con alta precisión, superando muchas veces la capacidad de percepción humana

- **escalabilidad**: analizar grandes volúmenes de imágenes o videos rápidamente, ideal para aplicaciones en industrias que manejan enormes cantidades de datos visuales.


### Desventajas y limitaciones

- **requisitos de la computadora**: para poder procesar las imágenes y videos a gran escala puede demandar altos recursos de hardware (CPU, GPU) y memoria.

- **datos y calidad de entrenamiento**: si se quiere tener datos precisos, el algoritmo necesita grandes cantidades de datos bien etiquetados para que se entrene correctamente, ya que los datos con baja resolucion pueden afectar el rendimiento

- **denpendencia de calidad de imagen**: el desempeño de los algoritmos de vision dependen mucho de la calidad de las imageneo o videos para el procesamiento de imagen

- **ambiguedad**: en condiciones no optimas (poca luz, angulos inusuales, imabenes borrosas, etc)el algoritmo pueden fallar o producir resultados erróneos


### Alternativas a OpenCV

- **TensorFlow**: Framework usado para machine learning, ofrece una biblioteca complementaria para visión llamada TensorFlow Lite la que facilita la implementación en dispositivos móviles y embebidos (sistema compuesto por una combinación de hardware y software para realizar una función específica)

- **Keras**: Usa TensorFlow como backend y ofrece una API simplificada para trabajar con redes neuronales, incluyendo modelos preentrenados para visión como VGG16 o ResNet.

- **PyTorch**: Competencia directa de TensorFlow, ofrece herramientas avanzadas para construir y entrenar modelos de visión artificial a gran escala, como la biblioteca Torchvision

- **Dlib**: Librería enfocada en el reconocimiento facial y machine learning, ofreciendo algoritmos preentrenados de alta precisión para detección y seguimiento de rostros


### Razones por las cuales se utilizo OpenCV

es una de las opciones más populares y eficientes para el procesamiento de imágenes

- **versatilidad**: cubre una amplia gama de funcionalidades, desde la manipulación básica de imágenes hasta técnicas avanzadas de visión por computadora

- **Soporte de la comunidad**: tiene una amplia comunidad y el soporte de documentación facilitan su uso en una variedad de proyectos

- **Rendimiento optimizado**: desarrollado en C/C++ con optimizaciones para su uso con GPUs, lo que lo hace eficiente para aplicaciones de visión en tiempo real

- **Integracion sencilla**: compatible con muchas otras herramientas y frameworks de IA, como TensorFlow o PyTorch, lo que facilita combinar procesamiento de imágenes con modelos de deep learning


### Diferencias entre IA Visión, IA NPL e IA LLM

||IA Visión | IA NPL |IA LLM
|--|--|--|--|
| **Objetivo** | permitir que las máquinas interpreten y comprendan imágenes y videos |interacción entre las computadoras y los lenguajes humanos|grandes modelos de lenguaje entrenados en enormes conjuntos de datos de texto
| **Aplicaciones** | detección facial, análisis de imágenes, vigilancia por cámaras, etc |traducción automática, análisis de sentimientos, clasificación de textos, etc|resúmenes automáticos, codificación automática, generación de artículos, etc
| **Técnicas** | procesamiento de imágenes, segmentación de imágenes y detección de bordes |análisis sintáctico, análisis semántico y embeddings de palabras|preentrenamiento y ajuste en grandes cantidades de datos textuales


## Consideracikones tecnicas

Se detallan las principales herramientas y consideraciones técnicas necesarias para trabajar con IA de visión. En este caso se trabajo en Python con diversas librerias open source


### OpenCV:

Libreria de código abierto especializada en visión artificial que incluye más de 2500 algoritmos. Se puede usar tanto para el preprocesamiento de imágenes como para la detección de objetos y reconocimiento facial.

> Para configurar OpenCV, es necesario instalar las dependencias correspondientes con el comando </br> 
> pip install opencv-python


### MediaPipe

framework diseñado para procesar series de datos como videos, con soluciones preconstruidas para la detección de rostros, manos y poses corporales. Al installarlo habilita la creación de pipelines de procesamiento de video y análisis de imágenes.

> La configuración de MediaPipe se realiza mediante </br> 
> pip install mediapipe


### NumPy

Biblioteca esencial para el cálculo numérico y científico en Python. Se utiliza en conjunto con OpenCV para operaciones matemáticas eficientes sobre matrices de imágenes. 

> Para su instalación correr el comando </br>
> pip install numpy


> si se quiere intalar todos de una vez correr esta linea </br> 
> pip install opencv-python mediapipe numpy


## Link de la demo

https://youtu.be/ovcgCNWP5NQ


[en ingles](https://github.com/btwitsmei/AI-Vision/blob/main/README(ENG).md)