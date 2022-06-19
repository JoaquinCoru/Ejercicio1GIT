# README con las respuestas a las preguntas del ejercicio

**- ¿Qué comando utilizaste en el paso 11? ¿Por qué?**

He utilizado git reset --hard HEAD~1 porque me permite deshacer lo que había en el último commit y en el working copy

**- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**

He utilizado git  reflog para ver el historial de commits y luego git reset --hard  (hash del commit) para volver a él 
actualizando los cambios en el working copy

**- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**

No causó conflictos porque los últimos cambios a los que se han hecho commit se hicieron en esta rama 

**- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**

Sí ha causado conflictos porque hemos hecho modificaciones en el mismo archivo en dos ramas diferentes, styled y 
htmlify desde el último commit que se hizo en master


**- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**

No ha causado conflicto porque en master no se habían hecho nuevos cambios en el archivo desde que se hicieron en la 
rama styles

**- ¿Qué comando o comandos utilizaste en el paso 25?**

git log - -graph

**- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**

Sí podría haber sido fast forward porque en este caso los commits de ambas ramas estarían en la misma línea y estarían 
todos los commits que teníamos accesibles en la misma rama tras hacer el merge

**- ¿Qué comando o comandos utilizaste en el paso 27?**

git reset HEAD~1

**- ¿Qué comando o comandos utilizaste en el paso 28?**

git restore git-nuestro.md

**- ¿Qué comando o comandos utilizaste en el paso 29?**

git branch -D title

**- ¿Qué comando o comandos utilizaste en el paso 30?**

git reflog : para ver el hash del merge que queremos rehacer

git reset (hash del commit) : Para volver a ese commit

**- ¿Qué comando o comandos utilizaste en el paso 32?**

git reflog: Para ver el historial de commits

git checkout (hash del commit inicial): Para volver a ese commit

**- ¿Qué comando o comandos utilizaste en el paso 33?**

git checkout master
