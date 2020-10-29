# IDS-Clase-git-github
**_Proyecto para practicar comandos de git para la clase de IDS_**

# **Comandos**

# git init 
Sirve para inicializar un Proyecto nuevo (crea un repositorio local en tu ordenador)

# git status
Sirve para ver el estado de nuestros archivos (los archivos que tenemos o que se estan trabajando)

# git add 
Agrega un archivo al staging area. 
### *sinstaxis* 
git add nombre del archivo 

# git add .
Agrega todos los archivos al staging area.

# git commit 
Para crear un primer punto de control de nuestro código

### *sinstaxis* 
git commit -m "Mensaje para el commit" 

# git config --global user.email
Para configurar el email del usuario que va a usar el repositorio 

### *sinstaxis* 
git config --global user.email"email del usuario"

# git config --global user.name 
Para configurar el nombre del usuario que va a usar el repositorio

### *sinstaxis* 
git config --global user.name"nombre del usuario"

# git log 
Sirve para ver todos los commits que se han creado 

# git checkout --
Sirve para revertir los cambios de los archivos 

### *sinstaxis* 
git checkout -- nombre del archivo

# git diff
Sirve para ver las diferencias hechas en los archivos 

### *sinstaxis* 
git diff nombre del archivo

# git branch
Muestra las ramas que existen en el repositorio 

# git branch nombre_de_rama
Crea una nueva rama del proyecto con el nombre que se coloque

# git checkout nombre_de_rama
Se mueve a la rama que seleccione en nombre_de _rama

# git remote add origin link_del_proyecto 
Conecta tu repositorio local con un repositorio online en github 

# git push -u origin main 
Carga tu repositorio local al repositorio de github 

# git clone link_del_repositorio 
Crea una copia del proyecto en tu ordenador

# .gitignore 
Es un archivo donde se colocan archivos o carpetas que no se quieran agregar al entorno de trabajo

>https://www.youtube.com/watch?v=HiXLkL42tMU&ab_channel=Fazt


### Crear una llave ssh
ssh-keygen -t rsa -b 4096 -C "Message"
