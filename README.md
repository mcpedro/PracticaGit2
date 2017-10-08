# PracticaGit2

### Pedro Venegas, Mari Carmen

Nota: en la terminal de mi ordenador no me sale el editor de texto nano. Cuando le digo 'git log' no me sale nada. 
Cuando intento hacer un 'merge' tampoco me sale el editor de texto. Al igual cuando pongo 'git commit' por lo que no sé
si habré realizado bien la practica obviando esto. Sin embargo cuando pongo en la terminal 'nano', el editor si que aparece y me dice
que si está instalado.

Otro problema al terminar la practica es que cuando acabo y le digo 'git status' me dice en rojo 'HEAD detached from htmlify'
al intentar arreglarlo he perdido el readme.md al subir a Github. Pero veo la opción de volverlo a escribir desde GitHub.

**1. ¿Qué comando utilizaste en el paso 11? ¿Por qué?

'git reset --hard HEAD~'

Con 'git reset HEAD~' se deshace el commit anterior, y el stating Area que da vacio, pero el commit queda en el working copy.
para deshacer el ultimo commit perdiendo los cambios realizados en el working copy utilizamos: 'git reset --hard HEAD~1'

**2. ¿Qué comando o comnados utilizaste en el paso 12? ¿Por qué?**

'git reset --hard 1208977'

Para conseguir rehacer el ultimo commit he puesto 'git reflog' donde me aparece el historial de los commits realizados y he copiado
el identificador. "Modifico el archivo don-quijote"

'git reset --hard 1208977' rehace el ultimo commit


**3. El merge del paso 13, ¿causó algun conflicto? ¿Por qué?**

'git merge master'

Para que 'styled' absorba a 'master' vemos en que rama estamos 'git branch'.
vamos a la rama styled con 'git checkout styled'. Y hacemos un merge con la rama master, con 'git merge master'

No causó ningún conflicto.

**4. El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**

'git merge htmlify'

Para que 'styled' absorba a 'htmlify' vemos en que rama estamos 'git branch'. vamos a la rama styled con 'git checkout styled'
y hacemos un merge con la rama 'htmlify', con 'git merge htmlify'

al hacer un merge me crea conflictos. He puesto 'git reset HEAD don-quijote.md' para deshacer cambios, 'git checkout styled'
'git reflog 1208977' es decir copio el código del contenido de la rama styled para quedarme con él.

**5. El merge del paso 21, ¿Causó algún conflicto' ¿Por qué?**

'git merge styled'

Sí. El merge causó un fast-forward

**6. ¿Qué comando o comnados utilizaste en el paso 25?**

'git graph'

Nota: Aunque en mi terminal no me sale.

**7. El merge del paso 26 ¿Podría ser un fast forward? ¿Por qué?**

'git merge title'

Sí. es un fast forwad por que al hacer un merge con la rama title, esta rama estaba creada en la rama master.
Estaban como en línea, en el mismo punto.

**8. ¿Qué comando utilizaste en el paso 27?**

'git reset HEAD~1

**9. ¿Qué comando utilizaste en el paso 28?**

**10. ¿Qué comando utilizaste en el paso 29?**

'git branch -D tittle'

**11. ¿Qué comando utilizaste en el paso 30?**

'git reflog' 'git checkout e7a7ea6'

Rehace el merge que había deshecho.

**12. ¿Qué comando utilizaste en el paso 32?**

'git reflog' 'git checkout 1694b67'

'git reflog' para ver el código. 'git checkout 1694b67' para volver al commit inicial


13. ¿Qué comando utilizaste en el punto 33?

'git reflog' 'git checkout e7a7ea6'

'git reflog' para ver el código. 'git checkout e7a7ea6' Cuando puse el título. "Añado titulo al archivo don-quijote"




















