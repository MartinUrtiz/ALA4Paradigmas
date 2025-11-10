Explicación de características de la Programación Orientada a Objetos

En este programa se aplican varias ideas de la Programación Orientada a Objetos (POO), aunque no se usaron clases directamente. El código usa tipos, interfaces y funciones para mantener una estructura clara y ordenada.

🔹 Encapsulamiento

Toda la información de una tarea está dentro de una estructura llamada Tarea, que agrupa sus propiedades (id, titulo, estado, etc.).
Además, se usa readonly y Object.freeze() para evitar que los datos se modifiquen por error, protegiendo el contenido de cada tarea.

🔹 Abstracción

Cada acción del programa (crear, buscar, filtrar o actualizar tareas) está dentro de una función con un nombre claro.
Esto hace que el código sea fácil de entender sin tener que saber los detalles internos.

Por ejemplo:

tareas = crearTarea(tareas, titulo, descripcion, "pendiente", dificultad);


Se entiende qué hace, sin mirar cómo funciona por dentro.

🔹 Modularidad

El código está dividido en partes pequeñas (funciones independientes), lo que permite mantener y modificar el programa más fácilmente sin romper otras secciones.

🔹 Inmutabilidad

Se crean nuevas versiones de las tareas en lugar de modificar las existentes.
Esto evita errores y mantiene el código más seguro y predecible.

Características no utilizadas

Herencia: no fue necesaria porque todas las tareas son del mismo tipo.

Polimorfismo: no se usaron distintos tipos de objetos con comportamientos diferentes.

Clases: el código se resolvió bien con funciones y tipos, por lo que no fue necesario crear clases.
