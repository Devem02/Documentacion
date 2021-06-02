# Space Invaders With Friends
## Descripción del problema
Basandonos en la version 1.0 del Space Invaders, se desarrollara una nueva versión que incluirá nuevas características como la posibildad de que varios jugadores participen simultaneamente.<br/>Para esto se deberán trabajaar dos programas en Java por separado, el servidor y el cliente. Donde el servidor recibe mensajes indicando las acciones que ha realizado cada jugador y este mismo actualiza a los demas clientes enviándoles el evento realizado por un determinado jugador.
<br/><br/>Ademas, en esta nueva version se añadirán dos nuevas clases de enemigos, que acompañaran a las ya existentes, las nuevas implementaciones seran las:
1. Tipo BST
   - El cual es un árbol binario de busqueda. Y se vera en pantalla como un árbol BST
2. Tipo AVL
   - Siendo un árbol AVL.
   


## Link a Jira
[Space Invaders Jira](https://diegovm02.atlassian.net/jira/software/projects/SI/boards/1)

## _Plan de Iteracion_


* Semana 1: Investigacion con respecto a los servidores.
* Semana 2: Crear clases de los arboles para el manejo de los invaders. Al momento en que las interacciones de los nodos funcionen bien.
* Semana 3: Crear el server y cliente para el multijugador. Al momento que sea posible observar los cambios.
* Semana 4: Mostrar Arboles en pantalla y cambios de los clientes. Que las oleadas no colapsen.
* Semana 5: Ser capaces de jugar. Cuando no suceda ningun bug ni run time error

## Descomposicion de  _User Stories_  en tareas
Para el proyecto se planteo el siguiente plan de iteracion de acuerdo a las *User Stories*

1.Crear multijugador
  - Crear servidor
    - Hacer que el Servidor maneje la logica del juego.
    - Hacer que el Servidor envie y reciba informacion del cliente.
  - Crear cliente
    - Hacer que el cliente se encargue del renderizado
    - Renderizar la informacion enviada por el Servidor
    - Hacer que el Cliente se encargue de la logica de su respectiva nave
  - Lograr conexión entre ambos

3.Crear clases de los arboles para el manejo de los invaders
  - 3.1 Crear clases Nodos para el uso en los arboles  
    - Nodo Binario
    - Nodo AVL
  - Arbol AVL
  - Arbol Binario

4. Lograr el intercambio de informacion entre servidor y cliente

5.Hacer aparecer los invaders y nave en pantalla

## Asignacion de tareas e historias
La asignación de tareas sucedio de la siguiente forma:

- Diego Vega y Jordy Calderon
    * Implementación del multijugador
    
- Juan Rodríguez y Jose Umaña
    * Creación de árboles
    
## Descripción de bugs encontrados

    
Diagrama de clase:
![alt text][logo1]

[logo1]: https://github.com/Devem02/Documentacion/raw/main/images/Diagrama.png "Logo Title Text 2"
