# Proyecto-GIT 2021
(❍ᴥ❍ʋ)->Proyecto para aprender git y github
## Apuntes
´´´
⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸
Introducción a git
● Git es una herramienta de código abierto que la inició Linus Torvalds, el
creador (al menos en sus inicios) de Linux.

● Una ventaja de Git es que un sólo programa puede ser trabajado
simultáneamente por varios desarrolladores.

● Git se basa en el concepto de repositorio.

● Cada uno de los desarrolladores tendrá su propio repositorio de forma local,
pero tendremos el control cada vez que hagamos un cambio en el código.

● Podremos acceder a versiones anteriores del mismo y podemos revertircambios.
⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸

⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸
Introducción a git

● Podemos utilizar repositorios locales y remotos.
● Git nos permite obtener “fotografías” o snapshots del código.
● El ciclo básico de uso de Git es el siguiente:
⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸

⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸
git Instalación Instalar git
● https://git-scm.com/git
⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸

⫸
Iniciar el área de trabajo Instalar git;

● git init: vamos a crear un proyecto nuevo.
● git add <archivo>: añadimos un archivo del working directory al staging
area.
● git status: Vemos en qué estatus se encuentran los archivos.
git
Añadir archivos
Instalar git
● git init: vamos a crear un proyecto nuevo.
● git add <archivo>: añadimos un archivo del working directory al staging
area.
● git status: Vemos en qué estatus se encuentran los archivos.
git

⫸⫸⫸⫸⫸Configuracion Importante ⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸
Configuración

Configuración
● git config --global user.email “tucorreo@tuservicio.com”
● git config --global user.name “tu_usuario”
● git commit
git
⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸

⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸
Regresar un cambio y ver las diferencias
Regresar un cambio y ver la diferencia
● git checkout -- index.html
● git diff index.html
⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸

⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸
git Control de versiones
Segundo commit
● Si deseamos nuevamente hacer un commit con los cambios,
● Debemos añadir nuevamente el archivo con add y luego commit.
● git commit -m “Version 0.0.2”
● Volver a dar log: ya se tienen dos commit, el ultimo es head-master
git
⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸

⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸Git-Ignore⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸
Ignorar archivo a subirlo
Ignorar archivo a subirlo
● Añadir una carpeta y un archivo.
● Status se ve en rojo
● Agregar el archivo .gitignore
● Nombre de la carpeta
● git status
● Rojo .gitignore
● Git commit -m “he agregado el .gitignore”

⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸RAMAS⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸
git
Crear ramas (branch)
Crear ramas (branch)
● Git branch
● Una sola rama
● Git branch login: creas la rama login
● Git branch
● Git checkout login: me cambio a la rama login
● Git status: los cambios en rojo
● Git add . añade todos
● Git commit -m “version alternativa con
● Estamos en login
● Git checkout master
● Git log
●
⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸

⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸
Crear repositorio en Github
Crear repositorios en github
● Entrar a github.com
git
Sincronizar git con github
Sincronizar git con github
● git remote add origin https://github.com/pakoarce/proyecto-git.git
● git push -u origin master
git

⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸⫸
