## WEB SCRAPING ELPAIS.COM

### Mini proyecto de scraping en NodeJS para extraer titulares de elpais.com:
<ol>
<li>Primero haciendo una petición del HTML de la página de elpais.com con Axios</li>
<li>Después convirtiendo ese HTML a una estructura de DOM</li>
<li>Extraer todos los elementos que queremos de esa estructura de DOM:</li>
 
<ul>
<li>título</li>
<li>entradilla</li>
<li>imagen</li>
<li>link</li>
</ul>
<li>Guardamos los 20 primeros titulares en un JSON en el disco</li>
<li>Terminamos guardando los titulares y resto de elementos en un archivo JSON con File System (fs)
</ol>

