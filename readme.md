# GIT (Sistema de control de versiones)

Esto es una guia teorico/practica para los alumnos de __Git Desarrollo Colaborativo__ que cursan los dias _jueves de 18hrs a 20hrs_, cuya finalidad es reforzar los conceptos y temas trabajados en clase.

## Congiuracion Inicial

Cuando trabajamos con GIT debemos iniciar un proyecto en la carpeta donde querramos llevar un control de los cambios.
Para ello es necesario establecer un nombre de usuario y correo con el que se pueda identificar a la persona que realizo dichas modificaciones.

La configuracion puede definirse en 3 niveles (local, global, system) segun como gestionemos los proyectos. Algunos de los comandos que podemos usar para definir o verificar dicha configuracion son:

* __git init:__ inicializa un repositorio en la carpeta actual
* __git config user.name 'name':__ define el nombre de usuario
* __git config user.name 'email':__ define el correo de contacto
* __git config --list:__ muestra la configuracion general