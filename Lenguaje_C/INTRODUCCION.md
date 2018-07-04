# Introduccion

<p align="justify">
Antes de iniciar nuestra aventura en el mundo de la programacion con el lenguaje C de la mano con el libro referencia <b>C Primer Plus 6th</b>. Realizaremos una introduccion basada en el contenido del primer capitulo de nuestro libro de referencia (Como recomendacion usar el libro antes nombrado para tener un mayor contenido de aprendizaje). En esta parte traremos los siguentes temas:
</p>

1. Breve historia y caracteristicas
2. Pasos para escribir un programa en C
3. Un poco sobre compiladores y linkers
4. Estandares de C
5. Keywords

<p align="justify">
C es un lenguaje de programación creado en 1972 por Dennis M. Ritchie en los Laboratorios Bell. Es un lenguaje orientado a la implementación de Sistemas Operativos, concretamente Unix. C es apreciado por la eficiencia del código que produce y es el lenguaje de programación más popular para crear software de sistemas, aunque también se utiliza para crear aplicaciones.  Se trata de un lenguaje débilmente tipificado de medio nivel pero con muchas características de bajo nivel. Dispone de las estructuras típicas de los lenguajes de alto nivel pero, a su vez, dispone de construcciones del lenguaje que permiten un control a muy bajo nivel. Los compiladores suelen ofrecer extensiones al lenguaje que posibilitan mezclar código en ensamblador con código C o acceder directamente a memoria o dispositivos periféricos. se pueden desarrollar compiladores de C fácilmente. En consecuencia, el lenguaje C está disponible en un amplio abanico de plataformas (seguramente más que cualquier otro lenguaje). Además, a pesar de su naturaleza de bajo nivel, el lenguaje se desarrolló para incentivar la programación independiente de la máquina. Un programa escrito cumpliendo los estándares e intentando que sea portátil puede compilarse en muchos computadores.
C se desarrolló originalmente (conjuntamente con el sistema operativo Unix, con el que ha estado asociado mucho tiempo) por programadores para programadores. Sin embargo, ha alcanzado una popularidad enorme, y se ha usado en contextos muy alejados de la programación de sistemas, para la que se diseñó originalmente
</p>

<p align="justify">
Tambien cabe decir que el lenguaje C incorpora las caracteristicas necesarias para la teoria y la practica de las ciencias de la computacion (planeamiento <i>top-down, programacion estructurada, diseño modular</i>). C tiene la versatibilidad de permitir escribir codigo para procesadores de 8 bits o para procesadores de supercomputadoras pero hay que tener en cuenta que si se realiza un codigo para un sistema operativo especifico (sea linux o windows o etc) sera un poco complicado que existe compatibilidad entre en las dos plataformas (por que los binarios generados para cada sistema son diferentes, y las funciones que se usan del api cambian).
</p>

<p align="justify">
El lenguaje C brind una gran libertad (no tanto como Ensamblador) al desarrollador en poder hacer ciertas cosas que en otros lenguajes no se podria hacer y esta libertad con lleva una gran resposabilidad, dado que nos permite tener acceso al hardware y al sistema operativo. Los errores que aveces se pueden encontrar programando son algunas veces dificil de encontrar (por ejemplo usando punteros) y con esto vamos a <b>"El precio de la libertad es una eterna vigilancia"</b>.
</p>

<p align="justify">
A veces leer codigo en C es muy dificil y poder seguirle el paso es muy dificil, pero ese es uno de los retos de C por algo anualmente se hacia un contest de codigo ofuscado.
</p>
<p align="center">
<img src="imagenes/ioccc.png"><br>
https://www.ioccc.org/
</p>

<p align="justify">
<b>C != C++ (y otros intentos de sabores de C)</b>. Cuando programamos en C++ programamos sin tener fundamentos de C puro, caemos algunas veces en la programacion por cajas negras, sabemos usar ciertas funciones predefinas por el lenguaje y sus librerias pero en realidad solo sabemos que entran ciertos parametros y salen ciertos procesamientos, con C tenemos todo el conocimiento del funcionamiento de las cosas al frente de nosotros y nos obliga a estar en constante evolucion. Con esto concluimos que aprendiendo C nuestra curva de aprendizaje de otro lenguaje sera mucho mas rapida y a parte de esto C es y sera uno de lenguajes mas usados y poderosos del mercado. C tiene diferentes aplicaciones y formas de uso, todo depende del enfoque que se le da al lenguaje aprovechando todas las caracteristicas del mismo.
</p>

<p align="center">
<img src="imagenes/aplicaciones.png" height="250">
</p>

## Entendimiento de la computadora

<p align="justify">
Para poder programar en C, se debe tener un entendimiento de las funciones de la computadoras un poco. empezando por los componentes que tiene:
</p>

1. CPU (Cental Unit Process)

<p align="center">
<b>Creacion de un procesador - Intel</b><br>
[![Creacion de un procesador - Intel](https://img.youtube.com/vi/d9SWNLZvA8g/0.jpg)](https://www.youtube.com/watch?v=d9SWNLZvA8g)
</p>

<p align="center">
<b>Decapping de varios procesadores</b><br>
<img src="imagenes/pro_inside.jpg" height="250">
</p>

<p align="center">
<b>Simulador de procesador - www.visual6502.org/JSSim</b><br>
<img src="imagenes/simulador.jpg" height="250">
</p>

<p align="center">
<b>Vista basica en diagramas de bloques</b><br>
<img src="imagenes/bloques.gif" >
</p>

<p align="center">
<b>Vision general</b><br>
<img src="imagenes/mezcla.png" height="500">
</p>

2. RAM (Random Access Memory)

<p align="center">
<b>Vision fisica de memoria RAM</b><br>
<img src="imagenes/ram.jpg" height="350">
</p>

<p align="center">
<b>Vision interna de memoria RAM</b><br>
<img src="imagenes/ram2.jpg" height="250">
</p>

3. Almacenamiento (Usb, HardDrive, Etc)
<p align="center">
<b>Disco Duro</b><br>
<img src="imagenes/hardrive.png" height="500">
</p>

4. Perifericos (Medios de entrada y salida de datos)

<p align="center">
<b>Partes de una MotherBoard</b><br>
<img src="imagenes/board.jpg" height="500">
</p>

## Alto nivel y compiladores

# Referencias
1. https://www.ecured.cu/Historia_del_Lenguaje_C
2. http://www.righto.com/2016/01/counting-bits-in-hardware-reverse.html
3. http://www.instructables.com/id/How-to-expose-the-die-contents-of-an-old-CPU/
4. https://www.quora.com/What-are-the-best-open-source-CPUs
5. https://wikimedia.org
6. https://blog.dell.com/en-us/laptop-hard-drive-failure-prevention-101/
