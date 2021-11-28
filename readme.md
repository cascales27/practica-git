**Practica 1**

Ejercicio 1 

Se deberá crear un repositorio y realizar una serie de operaciones desde la consola de comandos sobre el mismo para posteriormente subir el repositorio a Github. 

Se deberá entregar a través del formulario de prácticas indicando la URL del repositorio. En el repositorio, deberá existir un archivo readme.md con las respuestas a las siguientes preguntas:

- ¿Qué comando utilizaste en el paso 11? ¿Por qué? 
    git reset --hard HEAD~1. Por que con el reset HEAD~1 se mantendria el working copy. Lo compruebo con git log.

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
	Primero utilizo reglog para ver el identificador del commit que buscaba y luego  git reset –hard con el numero de identificador para llegar a el, porque asi se vuelve al trabajo que habia guardado en ese commit.

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
No, porque no hay diferencia entre los commits.

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
Si, porque cuando styled absorbe a htmlify hay diferencias en el archivo.

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
No, porque no hay modificaciones en los coomits.

- ¿Qué comando o comandos utilizaste en el paso 25?
 git log --graph --pretty=oneline


- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?

Si, porque en principio lo hice mal y lopude hacer , lo he vuelto ha hacer desde 0 todo y he hecho un  git merge –no- f y me ha salido tambien.

- ¿Qué comando o comandos utilizaste en el paso 27?
git reset --hard HEAD~1

- ¿Qué comando o comandos utilizaste en el paso 28?
Algo he hecho mal porque no tengo cambios para descartar, ni me dice nada al hacer git add gitnuestro ni al hacer commit. Con el comando git diff se tendrian que ver las diferencias.

- ¿Qué comando o comandos utilizaste en el paso 29?
git merge -D title
- ¿Qué comando o comandos utilizaste en el paso 30?
Primero se hace un reflog, para buscar el identificador y asi poder volver al estado que queremos volver. Finalmente un git reset –hard y el numero del identificador del punto al que queremos volver
- ¿Qué comando o comandos usaste en el paso 32?
En este caso despues de buscar con git reflog el commit al que queria volver(inicio del poema) git reset –hard y numero del identificador.

- ¿Qué comando o comandos usaste en el punto 33?


Como siempre git reflog al rescate, y git reset—hard con el identificador del commit al que queriamos ir.



En el paso 35 creo los tags pero no se como ligarlos al commit al que habria que ligarlos, lo buscare en el video de la clase del sabado por si lo encuentro y lo hago.
