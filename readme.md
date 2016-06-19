- ¿Qué comando utilizaste en el paso 11? ¿Por qué?
git reset --hard HEAD~1 , en el movemos head a commit anterior y además con --hard modificamos el working copy, por lo que volvemos al punto anterior (perdemos los cambios)

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?

git reflog para obtener el hash (0c7386d) del commit anterior que habíamos hecho
git reset --hard 0c7386d para volver a estar como estábamos modificando el working copy
- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?
No, porque todos los cambios estaban el styled

- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?
Si hubo conflictos por estar modificadas las mismas lineas

- El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?
No, el sistema identificó los cambios

- ¿Qué comando o comandos utilizaste en el paso 25?
git log --graph --decorate --pretty=oneline


- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?
Si, podría haberlo sido


- ¿Qué comando o comandos utilizaste en el paso 27?
git reset HEAD~1 


- ¿Qué comando o comandos utilizaste en el paso 28?
git reset --hard master

- ¿Qué comando o comandos utilizaste en el paso 29?
git  branch -D title

- ¿Qué comando o comandos utilizaste en el paso 30?

posicionados en master 
git reflog para sacar el hash del commit en el quey habiamos hecho el merge

git reset --hard 4195d5b para posicionarnos en el


- ¿Qué comando o comandos usaste en el paso 32?

git reflog 
git reset --hard 663e7c7


- ¿Qué comando o comandos usaste en el punto 33?
Git reflog para localizar el commit
Git reset --hard en el commit del merge con el titulo
