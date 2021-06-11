#Playground GitHub

------ Cheat Sheet ------
 
git add -A  -> Agregar todos los cambios que hemos realizado en nuestra rama.
 
git commit -m "tu mensaje va aquí" -> Agregamos los cambios realizados en nuetra rama.

git pull   -> Descargamos los cambios que haya en la rama Master/main.
 
git push -> Subimos los cambios a la rama Master/main.

git push origin master -> Enviamos los cambios al repositorio remoto

git branch -> nos muestra las ramas que tenemos.

git branch name -> Creamos una nueva rama con el nombre que definimos, por ejemplo: "git branch fox" nos creara una rama llamada "fox".

git branch -d name -> borramos la rama desea, por ejemplo: "git branch -d fox" borramos la rama "fox".

git checkout -> Nos permite movernos entre ramas.

------ Cheat command ------

git checkout -b name -> Creamos una rama nueva y nos movemos a esta al crearla.
---------------------------

git merge name -> nos permite mezclar dos ramas, para este comando nos tenemos que posicionar en la rama que queremos cambiar
y llamamos el comando.

git clone url -> clonamos un repositorio destino, por ejemplo: "git clone www.github.con/usuario/playground"www.github.con/usuario/playground

------ Trabajar entre ramas ------

Primero clonaremos el repositorio que necesitamos, para eso nos debemos posicionar en la carpeta que queremos clonarlo
y usaremos este comando:

git clone https://github.com/HectorAlrz/playground-github.git

Una vez que tengamos el repositorio local, debemos crear una rama de trabajo:

git branch hectoralrz 

Cambiamos a la rama que creamos:

git checkout hectoralrz

Supongamos que trabajamos en el proyeto sobre nuestra rama, debemos realizar lo siguiente

git add -A 

git commi -m "Modificación de index.html"

git pull

git push  origin master
>>>>>>> hectoralcaraz
