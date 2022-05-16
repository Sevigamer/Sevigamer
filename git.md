#Ordenes de git

Para cambiar el nombre usamos el comando.
>git config --global user.name "nombre de usuario"

Para cambiar el correo es el siguiente comando.
>git config --global user.email correofalso@jmail.com

Para cambiar el editor de texto es.
>git config --global core.editor nano

Si queremos iniciar el repositorio se hace con el comando.
>git init

Para añadir los archivos que tenemos en la carpeta al repositorio hacemos.
>git add .

Usamos el comando anterior si queremos que se suba todo de golpe si no queremos eso tendremos que poner el nombre del archivo en vez del punto.
>git add fichero

Para saber el estado en que se encuentran nuestros archivos usamos el siguiente comando.
>git status

Para crear una rama usamos.
>git branch nombre_rama

Para fusionar las ramas usamos.
>git merge nombre_rama

Para clonar un repositorio.
>git clone url_repositorio

Para subir los cambios al repositorio hacemos un.
>git push nombre_rama_remoto nombre_rama_local
 
Si queremos ver los repositorios remotos hacemos.
>git remote -v
