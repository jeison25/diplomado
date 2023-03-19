# diplomado

1. ¿Como clonar un repositorio?
- Primero se debe crear el repositorio en github desde la siguiente opción:  



- Una vez creado se generará una url, esa es la que se debe colocar desde consola usando git bash here, se debe tener en cuenta que la carpeta local donde se clonará el repositorio debe existir en el computador. 



- Para clonar un repositorio se debe usar el siguiente comando: 
  git clone urlRepositorio 



- Se evidencia el repositorio clonado: 


Desde GitHub Desktop se puede establecer conexión con terminales de texto y terminales como cmd para realizar cambios. Desde la aplicación se tiene un ambiente más amigable.


Creación de un repositorio
Puede almacenar distintos proyectos en repositorios de GitHub, incluidos proyectos de código abierto. Con los proyectos de código abierto, puedes compartir el código para mejorar el software y hacerlo más fiable. Puedes utilizar los repositorios para colaborar con otros y rastrear tu trabajo. Para más información, vea "Acerca de los repositorios". Para obtener más información acerca de los proyectos de código abierto, visita OpenSource.org.

Notas:

Puedes crear repositorios públicos para un proyecto de código abierto. A la hora de crear el repositorio público, asegúrese de incluir un archivo de licencia que determine cómo quiere que se comparta el proyecto con otros usuarios. Para más información sobre el código abierto, en concreto cómo crear e incrementar un proyecto de código abierto, hemos creado Guías de código abierto que le ayudarán a desarrollar una comunidad de código abierto con la recomendación de procedimientos recomendados para crear y mantener repositorios para un proyecto de código abierto.
También puede tomar un curso gratuito de GitHub Skills sobre el mantenimiento de comunidades de código abierto.
También puedes agregar archivos de estado de la comunidad a los repositorios para establecer instrucciones sobre cómo contribuir, velar por la seguridad de los repositorios y mucho más. Para más información, vea "Creación de un archivo de estado de la comunidad predeterminado".
En la esquina superior derecha de cualquier página, utiliza el menú desplegable  y selecciona New repository (Nuevo repositorio).
Menú desplegable con opción para crear un repositorio
Escriba un nombre corto y fácil de recordar para el repositorio. Por ejemplo: "hola-mundo".
Campo para proporcionar un nombre para el repositorio
Opcionalmente, puede agregar una descripción del repositorio. Por ejemplo, "Mi primer repositorio en GitHub".
Campo para escribir una descripción del repositorio
1. Elige la visibilidad del repositorio. Para más información, vea "Acerca de los repositorios".
Botones de radio para seleccionar la visibilidad del repositorio
1. Seleccione Initialize this repository with a README (Inicializar este repositorio con un archivo Léame).
Inicializar este repositorio con una casilla archivo Léame
1. Haga clic en Create repository (Crear repositorio).
Botón para crear un repositorio
Felicidades. Ha creado correctamente su primer repositorio y lo has inicializado con un archivo Léame.

# Imagenes github
[![thumb2-github-blue-logo-4k.jpg](https://i.postimg.cc/BvLTG4Dt/thumb2-github-blue-logo-4k.jpg)](https://postimg.cc/DWhJrVxK)


# Comandos GIT

[![comandos-git.png](https://i.postimg.cc/xCn9yMwK/comandos-git.png)](https://postimg.cc/v12RGgHB)

Este artículo proporciona una lista de los comandos GIT más usados, una breve descripción de ellos y ejemplos de su uso. Para una descripción detallada de todos los comandos GIT, comprueba esta

# git config #

Establece valores de configuración para tu usuario, email, gpg key, algoritmo diff preferido, formatos de archivo y más. Ejemplos:

- git config --global user.name "Mi nombre"
- git config --global user.email "usuario@dominio.com"

# 1git init #

Inicializa un repositorio git – crea el directorio .git inicial en un proyecto nuevo o existente. Ejemplo:

- git init
 
- Initialized empty Git repository in /home/username/GIT/.git/
  
# git clone #

Crea una copia de repositorio GIT de una fuente externa. También añade la ubicación original como remota de modo que puedas traerlo de nuevo y lanzarlo si tienes permisos. Ejemplo:

- git clone git@github.com:user/test.git

# git add #

Añade cambios de archivos en tu directorio de ensayo a tu index. Ejemplo:

- git add .

# git rm #

Elimina archivos de tu index y de tu directorio de ensayo para que no se rastreen. Ejemplo:

- git rm filename

# git commit #

Toma todos los cambios escritos en el index, crea un nuevo objeto de confirmación que apunta a él y establece la rama para que apunte a esa nueva confirmación. Ejemplos:

- git commit -m ‘committing added changes’
- git commit -a -m ‘committing all changes, equals to git add and git commit’

# git status #

Te muestra el estado de los archivos en el index en comparación con los del directorio de trabajo. Enumerará los archivos que no están rastreados (solo en su directorio de trabajo), modificados (rastreados pero aún no actualizados en tu index), y almacenados (añadidos a tu index y listos para comprometerse). Ejemplo:

- git status
 
- On branch master 
- Initial commit 
- Untracked files: 
- (use "git add <file>..." to include in what will be committed) 
 
- README



