2. git local a remoto
	1. git init → inicializa el repositorio local.
	2. git remote add origin {URL_REPO} → vincular los dos repositorios.
	3. git branch -m {nombre} → crear una rama en el repo local.

	*SIEMPRE JUNTOS (subir la rama al remoto)
	-------------------------------------------------------------------
	4. git add . → agregar los cambios al repo local.
	5. git commit -m "" → agregar un comentario al push.
	6. git push -u origin {RAMA_push} → subir las cambios al repo remoto.
	-------------------------------------------------------------------
