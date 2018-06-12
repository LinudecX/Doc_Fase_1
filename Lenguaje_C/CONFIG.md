# Configuracion de ambiente de desarrollo

<p align="justify">
Antes de empezar con todo el estudio del lenguaje C, debemos realizar la configuracion de nuestro ambiente de trabajo, abordaremos tres formas de poder trabajar con el lenguaje C. Se empezara documentando cada una de las tres formas de poder compilar y trabajar el lenguaje C (aunque existen mas). Dentro de las tres formas que se explicaran aqui, se dara pie para que los recien llegados a Gnu/Linux no les quede tan dificil la transicion a este sistema operativo, dando la oportunidad de que la persona que lea este material sea capaz de escoger alguna de las tres (de acuerdo a su experiencia o si quiere experimentar, que pueda hacerlo).
</p>

<p align="jusfity">
Esta claro que el uso de un IDE (Entorno Integrado de desarrollo) facilita la vida del desarrollador realizando muchas cosas por el (configuraciones, etc, etc), pero lo ideal es que el desarrollador primero conozca bien su forma de trabajar(compilando, generando codigo obj, incluyendo librerias, compilar sus propias librerias, debuggeando, etc) y luego si pase a un IDE. Ya que con esto no crearia dependencia aun solo IDE, si no que seria capaz de migrar algun IDE en algun momento y que la curva del aprendizaje sea mucho mas rapida. 
</p>

<p align="justify">
En esta primera fase no se abordara el uso de los archivos make, solo se enfocara en la programacion del lenguaje C, En llegado caso de ser necesitado se hablara de ello y se daran algunos ejemplos basicos, en la segunda fase se profundizara mucho sobre esto( http://calcifer.org/documentos/make/ ) ya que los IDE de C por debajo tienen este mecanismo que ayuda mucho en el desarrollo de proyectos grandes
</p>

## Instalacion de compilador y herramientas necesarias(Linux)

Para instalar GCC (que sera nuestro compilador de trabajo) debemos realizar ejecutar el siguente comando:

```bash
sudo apt-get install build-essential
```
<p align="center">
<img src="imagenes/gcc_install.jpg">
</p>

<p align="justify">
Estamos instalando por medio de los repositorios de ubuntu todo el paquete necesario para poder compilar con el gcc(compilador para lenguaje C) y el g++(compilador para c++) este paquete se llama build-essential. Aparte de esto nos incluye otros paquetes necesarios o que le dan una funcionabilidad mas (por ejemplo el dpkg-dev es usado para crear paquetes de nuestros programas para la instalacion).
</p>

<p align="justify">
Ahora vamos a comprobar la instalacion del compilador gcc que vamos a usar para poder compilar nuestros programas en C y verificar la version. 
</p>

```
gcc --version 
```

<p align="center">
<img src="imagenes/gcc_checked.jpg">
</p>

<p align="justify">
Con esto ya tenemos nuestro compilador basico para poder empezar a trabajar, idenpendiente de que forma se escoja.
</p>

## Configuracion de IDE o de formas alternativas de trabajo

### CodeBlocks

<p align="center">
<img src="imagenes/codeblocks_logo.png">
</p>

<p align="justify">
Codeblocks es un IDE libre, que esta liberado bajo la licencia(GPL v3). Creado por la gran demanda de usuarios. Es un IDE multiplataforma (puede ejecutarse en Linux, Mac, Windows), esta escrito en C++ sin lenguajes interpretados ni con librerias propietarias. Soporta una gran variedad de compiladores, es rapido y personalizable, brinda soporte para usar diferentes nucleos, permite realizar cross compiling(para circuitos integrados avr, arm y otro. Brinda una gran indepencia de proyectos(aislamiento).
</p>

<p align="justify">
Permite realizar Debugging por medio de una interface a GDB (GDB es un programa que permite depurar nuestros programas para encontrar erores o para comprender como se comporta el binario). 
</p>

#### Instalacion 

```bash
sudo apt-get install codeblocks
```
<p align="center">
<img src="imagenes/codeblocks_install.jpg"
</p>

<p align="justify">
Despues de ejecutar el comando de instalacion (asi tal cual como lo hicimos con el compilador gcc) codeblocks instalara las dependencias que necesitara para ejecutarse y quedara instalado dentro de nuestro equi, en xubuntu lo podran buscar en el menu y en el submenu "Desarrollo" o "Programacion" con el icono de una palita, o tambien podrian llamarlo desde una terminal de comandos solo escribiendo codeblocks.
</p>

#### Primera vista y algunas configuraciones

<p align="center">
<img src="imagenes/first_run.jpg">
</p>

<p align="justify">
Al ejecutar nuestro ide, nos mostrar una lista de los compiladores que ha detectado sobre nuestra maquina, como podemos ver el listado de compiladores que soporta codeblocks es bastante amplio, pero como solo nosotros usaremos gcc por ahora, ese sera el que seleccionaremos y lo setearemos por default.
</p>

<p align="center">
<img src="imagenes/view_ide.jpg">
</p>

<p align="justify">
Nos encontraremos con esta primera vista. Desde aqui podriamos antes de sentarnos a tirar miles y miles lineas  de codigo debemos realizar una preconfiguraciones para trabajar un poco mas comodos.
</p>

<p align="center">
<img src="imagenes/compiler_codeblocks">
</p>

<p align="justify">
Primeramente entraremos a las configuraciones del compilador para verificar que todo este bien, en este primera imagen se puede apreciar que el compilador gcc tiene diferentes opciones de compilacion(igual esto se ira viendo sobre la marcha y se profundizara en la segunda fase de la mano con make) por ejemplo si queremos compilar para que el binario se ejecute en maquinas con arquitectura de 32 bits o de 64 bits, normalmente se targetea  a maquinas de 32 ya que en algunos casos cuando se ejecuta un binario para una maquina de 32 bits en una maquina de 64 bits puede que exista la compatibilidad y se ejecute.
</p>

<p align="center">
<img src="imagenes/file_compiling.jpg">
</p>

<p align="justify">
En la ventana "Toolchain executables" podremos ver que ejecutables estan cargados para realizar la tarea de compilacion, si vemos bien el mensaje en rojo vemos que nos esta definiendo que la mayoria de programas deben existir en la ruta /usr/bin/[aqui-los-programas]. Y ejecutamos desde la consola "ls -a /usr/bin" podemos encontrar todos los binarios alli, hasta los binarios del sistema.  
</p>


### Sublime + Pluggins

### Vim + Some Weird Stuff

## Referencias


