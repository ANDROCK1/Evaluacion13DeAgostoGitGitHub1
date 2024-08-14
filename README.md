# Evaluacion13DeAgostoGitGitHub1

1 cd .. 
>se utiliza para retoceder

cd 
> se utiliza para volver a la raiz


2 ls
> su utiliza para listar los archivos

ls all
>muestra todas las listas de archivos

mkdir
>para crear un nuevo directorio en el archivo

touch
>crear un archivo vacio

pwd
>se utiliza para mostrar directorio actual


3
>El primer paso es configurar el nombre de usuario.
Configurar el nombre de usuario
git config --global user.name "Nombre de Usuario"
El segundo paso es configurar el correo electrónico.
 Configurar el correo electrónico
git config --global user.email correo@correo.com
Recomiendo cambiar la rama principal de `master` a `main`.
 Cambiar el nombre de la rama principal
git config --global init.defaultBranch main
Verificar la configuración realizada.
#Verificar la configuración realizada
git config --list

4
> Agregar archivos al área de preparación
1 git add <archivo>
Confirmar cambios
2 git commit -m "Mensaje del commit"
3 Agregar y confirmar cambios
git commit -am "Mensaje del commit"
4 Modificar el mensaje del último commit
Git & GitHub I2git commit --amend -m "Nuevo mensaje"
5 Ver el estado de los archivos
git status
6 Ver el historial de cambios
git log

5
>pull request es una solicitud para los cambios realizados y permite ver los cambios realizados para el publico