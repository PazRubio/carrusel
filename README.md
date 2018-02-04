
# Carrusel y mejora de la interactividad

En esta práctica hemos trabajado sobre la página de moda de Gema de la Fuente y Álvar Ruiz para mejorar y añadir interactividad.


## Secciones y modificaciones

### 1. Carrusel
Sobre la idea de la página en la que situábamos un carrusel al inicio, hemos implementado éste siguiendo el tutorial de youtube [Como hacer un Slider](https://www.youtube.com/watch?v=uzLabNV0rmQ). La parte correspondiente al CSS de este apartad está en el archivo css/slider_style.css, donde definimos tamaños, fuentes, colores, etc. En cuanto al movimiento de éste, lo implementamos en javascript, js/main.js, donde recogemos el número de imágenes, ocultamos todas menos la primera, y jugamos con la visibilidad de éstas, pasando de una a otra imágen de forma automática. También añadimos dos flechas para pasar adelante y atrás, funciones definidas en nextSlider y prevSlider, y una serie de puntos debajo de las imágenes para ir diréctamente a una imagen del carrusel, con la función pagination.

### 2. Estilos de la página
En cuanto a los estilos, hemos continuado dando a la página los mismo tonos y mantenido la disposición de ésta. El encabezado se hace más pequeño dejando paso a un menu desplegable que mantiene el mismo fondo y las mismas tonalidades al pasar el ratón. Las imágenes, que al hacer scroll aparecen por ambos lados, contienen un pie de imagen también en tonos azules. 

### 3. Interactividad al hacer scroll
El efecto de scroll está también implementado con css y javascript. En el fichero css/scroll_style.css definimos los estilos de las imágenes y las animaciones de éstas, especificando el sentido, tiempo y lugar final de cada animación (derecha e izquierda). En js/main.js definimos la funcion check if in view que controla cuándo se hace scroll y añade la clase in view, la correspondiente al estilo final que toman las imágenes. La animación del scroll está basada en el siguiente [codepen](https://codepen.io/SitePoint/pen/MwEaQM). 

### 4. Interactividad del menú de navegación.
Mantenemos el header anterior, pero al hacer scroll éste desaparece y se queda fijado a la parte superior únicamente el menú; esto lo hacemos simplemente añadiendo una clase llamada "fijo" con javascript cuando el scroll llega a 350 píxeles y eliminandola al hacer el scroll inverso, y a esta clase le damos una posición fija y otros estilos en la hoja de estilos css/scroll_style.css.
Además, a este menú le hemos añadido subopciones, y al pasar el ratón por encima de cada sección ésta se marca en un tono azulado y se subraya, además de desplegarse un submenú que se comporta de igual manera.

### 5. Interactividad de las imágenes
En cuanto a las imágenes hemos incorporado varios pequeños detalles al hacer hover. En un principio, las imágenes aparecen con un tono blanquecino, que al poner el ratón encima se vuelve del todo opaca y se desplaza suavemente hacia arriba dejando paso a un menu de pie de imágen. Este menú contiene el nombre del sector al que hace referencia y una nota con algo más de información. En el hueco de la derecha, aparecen un corazón que se puede marcar y desmarcar, un carrito que al pasar por encima se balancea y un botón paar dejar un comentario que hace zoom-in. Todo esto está implementado en css/anima_imagenes.css. 

### 6. Aviso de uso de cookies
El estilo de cookies está definido en el fichero css/slider_style.css, y el funcionamiento de éstas en js/main.js.

### 7. Microinteracciones
En relación con este apartado, hemos ido añadiendo en los puntos anteriores ciertas microinteracciones. Estas son, por ejemplo, el cambio e color y subrayado del menú desplegable; el cambio de la imagen del carrusel a través de los puntos girises/azules debajo del mismo, las distintas animaciones del pie de imagen (cambio de color y aumento del tamaño de tamaño del corazón, balanceo del carrito, zoom-in del botón), y cambio de opacidad y desplazamiento hacia arriba de la imagen a la vez que se muestra el pie de imagen.

### 8. Subida a github
* Enlace a este propio proyecto: https://github.com/LexaHunter/carrusel
* Enlace a github pages: https://lexahunter.github.io/carrusel/index.html

#### Autores

* **Alvar Ruiz** - [Github](https://github.com/alvar-ruiz)
* **Paz Rubio** - [Github](https://github.com/LexaHunter)

