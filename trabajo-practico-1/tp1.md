# Trabajo Practico N1


### *¿Qué es un Pull Request?*
El sistema de control de versiones **git**, ofrece una solucion muy conveniente a la hora de llevar control sobre el desarrollo de un proyecto, con el mismo podemos ver el progreso del trabajo solo con inspeccionar el cambio realizado en cada commit. Los **Pull Request** permiten no solo llevar de forma mas ordenada las tareas en la etapa del desarrollo, sino también crear propuestas o cambios que puedan ser integrados posteriormente a dicho proyecto.
Basicamente una **Pull Request** es la acción de validar un código que se va a mergear de una rama a otra.


### *Uso de un Pull Request*
Cuando se trabaja como parte de un equipo se debe llevar mayor cuidado con los cambios y los merge a master. Este es el principal uso que se les da a las Pull Request, ya que con ellas estarias haciendo una peticion de que esta rama cambiada sea incluida en **master**, incluyendo una explicacion mucho mas detallada de lo que tu codigo hace (mas alla del mensaje del commit) y la persona encargada de la integracion puede descargar tu rama, probar los cambios y aprobar o rechazar la peticion, segun sea el caso, inclusive dejar un comentario para que hagas algun arreglo si es requerido.  

![Captura1](/imagenes/captura_Pull_Request_1.png)
___
![Captura2](/imagenes/captura_Pull_Request_2.png)
___
![Captura3](/imagenes/captura_Pull_Request_3.png)
___



## Punto 5
**Mergear codigo con conflicto:**
![Captura4](/imagenes/captura_beyond_compare.png)  
  ___
  
* **LOCAL**: el o los archivos *head* del branch actual de la maquina en la que estamos trabajando.  

* **REMOTE**: el o los archivos *head* de una ubicacion remota a la cual intentamos merger en nuestro repositorio LOCAL.  

* **BASE**: el ancestro comun de LOCAL y BASE.