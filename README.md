# ComandosGIT
------------------------------------------Comandos seteando proyecto por primera vez------------------------------
git init //inicializa git en el repositorio local
git remote add origin https://github.com/hernang91188/PalabraFinal.git (para vincular el repositorio online al local. se hace 1 vez). para usar claves ssh con github seguir https://kbroman.org/github_tutorial/pages/first_time.html
nos paramos en la carpeta del proyecto con git bach y ejecutamos 
------------------------------------------Comandos seteando proyecto por primera vez------------------------------
ahora se pueden usar comandos git sobre la carpeta
git config --global user.name 'hernan gaona'
git config --global user.email 'hernang9188@gmail.com'
git add archivo.xml //agrega el archivo.xml a staging area. git add *.*  //agrega el directorio entero a staging area
git status //muestra el archivo en staging area y archivos no trackeados
git rm --cached archivo.xml (remueve el archivo de staging area)
git commit -m 'comentario' //commitea los cambios en staging a la rama en la q estemos parados
//se creamos en archivo .gitignore y agregamos ahi nombres de archivos, git no los tiene en cuenta al evaluar cambios
git branch nombreDelBranch //crea una ramma nueva  
git checkout nombreDelBranch//nos paramos en ese branch
git merge nombreDelBranch //parados en la rama de destino, mergea los cambios de nombreDelBranch a la rama en la q estamos parados 
git push -u origin nombreDelBranch //pushea a la web los cambios de la rama nombreDelBranch (hay q estar parado en la rama a pushear para hacerlo)
git log //muestra el log de commits para la rama en la q estoy parado

git branch -d localBranchName// delete branch locally
git push origin --delete remoteBranchName // delete branch remotely
