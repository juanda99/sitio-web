# sitio-web
Práctica realización sitio web mediante framework Bootstrap

## Introducción
La web tratará de un tema libre que deberá tener un mínimo de 4 páginas web donde figurarán entre otros los siguientes apartados:
- Presentación de empresa, asociación, etc.
- Página con los servicios, portfolio, actividades... según naturaleza del sitio web.
- Formulario de contacto con al menos los siguientes campos: nombre, teléfono de contacto, email, mensaje. 
- Multimedia con al menos un video y 10 imágenes.
- Acceso a redes sociales
- Menú de navegación de un máximo de 2 niveles.
- Enlace a un doc en algún lugar visible de la página donde aparezcan detallados los recursos técnicos utilizados:
    - Fuentes google utilizadas
    - Paleta de colores
    - Framework CSS...
   
##Diseño
- Uso de una paleta de colores.
- Consistencia en el diseño de cada página del sitio.
- Uso de fuentes según Google Fonts.
- Es obligatorio usar less para el diseño.
- Diseño responsivo de toda la página: video, menú, imágenes, texto...
- Uso de media queries o código en servidor para que la página se visualice en al menos 3 perfiles de dispositivos diferentes (movil, tablet y PC). El viewport deberá ser de la anchura del dispositivo.
- Criterio mobile first.
- Se deben utilizar un conjunto de iconos para mejorar la estética general de la página (por ej. iconos de facebook, google+ o similar). Se puede utilizar una librería ya existente como http://fortawesome.github.io/Font-Awesome/ o utilizar una propia. 
- Se valorará utilizar algún plugin de jQuery para hacer un slider en la cabecera de las páginas, mostrar las fotos a tamaño superior, uso de un mapa de Google, etc.

## Tiempo de carga
- Las imágenes deberán estar en la resolución mínima necesaria.
- Las imágenes tendrán que estar optimizadas para la resolución proporcionada.
- Los css y js tendrán que estar minified y minimizando el número de http requests para la versión de producción.
- El html tendrá que estar minified para la versión de producción.
- Se debe valorar el uso de algún CDN.
- Se comprobará el desarrollo correcto de este área mediante Google PageSpeed.
- Uso de sprites para los iconos del sitio web

## Código
- El sitio web deberá tener una estructura clara y concisa.
- El código html estará minified en producción.
- El código css y js estará minified en producción.
- Se valorará el uso de soluciones como normalize.css, modernizr, y en general cualquier otra solución que aparece en html boilerplate
- Todo el código css y js deberá ir en ficheros externos (nunca en el html)
- Se minimizará el número de accesos a ficheros css y js externos, pudiendose valorar el uso de CDNs
- Se validará el código según la W3C. 
- El código del proyecto se realizará a partir de un fork de este repositorio. Tendrá que haber al menos 5 commmits en 3 días diferentes y la versión de producción se colgará en el servidor infenlaces de modo que sea accesible navegando desde www.infenlaces.com
