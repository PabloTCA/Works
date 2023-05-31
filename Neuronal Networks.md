# ¿Qué es una red neuronal?
La red neuronal es un método de inteligencia artificial que enseña a las computadoras a procesar datos. Es un tipo de modelo de machine learning el cual está inspirado en la estructura y funcionalidad de los cerebros biológicos. Está compuesto de nodos interconectados, llamados neuronas artificiales o nodos los cuales están organizados en capas.
1. Input Layer (Capa de entrada): La red neuronal toma los datos de entrada, los cuales pueden ser numéricos, imágenes, texto, o cualquier tipo de datos. La capa de entrada consiste en nodos que representa las características o atributos de los datos de entrada.
2.	Hidden Layer (Capa oculta): Esta capa se encuentra entre la capa de entrada y de salida (Input Layer y Output Layer) y puede haber una o mas capas escondidas entre la de entrada y salida. Cada una de estas capas ocultas está compuesta de múltiples nodos, y estas capas son responsables de extraer y transformar características de los datos de entrada. La cantidad de capas ocultas y de sus nodos dentro de cada una de las capas ocultas dependerá de la complejidad del problema que se requiere resolver.
3.	Pesas y funciones de activación: Todas las conexiones entre dos nodos adyacentes tienen una pesa asociada. Las pesas determinan la fuerza de la conexión y son inicialmente asignadas con valores aleatorios. Los datos de entrada son multiplicados por las pesas, pasan por una función de activación, con la cual no introduce linealidades en la red. Las funcione de activación comunes incluyen funciones sigmoid, ReLU y tanh
4.	Output Layer (Capa de salida): La capa final de la red neuronal se llama capa de salida (Output layer). Produce las predicciones de la red o salidas basadas en los datos de entrada procesados. El numero de nodos en la capa de salida depende del problema que se requiere resolver. Por ejemplo, una red neuronal usada para la clasificación de imágenes puede que tenga nodos representando las diferentes clases.
5.	Feedfoward (retroalimentación): La retroalimentación es un proceso en el cual los datos de entrada son propagados a través de la red, desde la capa de entrada hasta la capa de salida. Cada nodo dentro de una capa recibe entradas de la capa anterior, aplica la función de activación a la suma ponderada de sus entradas y mandar el resultado a la siguiente capa.
6.	Función de perdida y retro propagación: Una vez que la red produce sus predicciones, una perdida de funciones se usa para medir la diferencia entre los resultados obtenidos y los resultados esperados. La meta es minimizar la perdida. La retro propagación es el proceso de actualizar las pesas en la red para que se pueda reducir la perdida. Calcula los gradientes de la perdida con respecto a las pesas y ajusta estas mismas usando un algoritmo de optimización, como el descenso de gradiente.
7.	Training (Entrenamiento): La red es entrenada por alimentar iterativamente los datos de entrada a través de la red, Computar la perdida, actualizar las pesas usando la retro propagación. Este proceso continúa por múltiples épocas hasta que la red neuronal mejora su rendimiento y la perdida se minimiza.
8.	Interferencia: Una vez que la red neuronal ha sido entrenada, se puede usar para inferencias o hacer predicciones en nuevos datos de entrada. Los datos de entrada son alimentados en la red neuronal, la capa de salida produce las predicciones de los resultados basado en las pesas de aprendizaje.

Las redes neuronales son capaces de aprender patrones complejos y relaciones en los datos, haciéndolas útiles en un amplio rango de tareas como es el reconocimiento de imágenes, procesamiento de lenguaje natural y modelos predictivos. La eficacia de una red neuronal depende de múltiples factores, incluyendo su arquitectura, tamaño, datos de entrenamiento y los hiper parámetros como el radio de aprendizaje y regularización.
Otras formas de utilizar las redes neuronales son:
•	Diagnostico medico mediante clasificación de imágenes medicas
•	Marketing orientado mediante el filtrado de redes sociales y el análisis de datos de comportamiento
•	Predicciones financieras mediante el procesamiento de datos históricos de instrumentos financieros
•	Previsión de la carga eléctrica y la demanda de energía
•	Proceso y control de calidad
•	Identificación de compuestos químicos
### Visión Artificial
También utilizadas para la visión artificial, la cual es la capacidad que tienen las computadoras para extraer información y conocimientos de imágenes y videos. Con las redes neuronales, las computadoras pueden distinguir y reconocer imágenes de forma similar a los humanos. La visión artificial tiene varias aplicaciones como las siguientes.
•	Reconocimiento visual en los vehículos autónomos para que puedan reconocer las señales de trafico y a otros usuarios del camino
•	Moderación de contenido para eliminar de forma automática los contenidos inseguros o inapropiados de los archivos de imágenes y videos
•	Reconocimiento facial para identificar rostros y reconocer atributos como ojos abiertos, gafas y vello facial
•	Etiquetado de imágenes para identificar logotipos de marcas, ropa equipos de seguridad y otros detalles de la imagen
### Reconocimiento de voz.
Las redes neuronales pueden analizar el habla humana a pesar de los diferentes patrones de habla, el tono, el idioma y el acento.
Los asistentes virtuales como Amazon Alexa, Siri, asistente virtual de Google y el software de transcripción automática utilizan el reconocimiento de voz para realizar tareas como las siguientes.
•	Asistir a los agentes de los centros de llamada y clasificar de manera automatizada las llamadas
•	Convertir en documentación las conversaciones clínicas que se estén llevando acabo en ese momento y en tiempo real
•	Puede traducir y agregar subtítulos con precisión a videos y grabaciones para aumentar su alcance
### Procesamiento de lenguaje natural (PLN)
A través del PLN se puede procesar texto natura, creado por humanos. Las redes neuronales apoyan a las computadoras a conseguir información y significado a partir de datos y documentos de texto.
•	ChatBots y agentes virtuales
•	Organización y clasificación automática de datos escritos
•	Análisis de inteligencia empresarial de documentos con formato largo, como lo son los emails y formularios
•	Indexar frases claves que indiquen sentimientos como comentarios positivos y negativos en las redes sociales.

