# Generar el zip que instala el repositorio
1. Creamos una carpeta llamada repository.[NOMBRE]
2. Dentro de la carpeta y generamos un addon.xml que contenga dentro de la extension del addon (separados por <dir>), los diferentes repositorios que queramos enlazar (de esta forma al instalarlo recoge todas las fuentes de los repos como si fueran propias), y la metadata con las imagenes, nombres y descripciones de nuestro proyecto
3. Dentro de la carpeta y añadimos un icon y un fanart
4. Con el workflow generamos automaticamente en la carpeta raiz un .zip de la carpeta generada con el nombre repository.[NOMBRE]-[VERSION].zip y que lo publique en una web con un index.html e indicando en las settings del proyecto de GitHub que es una Page (para esto el proyecto tiene que ser publico)