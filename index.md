# Space Invaders
## Descripción del problema
Invaders es un juego en el que el jugador puede controlar una nave que se mueve horizontal mente en la parte inferior de la pantalla con el fin de eliminar a todos los invasores. Los invasores son hileras de enemigos que avanzan de arriba hacia abajo en la pantalla y se mueven de lado a lado.(el movimiento es de la hilera completa).<br/>El jugador deberá mover la nave para eliminarlos y evitar que lleguen hacia la parte inferior de la pantalla.Las hileras de enemigos varían aleatoriamente. Cualquier tipo de hilera de enemigos se implementa mediante una lista enlazada y poseen ciertos atributos especiales.Conforme los niveles avanzan, los enemigos son más rápidos. Cualquier tipo de lista enlazada, debe ser implementada por el equipo de trabajo.Conforme el jugador destruye los enemigos, los miembros de la hilera se mueven hacia el centro:
<br/><br/>Existen las siguientes clases de hileras de enemigos:

## Link a Jira
[Space Invaders Jira](https://diegovm02.atlassian.net/jira/software/projects/SI/boards/1)

## _Plan de Iteracion_
<<<<<<< HEAD

* Semana 1: Aparecen las ventanas.
* Semana 2: Crear Clases para los objetos mostrados en pantalla. Al momento en que aparescan en pantalla .
* Semana 3: Crear clases de las listas para el manejo de los invaders.Al momento en que las interacciones de los nodos funcionen bien.
* Semana 4:Crear clases row que manejen el funcionamiento de las oleadas de enemigos. Que las oleadas no colapsen.
* Semana 5: Ser capaces de jugar. Cuando no suceda ningun bug ni run time error 
=======
| ID | Actividad | Semana | Condicion de culminación |
| --- | --- | --- | --- |
| 01 | Crear Ventanas |  1 semana | Aparecen las ventanas | 
| 02 | Crear Clases para los objetos mostrados en pantalla | 2 semana | Al momento en que aparescan en pantalla |
| 03 | Crear clases de las listas para el manejo de los invaders | 3 semana | Al momento en que las interacciones de los nodos funcionen bien |
| 04 | Crear clases row que manejen el funcionamiento de las oleadas de enemigos | 4 semana | Que las oleadas no colapsen |
| 05 | Ser capaces de jugar | 5 semana | Cuando no suceda ningun bug ni run time error |
>>>>>>> 82e96dfe833f4b83478be611582209dfd9bacd37

## Descomposicion de  _User Stories_  en tareas
Para el proyecto se planteo el siguiente plan de iteracion de acuerdo a las *User Stories*

1.Crear ventanas
  - Crear una ventana de Menu principal
  - Crear una ventana de Juego
  - Crear Una ventana de Instrucciones

2.Crear Clases para los objetos mostrados en pantalla
  - Crear clase Spacecraft
  - Crear clase LaserBeam
  - Crear clase minion (tipo de invader comun)
  - Crear clase boss (tipo especial de invader)
  - Crear clase Contador

3.Crear clases de las listas para el manejo de los invaders
  - 3.1 Crear clases Nodos para el uso en las listas  
    - Nodo simplemente enlazado 
    - Nodo doblemente enlazado
  - Lista simplemente enlazada
  - Lista doblemente enlazada
    - Crear función BubbleSort
    - Crear función que cambie la posicion del boss cada cierto tiempo
  - Lista simplemente enlazada circular
    - Crear función que convierte un minion en boss
   - Lista doblemente enlazada circular
     - Crear función que convierte un minion en boss

4.Crear clases row que manejen el funcionamiento de las oleadas de enemigos
   - Row Basic
   - Row A
   - Row B
   - Row C
   - Row D
   - Row E

5.Hacer aparecer los invaders y nave en pantalla

## Asignacion de tareas e historias
La asignación de tareas sucedio de la siguiente forma:

- Diego Vega
  * 1.Crear ventanas
  * 5.Hacer aparecer los invaders y nave en pantalla
    
- Juan Rodríguez 
  *  2.Crear Clases para los objetos mostrados en pantalla
    
- Jordy Calderón
  * 3.Crear clases de las listas para el manejo de los invaders
    
- Jose Umaña
  * 4.Crear clases row que manejen el funcionamiento de las oleadas de enemigos
    
## Descripción de bugs encontrados
- BubbleSort:
  - La función se mantiene ejecutandose en algunas situaciones y no se detiene a no ser que se detenga el proceso
    
