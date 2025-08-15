El IDE nos indica un error con el JDK, pero tambien tiene la opcion para corregirlo

Hay un error con el gestor de dependencias, esta creado con gradle y siempre hemos usado maven, no tengo idea de como corregirlo, debo investigarlo

No tengo claro como despues de realizar el Fork desde el repo git y clonarlo a mi maquina, que debo hacer depues, crear un nuevo proyecto en spring initializr?

La clase curso no tiene getter y seter, se corrige esta parte agregandolos.

La clase docente no tiene constructores y lo getter y setter estan incompletos, se corrige esto.

En la clase usuario hacia falta el atributo docente el el constructor, se agrega en la linea 40, ademas de los getter y seter.

Se intenta corregir el error del gestor de dependencias sin exito, con la ayuda de IA indica eliminar las carpetas gradle y crear archivo pom.xml pero la verdad es una solucion invasiva y no fui capas de implementarla y me hace plantar si se debe crear el proyecto desde cero con spring initializr

Para corregir el error de gestor de dependencias se puedes reemplazar las carpetas de anterior gestor, crear el archivo pom.xml pero no se que tan buena practica sea y la idea era no usar IA

Como la idea era no usar IA, no logro resolver problema de gestor de dependencias y por ende el codigo no compila, no puedo conectar a la BD y dejo el trabajo hasta este punto.

Puntos a reforzar

-Validar como solucionar un cambio del gestor de dependencias en un proyecto ya realizado
-No me queda claro si el proyecto se debia crear nuevamente desde spring initializr
-Reforzar la conocimiento en conexion a BD, en la clase que se explico este tema tube problemas con XAMPP
y no pude realizarlo