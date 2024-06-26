
## EXAMEN DE RECUPERACIÓN LMSGI
- Queda prohibido el uso de IA
- Dispones de dos horas para realizarlo (hasta las 11:15)

## RA1, RA2, RA3: Páginas web HTML + CSS + JAVASCRIPT

### ESTILOS BODY (RA 1 - 2 PUNTOS)
- Crea un archivo `index.html` que contenga la división de `header`, `nav`, `main` y `footer`.
- Cambia la fuente de todo el documento HTML a una que te guste.

### ESTILOS HEADER (RA 1 - 2 PUNTOS)
- Dentro del apartado `header` incluye un título de nivel 1 donde ponga **Noticias de TUNOMBRE**.
- Añade estilos al `header` como un color de fondo.
- Cambio de tipografía para el título a una MUY distinta de la que tiene el resto del documento.
- Centra el título.
- Cambia el color del título a un color que combine y sea visible.
- Añádele sombra al texto.
- Da suficiente espacio para que no quede el texto agobiado.

### ESTILOS NAV (RA 1 - 4 PUNTOS)
- Incluye varios enlaces en el `nav` (no tienen por qué llevar a ningún sitio) y espárcelos al ancho de la pantalla mediante flex.
- Añade un color de fondo similar al del `header`.
- Cambia el color de los enlaces interiores a un color visible y que combine (te recomiendo blanco).
- Elimina el subrayado de los enlaces.
- Da suficiente espacio para que no quede el texto agobiado.

### ESTILOS FOOTER (RA1 - 2 PUNTOS)
- En el `footer` incluye una lista sin orden con enlaces a redes sociales: página principal de Facebook, Twitter e Instagram.

  ### ESTILOS MAIN (RA 2 - 10 PUNTOS)
- Incluye un título de nivel 3 que ponga **Noticias de la semana**.
- También en `main` debes incluir un divisor tipo flex.
- Dentro de dicho divisor flex, debes incluir 5 divisores más que contengan:
  - Una imagen relacionada con la noticia.
  - Un título `h4` con el nombre de la noticia.
  - Un `p` con una pequeña descripción de la noticia.
- El flex deberá hacer un salto de línea cuando la página web encoja.
- Dale estilo a los divs dentro del flex para que tengan formato tarjeta o card (box-shadow, border-radius...).
- Cuando pases el cursor por encima de las tarjetas estas se deben resaltar de alguna forma (algunas ideas: cambiar color de la sombra, añadir bordes de colores).
- Uno de los divs deberá tener un estilo distinto (color, color de sombra) algo que lo destaque. Ejemplos: para indicar que es una noticia de última hora, más leída, exclusiva...

### A TODA LA PÁGINA (RA 3 - 10 PUNTOS)
- Incluye el mostrar y ocultar un elemento mediante javascript, que incluya un mensaje de alerta de confirmación. - 7 PUNTOS
- También muestra la fecha y la hora actual en alguna esquina de la página web. - 2 PUNTOS
- Inlcluye al menos una librería externa de javascript - 1 punto

## RA 4 CREACIÓN Y VALIDACIÓN XML

### Ejercicio 1 - 3 punto
Creación de un Documento XML sobre un Libro. Escribe un documento XML que represente la información detallada de un libro. Este contiene un atributo ISBN para identificar de manera única el libro. Para representar la información completa de un libro se necesita conocer el título, autor del cual queremos saber nombre, apellidos y fecha de nacimiento, publicación que se compone de la fecha de publicación y editorial. También almacenaremos el género y este a su vez se compone de principal, subgénero. También de libro queremos seguir conociendo el idioma y el precio, que presenta un atributo moneda que expresa el precio.

### Ejercicio 2 - 3 punto
Realiza un DTD para el ejercicio 1 que valide el documento XML que has creado.

### Ejercicio 3 - 4 puntos
Realiza un XML Schema para el ejercicio 1 que valide el documento XML que has creado.

## RA 5 - CONSULTA Y ALMACENAMIENTO XML
### Ejercicio 1 - 4 puntos
Descarga el archivo videojuegos.xml que se encuentra dentro de este repositorio y añádelo a tu proyecto. Ahora vamos a procesar este fichero mediante un programa en Java. El programa deberá mostrar por pantalla los títulos de los juegos que tienen una calificación mayor a 8.

### Ejercicio 2 - 3 puntos
Realiza las siguientes consultas en XPath sobre el documento XML videojuegos.xml. Para ello crea un documento (Google Docs) e incluye captura de su funcionamiento en BaseX (debe aparecer tanto la consulta como el resultado de dicha consulta).

a) Seleccionar todos los títulos de los videojuegos
b) Seleccionar la calificación más alta
c) Seleccionar la fecha de lanzamiento más temprana
d) Seleccionar los videojuegos con calificación mayor a 8


### Ejercicio 2 - 3 puntos
Realiza las siguientes consultas en XQuery sobre el documento XML reservas_hotel.xml. Para ello crea continúa con el documento (Google Docs) e incluye captura de su funcionamiento en BaseX (debe aparecer tanto la consulta como el resultado de dicha consulta).

a) Obtener el nombre y la fecha de check-in de las reservas hechas para una habitación "Suite"
b) Listar los nombres de los clientes asignados a la "Suite 101", ordenados por fecha de check-in ascendente
c) Obtener los nombres de los clientes con una estancia mayor a 5 días

