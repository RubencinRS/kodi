# Generar el zip que instala el repositorio
1. Creamos una carpeta llamada repository.[NOMBRE]
2. Dentro de la carpeta y generamos un addon.xml que apunte al addons.xml y el addons.xml.md5 de la carpeta raiz (para esto el proyecto tiene que ser público), y la metadata con las imagenes y nombres/descripciones
3. Dentro de la carpeta y añadimos un icon y un fanart
4. Con el workflow generamos automaticamente en la carpeta raiz un .zip de la carpeta generada con el nombre repository.[NOMBRE]-[VERSION].zip
5. Publicamos el .zip en una web con un index.html e indicando en las settings del proyecto de GitHub que es una Page y que haga el deploy

# Generar los repositorios internos y los addons internos
1. Generamos un addons.xml en la carpeta raiz en el que indicamos lo que va a tener el repositorio instalado (repositorio remoto o addon)
2. Con el workflow generamos automaticamente el fichero addons.xml.md5