#### Arquitectura de red neuronal profunda

![arquitectura de red neuronal](https://d1.awsstatic.com/whatisimg/intro-gluon-1%20(1).ac2f31378926b5f99a4ba9d741c4aebe3b7a29e2.png)
 
## Tipos de redes neuronales
### Redes neuronales prealimentadas:
Las redes neuronales prealimentadas procesan los datos en una dirección, la cual es desde el nodo de entrada hasta el de salida.
Todos los nodos de la capa se encuentran conectados con todos los nodos de la siguiente capa. Utiliza un proceso de retroalimentación para mejorar las predicciones a lo largo del tiempo.
### Algoritmo de propagación:
La forma de aprender de las redes neuronales artificiales es de manera continua, usando bucles de retroalimentación correctivos el cual mejorara su análisis predictivo. Recorre el camino de los datos que vienen desde el nodo de entrada hasta el nodo de salida a través de los diferentes caminos que se encuentran en la red neuronal. Como nomas hay un camino correcto la red neuronal usa un bucle de retroalimentación:
1. Cada nodo intenta adivinar el siguiente nodo de la ruta.
2. Se comprueba si la suposición es correcta. Los nodos asignan valores de peso mas altos a las rutas que conducen a mas suposiciones correctas y valores de peso mas bajo a las rutas que conduce a suposiciones incorrectas.
3.	Para el siguiente punto de datos los nodos realizan una predicción nueva con las trayectorias de mayor peso y luego repiten.
### Redes convolucionales
Las capas ocultas en este tipo de redes neuronales realizan funciones matemáticas específicas, síntesis o filtrado, denominadas convoluciones. Esto las hace muy útiles para el reconocimiento y clasificación de imágenes. Es más fácil de procesar sin perder características que son fundamentales para hacer una buena predicción. Cada una de las capas ocultas extrae y procesa diferentes características de la imagen, los bordes, el color y la profundidad.

## Matemáticas y esquema general
Cada conexión neuronal tiene pesos y a estos pesos se les asignara una respectiva “w” ya sea “w1”, “w2” etc. Detrás de estos pesos se encuentra una conexión sináptica que seria en otras palabras la salida de otra neurona. Las salidas de las neuronas le asignamos una variable “y”.
Entonces si asignamos a las conexiones de los pesos de nuestra neurona como “x1, x2…xn” tendremos que: “y=w1x1 + w2x2 + w3x3 + …. + wnxn” esta ecuación es un producto punto y se puede representar en forma vectorial como “y = wx” donde “w” y “x” son vectores. Además, a cada neurona le podemos agregar un offset el cual lo representaremos con b y nos quedaría una ecuación y=w^t x+b
Para poder hacer un procesamiento básico en cascada donde cada neurona se encuentra conectada con otras neuronas, necesitamos que la salida de cada neurona sea una operación no lineal por lo tanto al valor anterior de “y” se le aplicara una función de activación no lineal, entonces la salida de la neurona será una activación y al concatenar muchas neuronas formando una red neuronal profunda el poder de representación será mucho más profundo.

![Matematicas de una neurona](http://www.cs.us.es/~fsancho/images/2019-12/artneur.gif)

### Funciones de activación
La función de activación se elige de acuerdo con la tarea realizada por la neurona, entre las mas comunes de las RNAs podemos ver:

![Funciones de activacion mas comunes](http://www.cs.us.es/~fsancho/images/2019-12/activationfunctions.png)

