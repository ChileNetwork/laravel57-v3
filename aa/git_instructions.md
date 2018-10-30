####### Github Account
####### username: chilenetwork
####### password: Marrojo$$M......2

## Crear Repositorio en Github
	…or create a new repository on the command line

	echo "# laravel57-v3" >> README.md
	git init
	git add README.md
	git commit -m "first commit"
	git remote add origin https://github.com/ChileNetwork/laravel57-v3.git
	git push -u origin master

	…or push an existing repository from the command line

	git remote add origin https://github.com/ChileNetwork/laravel57-v3.git
	git push -u origin master

## Inicializar repositorio en terminal:
Crea un directorio oculto .git con archivos y carpetas en localhost.

$ git init
Initialized empty Git repository in /Users/msoto/Sites/laravel57-v3/.git/

## Configurar nombre y email de usuario.
$ git config --global user.name "chilenetwork"
$ git config --global user.email "msotosalgado.77@gmail.com"

## Seteamos el repositorio remoto.

$ git remote add origin https://github.com/ChileNetwork/laravel57-v3.git

## Agrega todos los archivos en el directorio local a la cola de subida.

$ git add .

## Crea el Commit con una leyenda para la actualizacion.

$ git commit -m "Primer Commit: Subir archivos Laravel Version 5.7"


## Ahora subimos los archivos con el comando Push.
Este comando se puede hacer una sola vez. Luego no sera necesario -u origin master para subir los 
arhivos.
$ git push -u origin master

