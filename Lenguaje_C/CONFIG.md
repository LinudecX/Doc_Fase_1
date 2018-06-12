# Configuracion de ambiente de desarrollo

<p align="center">
Antes de empezar con todo el estudio del lenguaje C, debemos realizar la configuracion de nuestro ambiente de trabajo, abordaremos tres formas de poder trabajar con el lenguaje C. Se empezara documentando cada una de las tres formas de poder compilar y trabajar el lenguaje C (aunque existen mas). Dentro de las tres formas que se explicaran aqui, se dara pie para que los recien llegados a Gnu/Linux no les quede tan dificil la transicion a este sistema operativo, dando la oportunidad de que la persona que lea este material sea capaz de escoger alguna de las tres (de acuerdo a su experiencia o si quiere experimentar, que pueda hacerlo).
</p>

<p align="center">
Esta claro que el uso de un IDE (Entorno Integrado de desarrollo) facilita la vida del desarrollador realizando muchas cosas por el (configuraciones, etc, etc), pero lo ideal es que el desarrollador primero conozca bien su forma de trabajar(compilando, generando codigo obj, incluyendo librerias, compilar sus propias librerias, debuggeando, etc) y luego si pase a un IDE. Ya que con esto no crearia dependencia aun solo IDE, si no que seria capaz de migrar algun IDE en algun momento y que la curva del aprendizaje sea mucho mas rapida. 
</p>

<p align="center">
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

Estamos instalando por medio de los repositorios de ubuntu todo el paquete necesario para poder compilar con el gcc(compilador para lenguaje C) y el g++(compilador para c++) este paquete se llama build-essential. Aparte de esto nos incluye otros paquetes necesarios o que le dan una funcionabilidad mas (por ejemplo el dpkg-dev es usado para crear paquetes de nuestros programas para la instalacion).

Ahora vamos a comprobar la instalacion del compilador gcc que vamos a usar para poder compilar nuestros programas en C y verificar la version. 

```
gcc --version 
```

<p align="center">
<img src="imagenes/gcc_checked.jpg">
</p>

Con esto ya tenemos nuestro compilador basico para poder empezar a trabajar, idenpendiente de que forma se escoja.

## Configuracion de IDEs



### CodeBlocks

<p align="center">
<img src="imagenes/codeblocks_logo.png">
</p>

### Sublime + Pluggins

### Vim + Some Weird Stuff

## Referencias


