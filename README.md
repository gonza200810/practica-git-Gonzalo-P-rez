# Prácticas de Git y Github

## José Gonzalo Reyna Pérez

## 2630022

**Objetivo:**
Crear un repositorio local utilizando Git, conectarlo con un repositorio remoto en Github y practicar la sincronización de cambios en ambas direcciones: de local a Github y de Github a local.

## descripción del procedimiento

Primero ``cree una carpeta``, despues ``inicie el repositorio local``, ``configure la rama principal`` con el nombre main y ``cree los archivos`` README.md y datos.txt, hice un git status para verlos y despues ``agrege los archivos al área de preparación`` (Staging Area), verifique el estado del repositorio y ``hice mi primer commit``.

Cree un repositorio nuevo en Github con el mismo nombre, copie el URL del repositorio de Github y vincule el repositorio local con el repositorio remoto, verifique que el repositorio remoto se haya agregado correctamente.

Realicé la primera sincronización utilizando el comando ``git push -u origin main `` con el cual envie los archivos del repositorio local al repositorio remoto en Github.

``Me dirigí a Github y modifiqué el archivo datos.txt``  lo guarde y me fuy a powershell y utilicé git pull origin main para descargar los cambios de Github al repositorio local y comprobar que la modificación apareciera.

Después`` modifique el archivo datos.txt desde el repositorio local`` hice un git status enseguida utilize git add . para preparar los cambios, git commit para registrarlos  y git push para enviarlos a Github.

### Descripción de los archivos
* README.md: Contiene la documentación de la practica.
* datos.txt: Contiene los datos utilizados para comprobar la sincronización.

## Comandos utilizados

* ``cd``: para ubicarme en la carpeta donde crearé la carpeta practica-git-Gonzalo-Pérez.
* ``mkdir``: Lo utilicé para crear la carpeta practica-git-Gonzalo-Pérez.
* ``cd``: Para entrar en la carpeta practica-git-Gonzalo-Pérez,
* ``git init``: para iniciar un repositorio en git.
* ``git branch -M main``: Para configurar el nombre de la rama principal como main.
* ``New-Item``: Para crear mis archivos.
* ``git status`` : Para ver el estado de mis archivos.
*`` git add .`` : Para agregar mis archivos al área de preparación.
* ``git commit -M ""`` : Para guardar los cambios en el historial.
* ``git remote add origin`` : Conecte el repositorio local con Github.
* ``git remote -v`` : Para verificar que el respositorio remote se haya agregado correctamente.
* ``git push -U origin main`` : Envie por primera vez el repositorio local a Github.
* ``git pull ``: Descarge los cambios de Github al repositorio local.
* ``git pull origin main`` : Hice el comit en Github para guardar cambios.


## Conclusión

* Con esta practica aprendí a crear un repositorio local, conectarlo con Github y sincronizar cambios en ambas direcciones utilizando Git.

