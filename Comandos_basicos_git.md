Comandos básicos

. Inicializamos nuestro repositorio local >>git init
. Nos traemos el directorio remoto>> git clone https://github.com/xxx/pps.git
. Añadimos los cambios al stage>> git add .
. Registramos los cambios >> git commit –m “Configuracióninicial
. Subimos nuestros cambios  al remoto >> git push origin master

Ramas

. Crear una rama:
$ git checkout -b rama1

. Ver enque ramaestamo:
$ git Branch

. Cambiar de rama:
$ git checkout master

Ver los cambios entre ramas:
$ git diff --stat master rama1

Fusionar rama:
$ git checkout master
$ git merge --no-ff rama1

Eliminarla rama:
$ git branch -d rama1
