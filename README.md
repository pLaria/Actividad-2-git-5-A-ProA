# Actividad-2-git-5-A-ProA
Ejemplo de descarga, clonación modificación y creación de ramas
Para descargar un repositorio externo Tiene que utilizar el comando "git clone" seguido de la url "https://github.com/pLaria/Actividad-2-git-5-A-ProA"
"git clone https://github.com/pLaria/Actividad-2-git-5-A-ProA.git"
Abran el repositorio descargado con "cd Actividad-2-git-5-A-ProA"
Para ver el historial de commit "git log"
Ver el listados de archivos "ll"
Modificacion de archicos con el editor de "git vim" seguido del nombre del archivo
Con "git status" visualizamos en que archivos se han realizado cambios
Con "git diff" muestra las diferencias entre el repositorio original y tu clone modificado en tu maquina
Agegamos el archivo modificado con "git add"
Creamos el "git commit -m" seguido de un mensaje de lo que se ralizo "se modifico el archivo *.txt " y agregamos los archivos al repositorio que estamos utilizando
Para subir nuestro codigo a internet "git push origin master"
Para descargar la ultima version del codigo "git pull origin master"


A la hora de trabajar con varias personas programando en un mismo proyecto una buena accion es crear una "rama" del codigo (branch) 
asi evitamos pisamientos en las modificaciones de codigo, al realizar una branch todas personas puder ver que cambios hiciste se acepta lo meten y se crea una nueva version.

Para crear uan branch "git branch minuevarama"
Para trabajr con la rama creada "git checkout minuevarama"
Realizamos un "git status" para confirmar que estamos trabajando en la nueva rama
para enlistar todas las branch creadas de este proyecto dentro de tu pc "git branch"
Ver el listados de archivos "ll"
Modificacion de archicos con el editor de "git vim" seguido del nombre del archivo
Con "git status" visualizamos en que archivos se han realizado cambios
Con "git diff" muestra las diferencias entre el repositorio original y tu clone modificado en tu maquina
Agegamos el archivo modificado con "git add"
Creamos el "git commit -m" seguido de un mensaje de lo que se ralizo "se modifico el archivo *.txt " y agregamos los archivos al repositorio que estamos utilizando
linkeamos una branch en repositorio del servidor con el repositorio local donde estamos trabajando "git push -u origin minuevarama"
"git log"

mostrar branch locales y remotas "git branch -a"

borrar feature "git push origin --delete minuevarama"
borrar branch  "git branch -d minuevarama"
