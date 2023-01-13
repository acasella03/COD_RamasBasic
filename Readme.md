# Tarea: Git Ramas (básico)

### Enunciado:
Crea un repositorio y realiza commits para que quede igual que el gráfico. Los commits 'C' y 'D', tienen que estar en una rama nueva llamada 'exp'.

Al final tiene que haber un merge:

Las modificaciones de la rama 'exp'  tienen que realizarse en una clase diferente.

Crea un Readme con todos los comandos en orden.

## Comandos realizados:

1. Creo un proyecto nuevo llamado "RamasBasic" y edito mi código en la Clase Main que se guarda en la Rama "master", a continuación realizo un commit (A) para que quede reflejado dicho cambio.
2. Realizo otra edición en la Clase Main, a continuación realizo el segundo commit (B) para que quede reflejado dicho cambio.
3. Luego en la HEAD(CurrentBranch) con el botón derecho del ratón creo una rama nueva llamada "exp", en dicha rama creo una nueva Clase llamada "NuevaClase", escribo código en dicha Clase y dejo reflejado la colaboración en un commit (C).
4. Vuelvo a la rama "master" para editar el código en la Clase Main porque en esa Rama sólo existe dicha clase, dejo reflejado éste cambio en el commit (E).
5. Luego me cambio a la rama "exp", edito la Clase "NuevaClase" porque es donde el colaborador está trabajando el código, dejo reflejado dicho cambio en el commit (D).
6. Vuelvo a la rama "master" para unir el código del colaborador realizada en la rama "exp" con la rama "master" ya que, en teoría, el código del colaborador sirve para el proyecto principal representado en dicha rama "master", una vez realizado el merge en la rama "master" en el fichero src sale reflejado tanto la clase Main como la clase "NuevaClase" del colaborador con los cambios de ambas clases hasta éste momento. Realizo el último commit (Merge branch'exp') realacionado con el código.
7. Por último agrego el Readme.md con la explicación pertinente y realizo un commit (Readme) para actualizar la explicación del proyecto.

