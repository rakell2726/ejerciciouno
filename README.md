Prework
*instalaciones Necesarias
-Visual code: Es un editor de código fuente.
-Git: Es una aplicación para entornos.
-Wakatime: Control de tiempo de programación.
-Github: Sistema de conrol de versiones (VCS).



* Comandos

pwd: Me permite conocer la ruta actual (Donde estoy ubicado).

ls: Ver los elementos de la carpeta donde estoy ubicado.

clear: Limpiar la pantalla.

ls -la: Ver detalle de la información con los permisos que tienen esos recursos.

mkdir: Crear un directorio.

rm – rf [nombre directorio]: Borrar de forma forzosa el recurso.

cd [carpeta]: Dirigirme a una carpeta deseada.

cd ..: Devolverme a una ruta o carpeta anterior.

touch [NombreNuevoArchivo] : Crear un archivo de cualquier tipo distinto a una carpeta.

nano [NombreNuevoArchivo] : Crear un archivo.

cat [NombreNuevoArchivo] : Mostrar los datos de un archivo.

*Git
- Para iniciar se debe configurar el nombre y correo.

git config --global user.name "Nombre Completo"
git config --global user.email "email@example.com"

-Comandos mas utilizados

git init : este comando se encarga de iniciar el repositorio (esto va a crear una carpeta oculta .git en la carpeta donde ejecutes este comando).
git add . : Prepara los archivos para el commit .
git commit -m <descripción de los cambios> : Crea un commit a partir de los cambios que están en el index con el mensaje que se le pase a la opción -m .
git status : Muestra la lista de archivos con cambios desde el último commit y los que van a ser incluídos en el siguiente commit.
git remote add origin <URL repositorio> : Indicar la dirección del repositorio
git push origin <Raman main> : Entregar los cambios
git pull origin <Raman main> : Bajar los cambios



