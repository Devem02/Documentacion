# Space Invaders
## Descripción del problema
Invaders es un juego en el que el jugador puede controlar una nave que se mueve horizontal mente en la parte inferior de la pantalla con el fin de eliminar a todos los invasores. Los invasores son hileras de enemigos que avanzan de arriba hacia abajo en la pantalla y se mueven de lado a lado.(el movimiento es de la hilera completa).<br/>El jugador deberá mover la nave para eliminarlos y evitar que lleguen hacia la parte inferior de la pantalla.Las hileras de enemigos varían aleatoriamente. Cualquier tipo de hilera de enemigos se implementa mediante una lista enlazada y poseen ciertos atributos especiales.Conforme los niveles avanzan, los enemigos son más rápidos. Cualquier tipo de lista enlazada, debe ser implementada por el equipo de trabajo.Conforme el jugador destruye los enemigos, los miembros de la hilera se mueven hacia el centro:
<br/><br/>Existen las siguientes clases de hileras de enemigos:
1. Basica
   - Solo tiene minions
2. Tipo A
   - Tiene un Boss
3. Tipo B
   - Tiene un Boss que se intercambia
4. Tipo C
   - Tiene un Boss que si se destruye otro toma su lugar aleatoriamente
5. Tipo D
   - Todos los miembros de la hilera tienen resistencias distintas
6. Tipo E
   - La hilera rota con el Boss en el centro
7. Tipo BST
   - Hilera con forma de arbol binario
8. Tipo AVL
   - Hilera con forma de arbol AVL

Ademas de esto se incluye el modo multijugador, el cual usando un servisor local varios usuarios pueden jugar simultaneamente.


   


## Link a Jira
[Space Invaders Jira](https://diegovm02.atlassian.net/jira/software/projects/SI/boards/1)

## _Plan de Iteracion_


* Semana 1: Aparecen las ventanas.
* Semana 2: Crear Clases para los objetos mostrados en pantalla. Al momento en que aparescan en pantalla .
* Semana 3: Crear clases de las listas para el manejo de los invaders.Al momento en que las interacciones de los nodos funcionen bien.
* Semana 4:Crear clases row que manejen el funcionamiento de las oleadas de enemigos. Que las oleadas no colapsen.
* Semana 5: Ser capaces de jugar. Cuando no suceda ningun bug ni run time error

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
    
Diagrama de clase:
![alt text][logo1]

[logo1]: https://github.com/Devem02/Documentacion/raw/main/images/Diagrama.png "Logo Title Text 2"