# Comandos visto en la clase para administracion de servidores SSH

# Dentro de la terminal:

// SSH -V             -->Cheacamos version de SSH
// man SSH            -->Checar manual de SSH 
// cd ~/.ssh          -->Nos cambiamos a esa ruta
// ls                 -->La carpea esta vacia o con . ..
// ssh-keygen -t rsa -b 4096 -c gustavo.jaimes@my.unitec.edu.mx    -->Conectamos con la cuenta de github
## Nos pide una contraseña:         -->Esta contraseña puede ser diferente a la de github
// ls                  -->Visualizamos los archivos. Debe aparecer unos con id_rsa (llave completa) id_rsa.pub (Llave, la que nos sirve)
// nano o vi id_rsa.pub   -->Para visualizar el archivo
// eval "$(ssh-agent -s)"   -->Va y consulta todas las llaves, arroja Agent pid 2896
// ssh-add ~/.ssh/id_rsa      -->pide contraseña que pusimos a la llave

##Nos vamos a git hub -Menu -Setting -SSH and GPG Keys -boton "New ssh Key"

// Tittle:_Nombre_para_identificar_
#en linea de comandos, sacamos la llave del archivo id_rsa.pub con el archivo vi, cat, nano, more
//La llave la pegamos abajo de tittle     *Si la llave es negra no ha sido utilizada si es verde ya fue
// boton "ADD SSH KEY"

//Nos vamos a git   la pagina principal y creamos un repositorio.Public,  tiene que estar vacio  "Create repositorio"

##En la terminal nos vamos hasta nuestro escritorio
// Creamos una carpeta mkdir _administracion_      -->Creamos nuestra carpeta donde vamos a trabajar.
// cd _administracion_                            -->Nos cambiamos a la carpeta que creamos
// git init                                      -->Iniciamos proyecto en git
// ls
// touch README.md                              -->Creamos un archivo
// vi o nano README.md                          -->Agregamos contenido

// :W :q                                       -->Guardamos y salimos
// git add .                                   -->Agregar archivo
// git commit -m "first commit"                -->
// git remote add origin git@....              -->Comando para subir nestro contenido. Esta en la pag de git
// git push -u origin master                   -->Comando para subir contenido
   
      

