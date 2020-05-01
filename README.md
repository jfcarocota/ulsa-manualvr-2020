# Computer Graphic

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

# SHADING

El Shading es el proceso de representación que consiste en calcular el color de los objetos en la escena 3D, todo esto girando en torno al concepto de la luz  de manera virtual.
Al renderizar, estamos interesados ​​en reproducir la forma, la visibilidad y la apariencia de los objetos desde un punto de vista dado. La parte de visibilidad del proceso de renderizado se ocupa de la forma y el problema de visibilidad. El sombreado se ocupa de la estimación o la simulación del color de los objetos como se ve desde un punto de vista dado. El punto de vista aquí juega un papel importante. La apariencia de los objetos puede cambiar con el ángulo de visión. La apariencia de un objeto también depende de algunos parámetros bastante obvios, como la cantidad de luz en la escena, la orientación de las superficies con respecto a las fuentes de luz en la escena, los colores de los objetos, etc. Generalmente, por qué las cosas se ven de la manera en que se ven, tiene mucho que ver con la forma en que la luz interactúa con la materia. Los principios involucrados en este proceso son bastante conocidos hoy y están bien descritos por leyes que generalmente también son fáciles de simular con una computadora. El sombreado se basa en estas leyes para simular la apariencia de los objetos de manera consistente y realista.

Si el objetivo es el foto-realismo, el shading se preocupa por reproducir la apariencia o el aspecto de las superficies reales con un grado de precisión tal que el ojo humano ya no puede notar la diferencia entre mirar una imagen del mundo real y el mundo real en sí mismo. El objetivo de la representación fotorrealista es producir una imagen generada por computadora que se vea real o parezca una fotografía. El shading, que es la parte del proceso de renderizado durante el cual se define la apariencia de los objetos, juega, por supuesto, un papel crítico en el renderizado fotorrealista. En el otro lado del espectro, la representación no fotorrealista (RNF por sus siglas) se ocupa de crear o simular todo tipo de estilos de representación artística. El objetivo de RNF puede ser reproducir técnicas artísticas reales, como la pintura al óleo o acuarela, o desarrollar estilos completamente nuevos que solo pueden explorarse y generarse con computadoras.
