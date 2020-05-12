# ABSTRACT
<p align="justify">El siguiente documento es un manual de usuario de la tecnología VR Daydream, el cual contiene información sobre los conceptos de la Realidad Virtual, Realidad  Aumentada y Realidad Mixta, la Realidad Extendida (XR, por su siglas en inglés), contiene su propia definición, los antecedentes de cada uno de estos conceptos, también incluye contenido sobre  Computer Graphics y Shading. Además en este manual encontrarás una serie de pasos para poder configurar desde cero el casco para realidad virtual y los controles para VR de la misma manera que preparar el software de la computadora para poner en funcionamiento estos mismos.
Este documento contiene software, plataformas y herramientas para realizar realidad aumentada, así como librerías de realidad mixta, también tiene una sección de las aplicaciones actuales de la realidad mixta en los campos laborales (Educación, salud, etc).
En el tema de Computer Graphics se presentan las diversas librerías de OpenGL, cada una con una pequeña introducción a estas tecnologías. En Shading se muestran sus conceptos básicos y/o características. </p>

<p align="justify">También podrá encontrarse un apartado que contiene información general del visor en específico que se utilizará para el desarrollo, la definición de Daydream (la tecnología detrás del visor), el cual nos permite ver aplicaciones en Realidad Virtual  y el Motor Gráfico que se usará en cuestión, Unity, para crear aplicaciones y los pasos para enviarlas al visor para poder desarrollar de una manera más efectiva.</p>

# INTRODUCCIÓN
<p align="justify">El siguiente manual se centra en ver y entender los diversos tipos de disciplinas de simulación en tiempo real que pueden existir, ya sea la Realidad Virtual (se centra en dar la impresión al usuario de estar inmerso en un mundo completamente virtual), la Realidad Aumentada (combina los elementos físicos tangibles con elementos virtuales), como también la combinación de ambas conocida como la Realidad Mixta, encontraremos también las características y diferencias entre cada una de estas. Así como también entender la definición de los Computer Graphics y descubrir el proceso detrás de esto, como también las técnicas de el manejo y control de la iluminación virtual de la que se encarga el apartado Shading. </p>

<p align="justify">Por consiguiente este manual será de mucha ayuda para apoyar a los diferentes usuarios, el cual tiene un enfoque especial en que sea entendible para la mayor cantidad de personas posible que quieran aprender a utilizar los cascos de Realidad Virtual, facilitandoles el procedimiento estableciendo una serie de pasos en los que se explica detalladamente desde como configurar el visor de realidad virtual Lenovo Mirage Solo VR hasta instalar aplicaciones hasta desarrollarlas desde la plataforma de gráficos por computadora Unity.</p>
<p align="justify">Alrededor de 1960 la agitación de la guerra fría y las ideas de la utopía marcaron el futurismo robótico y nuevos horizontes respecto a los paradigmas tecnológicos. La tecnología en el siglo XX veía más allá del tiempo mismo e idealizaban la idea de poder recrear cerebros electrónicos. La inteligencia artificial se desempeñaba en computadores colosos de transistor cuya memoria no superaba la de una calculadora de 1990. El máximo exponente de la Proto Inteligencia Artificial era el TC-2 el MIT de la EE.UU. Sin embargo en este armatoste computacional que se remonta a los años 60 trajo a la luz los primeros gráficos por ordenador. (Mario Viciosa, 2019) </p>
<p align="justify">Los primeros cascos de realidad virtual. Los primeros pencil sobre pantallas. Todo eso se coció en la mente de Ivan Sutherland hace más de medio siglo. Así trabajaba este informático en el laboratorio Lincoln del MIT en los sesenta y así trabaja en la actualidad. A sus 80 años, sigue rodeándose de jóvenes a los que escucha atentamente para poder saber por dónde irá el futuro. (El Independiente, 2019)
Sutherland es conocido como el padre de los gráficos por ordenador. Pero también como el pionero de los cascos de realidad virtual. Inventó el primer prototipo de Óculos para realidad virtual. </p>
<p align="justify">Dando clases en Harvard, visité a Bell Helicopter. El tenían unos cascos para poder ver en infrarrojo, gracias a una camarita que tenían en el techo. Se me ocurrió que podían sustituir la cámara por un ordenador y fabricar un mundo sintético que reprodujese un tipo de realidad. (Sutherland) </p>


