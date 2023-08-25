
<h2> H-1 (ENVIAR UN COMMIT AL REPOSITORIO REMOTO) 👀👀👀</h2> 


Crear un nuevo repositorio en github nombre: git_h-1

1.Crear un repositorio local

> git init 

2.Registrar el repositorio remoto con tú repositorio local

>git remote add origin (pegar_la_ruta_del_repositorio_local)

3.Verificamos la ruta remota

>git remote -v

4.Crear un archivo llamado lista_de_usuarios.txt

>touch lista_de_usuarios.txt

5.Examinar la creación del archivo

>ls -l

6.Agregar el archivo lista_de_usuarios.txt al stage(marcarlos para commitear)

>git add lista_de_usuarios.txt

7.Verificamos el status

>git status

8.Se realiza el commit

>git commit -m "feat: add lista_de_usuarios.txt"

9.Verificamos el commit

>git log --oneline

10.Hacemos push

>git push -u origin master

11.Verificamos el repositorio remoto en github para ver el push enviado



