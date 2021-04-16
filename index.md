# Space Invaders
## Descripción del problema

#### Link a Jira
[Space Invaders Jira](https://diegovm02.atlassian.net/jira/software/projects/SI/boards/1)

## _Plan de Iteracion_
| ID | Actividad | Semana | Condicion de culminación|
|--- | ---| ---|---|
|01| Crear Ventanas |  1 semana | Aparecen las ventanas |
|02| Crear Clases para los objetos mostrados en pantalla| 2 semana | Al momento en que aparescan en pantalla ||
|03| Crear clases de las listas para el manejo de los invaders| 3 semana| Al momento en que las interacciones de los nodos funcionen bien|
|04| Crear clases row que manejen el funcionamiento de las oleadas de enemigos| 4 semana | Que las oleadas no colapsen|
|05| Ser caoaces de jugar | 5 semana | Cuando no suceda ningun bug ni run time error |

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
  * 1.Crear una ventana
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
    