# Gráficos por computadora

Las computadoras no solo empezaron a aparecer en los hogares, sino    que también mejoraron significativamente en cuanto a rendimiento,    potencia del procesador, memoria y almacenamiento, lo que permitió    que se crearan terminales con una mejor resolución para desplegar    gráficos por computadora, que además fueron evolucionando para entrar    a equipos más poderosos en lugar de mantenerse en las computadoras de    trabajo o de hogar. Los equipos se comenzaron a volverse inteligentes    y más autónomos, lo que permitió un crecimiento acelerado en el área,    por otra parte, las computadoras que se desarrollaban en esta década    contaban con una interfaz gráfica de usuario, lo cual se convirtió en    la base de la tecnología multimedia.

## OpenGL

**OpenGL** (Open Graphics Library) es un estándar que define una multiplataforma y API multilenguaje para las aplicaciones gráficas de 2D y 3D. Su interfaz se utiliza con más de 250 funciones para usarse para dibujar escenas tridimensionales complejas a partir de primitivas geométricas, líneas, triángulos. Originalmente fue desarrollado por Silicon Graphics Inc. (SGI) en 1992. En la realidad virtual, también se utiliza para desarrollo de videojuegos. OpenGL tiene varias librerías como:

**Librerías de crear y administrar ventanas OpenGL**
**Librería GLUT**: Fue creado por Mark J. Kilgard Es un interfaz programado en el lenguaje de programación C, ANSI y Fortran para poder escribir en OpenGL.

Las librerías ofrecen:
-   Librerías múltiples para render.
-   Procesamiento de eventos de entrada iniciado por el usuario (Callbacks).
-   Variados dispositivos de entrada.
-   Menús desplegables.
-   Rutinas para generar objetos estándares.

**Librería GLFW**:  Es una librería multiplataforma en código abierto para el desarrollo de OpenGL en escritorio. donde proporciona una API simple para crear ventanas, entradas y contexto, está escrito en el lenguaje de programación C.

  
**Librería FreeGlut**:  Fue creado en 1 de diciembre en el año 199 por Pawel W. Olszta con cooperación de Andreas Umbach y Steve Baker, pero John F.Fay, John Tsiombikas y Diedercik C. Niehorster con los que mantienen vivo la librería freeglut, Es un software libre de código abierto de OpenGL de GLUT, se encarga en hacer todas las tareas específicas del sistema necesariamente para crear ventanas para poder permitir programas OpenGl para que seas totalmente portátiles.

#### Librerías multimedia de OpenGl para poder crear ventanas, entradas, sonidos, y otras tareas útiles para la realización, por ejemplo, de un videojuego.

**Libreria Allegro**: Es un Software libre creado en 1990 por Shawn Hargreaves, va dirigido como una multiplataforma a los videojuegos y programación multimedia (2D y 3D) diseñada para usarse como C, C++ y Objective-C, donde maneja tareas de bajo nivel, para crear ventanas, entrada de usuario, cargar datos, dibujar, sonidos, ya que es un motor de juegos, donde puedes diseñar y estructurar los programas.

**Librería SDL(Simple DirectMedia Layer)**: Es creado por Sam Lantinga en 1998, es una desarrollo de software multiplataforma capaz de abstraer de hardware para hacer un componente de hardware multimedia de computadora, puede usarlo para escribir juegos de computadora de alto rendimiento en muchos sistemas operativos, se utiliza video, audio, hilos, objetos compartidos, redes y temporizadores, ya que mencionan un error común en SDL, donde mencionan que es un motor de juegos pero es incorrecto, donde es una biblioteca adecuada para crear juegos directamente o indirectamente construirlos encima de ellos. La biblioteca está construida por C, y dependiendo de la plataforma C ++ y Objective-C.

