# Qué es Git?

Es un sistema de control de versiones que administra las distintas versiones de un programa.

- Es un sistema de control distribuido.
- Ayuda a coordinar el trabajo entre los multiples desarrolladores.
- Mantiene un registro de quién y cuando se realizan cambios.
- Tiene la caracteristica de poder revertir cambios en cualquier momento.
- Nos brinda la capacidad de mantener nuestro repositorio de proyectos de forma local y remota.

# Conceptos básicos:

- Working directory: Nuestra áre de trabajo.
- Staging area: Área donde estarán nuestros archivos listos para ser guardados.
- Repository: Donde se encontrarán todos los archivos guardados.

# Comandos básicos:

- git init: Para inicializar un repositorio de proyecto local.
- git add "file"/git add .: Para pasar nuestros archivos del "woking dir" al "staging area".
- git status: Para ver en que estado están nuestros archivos, si están en el "working dir" o "staging area".
- git commit/git commit -m "mensaje": Para guardar nuestros archivos del "staging area" en el repositorio local, con esto crearemos un "snapshot".
- git log: Muestra un registro de commits, su hash y respectivo mensaje.
- git diff "file": Para comparar las diferencias de un archivo con sus versiones anteriores.
- git branch "rama": Crea una rama nueva.
- git branch: Muestra las ramas existentes en nuestro repositorio.
- git checkout "rama": para moverse entre ramas y poder trabajar sobre ellas de forma especifica.
- git push: Para subir nuestros cambios del repositorio local al repositorio remoto(en la nube).
- git pull: Para traer los cambios que contenga el repositorio remoto a nuestro repositorio local.
- git clone: Para hacer una copia de un repositorio remoto de forma local.

# Comandos para subir nuestro proyecto a nuestro repositorio en la nube.
- git remote add origin "link del repositorio remoto".
- git push -u origin master

# Donde descargar git:

https://www.git-scm.com
