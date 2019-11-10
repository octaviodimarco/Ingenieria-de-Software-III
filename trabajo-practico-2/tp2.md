# Trabajo Practico N2

### *Introducción a Maven*
*Maven*  es una herramienta open-source, que se creó en 2001 con el objetivo de simplificar los procesos de build (compilar y generar ejecutables a partir del código fuente). Es una evolucion de otras herramientas para construir herraminetas de java. Tiene multiples utilidades y puglins. 

**POM:**
Es fichero de configuración de Maven, basicamente es la receta de que quiero construir. Define las diferentes pasos durante la ejecucion de un build.

* modelVersion: Siempre es 4.0.0, es la version de la definicion del lenguaje de Maven.
* groupId: el id del grupo del proyecto.
* artifactId: nombre del proyecto, es el identificador de la libreria que nosotros estamos construyendo.
* versionId: Esto representa la version de nuestra libreria. *SNAPSHOT* significa que esta en desarrollo.




**Repositorios:** 
* Central: en este repositorio se encuentra todo, por defecto se busca aca.
* Local: mi copia.
* Remoto: cosas que puedo tener en un servidor privado.

___ 
### *Ciclos de vida*
Maven esta basado alrededor de un concepto central, los **ciclos de vida**. Esto significa que el proceso de construir y distribuir un proyecto particualr esta claramente definido.
Para la persona encargada de construir el proyecto esto significa que solo debe aprenderse unos pocos comandos para ser capaz de buildear un proyecto de Maven, ademas el **POM** asegura que se obtenga el resultado obtenido.

Los ciclos de vida son tres:
* default: encargado del deployment.
* clean: maneja la limpieza del proyecto.
* site: se encarga de la creacion de la documentacion.




Conclusiones:
Al ejecutar el clean install lo primero que hizo fue descargar numerosos archivos desde central.

Punto 6:
El problema, como dice la consola es que no se ha encontrado el pluggin uber-jar, la solucion, entonces, es incluirlo.  
___
Luego de incluirlo:
![Imagen1](/imagenes/captura_Hola_Mundo.png)


___

### *Build tools para otros lenguajes*

1. C++ --> CMake, SCons, Premake
2. Scala --> sbt
3. Python --> PyBuilder
4. Swift --> Package Manager
5. Rust --> Cargo
6. Groovy --> Gradle
7. Go --> Task, Makefile
8. PHP --> Phing
9. Scratch --> The Chopper, Miter Sander, Paper Cutters
10. Kotlin --> Ant

___ 
### *Ejemplo con nodejs*
Luego de instalar Nodejs y Express se ejecuta la siguiente aplicacion:
![Imagen2](/imagenes/captura_node_js.png)