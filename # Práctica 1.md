# Práctica 1

## Prueba de comandos 

## git clone https://github.com/gitt-3-pat/hello-world
[//]: # (Mediante este comando copiamos el respositorio dado en la carpeta en cuya ruta nos encontramos en la ventana de comandos.)
>>
Cloning into 'hello-world'...
remote: Enumerating objects: 38, done.
remote: Counting objects: 100% (38/38), done.
remote: Compressing objects: 100% (23/23), done.
remote: Total 38 (delta 1), reused 31 (delta 0), pack-reused 0
Receiving objects: 100% (38/38), 58.97 KiB | 1.68 MiB/s, done.
Resolving deltas: 100% (1/1), done.

## git status
[//]: # (Mediante este comando consultamos el estado en el que está nuestro repositorio)
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

## git add .
[//]: # (Este comando es necesario antes de realizar un push o comit, para indicar que has realizado cambios en el repositorio)

## git commit -m "Prueba  git commit -m "Prueba del comando git comit"
[//]: # (Mediante este comando guardamos los cambios realizados en el repositorio y añadimos el mensaje deseado, cuyo contenido se mostrará en github.)
[main 54c14a1] Prueba del comando git comit
 1 file changed, 22 insertions(+)
 create mode 100644 "# Pr\303\241ctica 1.md"del comando git comit"
[main 54c14a1] Prueba del comando git comit
 1 file changed, 22 insertions(+)
 create mode 100644 "# Pr\303\241ctica 1.md"

 ## git push 
 [//]: # (Con este comando mandamos nuestro repositorio a github.)

 ## git checkout -b feature/1
 [//]: # (Usando este comando creamos la rama feature y nos movemos a ella.)
Switched to a new branch 'feature/1'

## git checkout main
[//]: # (Mediante este comando nos movemos a la rama original.)
Switched to branch 'main'
M       "# Pr\303\241ctica 1.md"
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)
