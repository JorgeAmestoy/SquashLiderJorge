***TAREA MERGE SQUASH POR PAREJAS***<br><br>
------------
<br>

**Pasos realizados como líder del proyecto:**
<br>

1. Inicializo el repositorio dándole en la barra superior de herramientas a VCS y `create git repository`<br>
2. Realizo los dos primeros commits (color azul) en la clase Main haciendo las modificaciones deseadas en el código y posteriormente en la ventana de la izquierda de Commit
, guardo los cambios, pongo el nombre correspondientes a estos y pulso `commit`.
3. Creo una nueva rama ("Líder") pulsando main en la esquina inferior derecha y después en `New Branch` , y le doy nombre a esta (comando de consola: git branch lider)
4. Verificando que estoy trabajando en la nueva rama (comando consola: git branch), creo una nueva clase y hago las modificaciones y commits correspondientes. Tres en este caso.
5. Terminada mi parte, vuelvo a la Rama Main (comando consola: git checkout main) 
6. Descargo del remoto los cambios realizados por mi compañera con `git pull` o `update project` en la flecha azul superior derecha.
7. Tras esto, hago un `git merge`. Pulso Git en la barra de herramientos, le doy a Merge, elijo la rama con la qué quiere hacer merge, en este caso la rama Colaborador. Le doy a --squash.
8. Realizo el mismo proceso pero con la rama Lider.
8. Hago un nuevo commit y subo el proyecto a GitHUb con git push.


