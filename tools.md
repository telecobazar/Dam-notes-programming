
 ## Comandos 
 -----------------------------
 ```
 aqui van los comandos 

 ```
 - ls: list files. Muestra el directorio
 - cd: change directory. Cambia de directorio.
 - mkdir: make directory (crear un directorio.)
 - rm: remove (quitar un archivo)
 - rmdir: remove directory (quitar un directorio solo si esta vacio)
 - rm -rf (**r**ecursive **f**orce) permite quitar un directorio aun teniendo contenido 
 - cat: concatenar archivos en la terminal mostrandolos por pantalla

## para git
-----------------------------

- clone
- commit
- status
- add (vigilar nuevos ficheros)
 git add-u(remove deleted files)
 - pull: download 
 - push: upload 
 - seq: secuencia de numeros 

 ## Comandos que unen

 - cat : concatenar archivos en la terminal.
 - paste: unir en vertical.
 - join: combinaciones. 

 ## Comandos que dividen

 - cut: corta vertical => cut -f1 -d" " -- se queda con la fila 1 separada por espacios
 - split: divide horizontal

 ## proceso para subir a git 

 - 1º->  cp -r ~/Documentos/apuntes/* .
 - 2º->  git status -- saldra si se ha modificado algo
 - 3º->  git commit -m "Initial commit "
 - 4º->  git add .
 - 5º->  git commit -m "Initial commit "
 - 6º->  git status --saldra si esta listo para hacer un push 
 - 7º->  git push
