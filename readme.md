¿Qué comando utilizaste en el paso 11? ¿Por qué?

Utilice el comando git reset --hard HEAD~1. Utilizo este comando para deshacer el último commit con el modificador --hard para que se pierdan los cambios en el stating área.

¿Qué comando utilizaste en el paso 12? ¿Por qué?

Para rehacer el commit primero tenemos que hacer git reflog para localizar el identificador de del commit que acabamos de deshacer. Posteriormente utilizaremos el comando git reset -- <identificador_del_commit_anterior>.

El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

No causa ningún conflicto. De hecho, la respuesta del merge es Aready up to date, porque ese commit ya contiene al commit con el que mergea.
 
El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?

SI hay conflicto pues se trata de un merge no fast fordward.

 El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?

No hay conflicto pues se trata de un merge fast forward

¿Qué comando o comandos utilizaste en el paso 25?

git log --graph --decorate -- pretty=oneline

El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?

Si podría ser fast fordward porque existe conexión directa entre los dos commits que hacen el merge

¿Qué comando o comandos utilizaste en el paso 27?
git reset HEAD~1

¿Qué comando o comandos utilizaste en el paso 28?

git checkout -- git-nuestro.md
 
¿Qué comando o comandos utilizaste en el paso 29?

git branch -D title

¿Qué comando o comandos utilizaste en el paso 30?

git reflog (para buscar el commit en el que hicimos el merge)
git reset --hard <identificador_del commit_donde_se_hizo_el_merge)

¿Qué comando o comandos utilizaste en el paso 32?

git reflog (para buscar el commit inicial)
git reset --hard <identificador_del commit_inicial)

¿Qué comando o comandos utilizaste en el paso 33?
git reflog (para buscar el commit en el que pusimos el titulo)
git reset --hard <identificador_del commit_donde_pusimos_el_titulo)