**Librería SFML(Simple and Fast Multimedia Library)**: Es una librería recientemente creada por Laurent Gomila en 2007, es una plataforma diseñada para la programación de aplicaciones (API) con varios componentes multimedia. Es en lenguaje C++ con enlaces C. Se maneja por creaciones de ventanas y la creación de administracion, ya que también proporciona un módulo de gráficas aceleradas de hardware de computadoras 2D.

Al paso de los años la tecnología evoluciona las universidades tienen que cambiar su método de enseñanza se caracterizan por medio de estrategias y enfoque del aprendizaje, ya que se necesita esfuerzo, energía y creencias sobre la capacidad para aprender nuevos métodos de tecnología a los videojuegos, se encuentra lo necesario par ala ejecución de las aplicación mediante una máquina virtual y el sistema está optimizado para que se ejecuten múltiples instancias, donde también se puede desarrollar java, donde las universidades les enseñan la programación básica C, C++ y hasta su arquitectura, ya que esto está diseñada para simplificar los componentes de cualquier aplicación para su capacidad de usuario. Las universidades uno de los básicos de OpenGl, uno de los básicos de creación de videojuegos.

# REALIDAD VIRTUAL

La Realidad Virtual (Siglas en inglés VR) es un entorno de escenas y objetos de
apariencia real generado mediante tecnología informática que crea en el usuario la
sensación de estar inmerso en él, conocido como gafas o casco de realidad virtual.

Todo comenzó con el Sensorama, un simulador multisensorial, creado por Morton
Heilig entre 1960 y 1962. Se trataba de una película pregrabada en color y estéreo,
que fue completada con un sonido binaural, con olor, con viento y con experiencias
añadidas de vibración en el asiento.

Éste fue el primer acercamiento en la creación de un sistema de realidad virtual con
todas las características de un ambiente virtual, aunque no era interactivo.
En 1965, Ivan Sutherland propuso la solución definitiva para crear realidad virtual:
un concepto de construcción artificial del mundo real, que incluía gráficos
interactivos, retroalimentación de fuerza, sonido, olfato y gusto. A este concepto se
le llamó The Ultimate Display.
La Espada de Damocles fue el primer sistema de RV realizado sobre hardware, no
solo como un concepto. Ivan Sutherland construyó un dispositivo considerado como
la primera pantalla montada en la cabeza (Head Mounted Display, HMD), con un
adecuado seguimiento de ésta a tiempo real. La imagen estaba contemplada por
una vista estéreo que se actualizaba correctamente de acuerdo con la posición de la
cabeza del usuario y su orientación.
La realidad virtual ha evolucionado desde los años 60 hasta la actualidad.
Gracias a esta tecnología, podemos sumergirnos en videojuegos como si fuéramos
los propios personajes, aprender a operar un corazón o mejorar la calidad de un
entrenamiento deportivo para obtener el máximo rendimiento.
Para mejorar estas experiencias, se puede hacer el uso de otros dispositivos como
sensores de movimiento, audífonos, guantes, etc.
Estos dispositivos son tan inmersivos que privan parcial o totalmente el sentido de la
vista del usuario, poniendo en riesgo la integridad del mismo y otros individuos a su
alrededor.
Para evitar esto, algunos dispositivos actuales cuentan con detectores de
movimiento, que marcan los límites del área permitida para la libre movilidad:
cuando el usuario llega a estos límites definidos por el dispositivo y los cálculos
constantes durante el movimiento, al usuario se le informa que se encuentra fuera
de la zona segura y así se puedan evitar accidentes.

# REALIDAD AUMENTADA

La realidad aumentada (siglas en inglés AR) nos permite añadir capas de información visual
sobre el mundo real que nos rodea, utilizando la tecnología, dispositivos como pueden ser
nuestros propios teléfonos móviles. Esto nos ayuda a generar experiencias que aportan un
conocimiento relevante sobre nuestro entorno, y además recibimos esa información en tiempo real.

