# Desafío 5 - Todo List
En este desafío validaremos nuestros conocimientos para agregar elementos dinámicamente en una página web. Para lograrlo, necesitarás aplicar lo aprendido en la guía

Lee todo el documento antes de comenzar el desarrollo __individual__, para asegurarte de tener el máximo de puntaje y enfocar bien los esfuerzos.

## Descripción

Aplicando los conceptos y herramientas aprendidas hasta ahora, deberás crear una página web que permita mantener un control de tareas pendientes.

A continuación te mostramos lo que debes maquetar:

<p align="center">
  <img src="https://github.com/Felipe-M-dev/JS-Challenge-05/blob/main/01.png?raw=true?raw=true" alt="Imagen 01"><br>
Imagen 1. Maqueta general del desafío<br>
Fuente: Desafío Latam
</p>

En donde tenemos un resumen de las tareas en el lado izquierdo:

<p align="center">
  <img src="https://github.com/Felipe-M-dev/JS-Challenge-05/blob/main/02.png?raw=true?raw=true" alt="Imagen 02"><br>
Imagen 2. Resumen<br>
Fuente: Desafío Latam
</p>

El resumen debe actualizarse cada vez que se agregue, modifique o elimine una tarea. Se deberá permitir al usuario agregar nuevas tareas a través de un input, las cuales serán enlistadas con su detalle y opciones para marchar o eliminar:

<p align="center">
  <img src="https://github.com/Felipe-M-dev/JS-Challenge-05/blob/main/03.png?raw=true?raw=true" alt="Imagen 03"><br>
Imagen 3. Lista de tareas<br>
Fuente: Desafío Latam
</p>

Las tareas deberán registrarse en un arreglo de objetos que guarde el id, la descripción y si ésta está realizada o no. Cuando una tarea está realizada puede cambiarse el estilo del texto o puede aparecer como un texto que diga "realizado". Tu decides.

## Requerimientos

1. Agregar tareas con descripción al llenar el input y presionar el botón agregar tarea La tarea es agregada al arreglo y luego la lista en la página web se actualiza. __(2 puntos)__

2. Borrar una tarea al hacer click en el botón que acompaña a la tarea. Se debe borrar el dato del arreglo y actualizar la lista. __(2 puntos)__

3. Contar el total de tareas, mantener actualizada esta cuenta cuando se agregue una tarea nueva o se borre una tarea. __(2 punto)__

4. Marcar una tarea como completada al hacer click en un botón "cambiar" (o se puede utilizar un checkbox como muestra la imagen) __(2 puntos)__<br>
Pistas<br>
○ Agregar al objeto el estado completado<br>
○ Iniciar las tareas con completado: false<br>
○ Al hacer click en el botón cambiar, se debe buscar el elemento por el índice y luego cambiar el estado a completado: true

5. Contar el total de tareas realizadas __(1 punto)__

💡 __Hint__: filtrar y luego contar

6. El código incluye al menos 3 tareas iniciales en el arreglo y esta se muestran en la página web recorriendo el arreglo (se puede utilizar for of o forEach) __(1 puntos)__

😊¡Mucho éxito!

[Try site](https://felipe-m-dev.github.io/JS-Challenge-05/)