Al contrario de la realidad virtual, la Realidad Aumentada no es inmersiva y su
visualización e interacción es a través de un dispositivo que cuenta con una cámara,
mostrando así el entorno real, pero mostrando elementos gráficos inexistentes
superpuestos en dicho entorno. Con estos dispositivos también se logra una
interacción a través de una interfaz y funciones del mismo dispositivo como el gps,
giroscopio, etc.
Debido a que esta experiencia no es totalmente inmersiva, no es necesario
medidas de seguridad o dispositivos que detecten nuestra zona segura ya que el

usuario siempre se encuentra y cuenta con la noción suficiente para detectar que
aún se encuentra en el entorno real.

Mediante la realidad aumentada, el mundo virtual se entremezcla con el mundo real, de manera
contextualizada, y siempre con el objetivo de comprender mejor todo lo que nos rodea.

Hay diversos tipos de realidad aumentada dependiendo del objetivo final que se busque, y sobretodo,
de los componentes del mundo real que entren en juego.

**Imágenes
Cualquier imagen es válida para colocar contenido de Realidad Aumentada sobre ella.
En el pasado se utilizaban comúnmente elementos predefinidos, conocidos como "Markers", con
apariencias similares a las de un código QR.

Ahora, gracias a las nuevas tecnicas de clasificación de imágenes, la realidad aumentada es
mucho más natural, pudiendo utilizarse cualquier elemento del entorno, como el logo de una empresa,
una tarjeta de visita, la carta de un restaurante, o el mapa turístico de una ciudad, por citar algunos
ejemplos.

**Espacios
La Realidad Aumentada está en continua evolución, tanto es así que hoy en día existen dispositivos que
nos permiten reconocer cualquier estancia, habitación o espacio donde estemos situados; y además reconocer
y memorizar la posición de las capacidades físicas el entorno: paredes, techos, suelo, muebles, etc.

**Lugares
La Realidad Aumentada está en continua evolución, tanto es así que hoy en día existen dispositivos 
que nos permiten reconocer cualquier estancia, habitación o espacio donde estemos situados; y además
reconocer y memorizar la posición de las capacidades físicas el entorno: paredes, techos, suelo, muebles, etc.

# Shading

El Shading es el proceso de representación que consiste en calcular el color de los objetos en la escena 3D, todo esto girando en torno al concepto de la luz  de manera virtual.
Al renderizar, estamos interesados ​​en reproducir la forma, la visibilidad y la apariencia de los objetos desde un punto de vista dado. La parte de visibilidad del proceso de renderizado se ocupa de la forma y el problema de visibilidad. El sombreado se ocupa de la estimación o la simulación del color de los objetos como se ve desde un punto de vista dado. El punto de vista aquí juega un papel importante. La apariencia de los objetos puede cambiar con el ángulo de visión. La apariencia de un objeto también depende de algunos parámetros bastante obvios, como la cantidad de luz en la escena, la orientación de las superficies con respecto a las fuentes de luz en la escena, los colores de los objetos, etc. Generalmente, por qué las cosas se ven de la manera en que se ven, tiene mucho que ver con la forma en que la luz interactúa con la materia. Los principios involucrados en este proceso son bastante conocidos hoy y están bien descritos por leyes que generalmente también son fáciles de simular con una computadora. El sombreado se basa en estas leyes para simular la apariencia de los objetos de manera consistente y realista.

Si el objetivo es el foto-realismo, el shading se preocupa por reproducir la apariencia o el aspecto de las superficies reales con un grado de precisión tal que el ojo humano ya no puede notar la diferencia entre mirar una imagen del mundo real y el mundo real en sí mismo. El objetivo de la representación fotorrealista es producir una imagen generada por computadora que se vea real o parezca una fotografía. El shading, que es la parte del proceso de renderizado durante el cual se define la apariencia de los objetos, juega, por supuesto, un papel crítico en el renderizado fotorrealista. En el otro lado del espectro, la representación no fotorrealista (RNF por sus siglas) se ocupa de crear o simular todo tipo de estilos de representación artística. El objetivo de RNF puede ser reproducir técnicas artísticas reales, como la pintura al óleo o acuarela, o desarrollar estilos completamente nuevos que solo pueden explorarse y generarse con computadoras.

