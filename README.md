# Apuntes

Github y Git
¿Qué es Github y Git?
Github es una plataforma en la nubeque permite almacenar, gestionar y colaborar en proyectos de código usando el sistema de control de versiones de Git. En pocas palabras, es el lugar donde los desarrolladores trabajan juntos para crear software, compartirlo y mejorar su calidad. Git es un sistema de control de versiones distribuido creado por Linus Torvalds en  2005. Su proposito es ayudar a los desarrolladores a gestionar el historial de cambios en el codigo de un proyecto, permitiendo trabajar de forma colaborativa y segura. 

Comandos para Github
Git clone - Este comando lo que hace es que clona el repositorio que ha sido creado en Github, para que se pueda trabajar de forma local desde cualquier dispositivo que pertenezca al propietario.
Git add . - Lo que hace este comando es añade todos los archivos que se han creado para que a la hora de tener sincronizado tanto lo que se esta trabajando en local como en el repositorio que se encuentra en Github.
Git commit -m - Este comando sirve para poner a todos los archivos como si fuera en una carpeta invisible para que sea facil el poder enviar los archivos al repositorio. El apartado -m, lo que indica es que se pueda poner un nombre, indicando los cambios que se han realizado en general dentro de cada archivo.
Git push origin main - Este comando sirve para que una vez ya esta listo todo para poder enviar al repositorio. El apartado origin significa que se esta enviando desde el dispositivo al repositorio que se encuentra en Github.

Se vería de esta manera todos los comandos para realizar los comandos para poder tener sincronizado tanto el trabajo hecho en el dispositivo personal como en el repositorio
![Git clone](./imagenes/git%20clone.png)
![Git add](./imagenes/git%20add.png)
![Git commit](./imagenes/git%20commit.png)
![Git push](./imagenes/git%20push.png)

¿Qué es un Lenguaje de Marcas?

Es un sistema para anotar un documento de manera que se pueda estructurar, formatear o enlazar contenido de manera legible tanto para personas como máquinas. 
A diferencia de los lenguajes de programación, los lenguajes de marcas no ejecutan acciones por sí mismos, sino que estructuran o describen información usando etiquetas.

Lenguajes de Marca y su propósito principal:
1.	HTML (HyperText Markup Language): Crear y estructurar páginas web
2.	XML (eXtensible Markup Language): Almacenar y transportar datos de manera estructurada, usando en la interoperabilidad de sistemas y aplicaciones.
3.	Markdown: Formatear texto de manera sencilla y rápida, especialmente en archivos README, blogs o foro

Markdown
Podemos crear un archivo de texto plano con varias extensiones para archivos de Markdown dependiendo del destino del archivo.

Etiquetas de markdown
•	Encabezados: Llevan ya asociado un estilo por defecto cada uno y sirven para iniciar sesiones en los documentos:
#H1
##H2
###H3
####H4
#####H5
######H6

•	Estilos de letra
1.	Itálica o cursiva: *texto* o _texto_
2.	Negrita: __texto__
3.	Tachado: 

•	Anidar estilos: **palabra1 _palabra2_**

Etiquetas Markdown
•	Enlaces:
[link](https://www.google.es/ “Enlace a Google”)

•	Imagen:
![DBS manga](./imagenes/dbs%20manga.jpg)

•	Tablas:
|Columna1|Columna2|Columna3|
Para poder centrar el texto hay que poner : al principio y al final de la columna, para alinear el texto a la izquierda hay que poner : al principio y para alinear el texto a la derecha hay que poner : al final

Introducción a HTML

•	HTML (HyperText Markup Language) es un lenguaje de marcado estándar para crear páginas web
•	HTML define la estructura y el contenido de las páginas web mediante etiquetas.
•	Etiquetas de apertura: consiste en el nombre del elemento, encerrado por un paréntesis angular (<)
•	Etiquetas de cierre: consiste en el nombre del elemento, encerrado por una barra y un paréntesis angular (/>)
•	Estructura básica de un fichero HTML: Para empezar, hay que poner una declaración DOCTYPE, seguido por HTML para decirle al usuario que este fichero va a ser HTML. La etiqueta head, contiene metadatos, enlaces a hojas de estilo y scripts, pero nunca se va a ver cuándo se acceda a este documento HTML.
•	La etiqueta meta charset: significa que cantidad de caracteres especiales va a tener la página de HTML
•	La etiqueta link rel: hace que buscar en tu dispositivo aquel documento que quieras tener enlazado a la página de HTML que estemos creando
•	Etiquetas importantes de HTML:
o	<h1 a 6>: son las etiquetas de encabezado
o	<p>: es la etiqueta para poner un párrafo
o	<strong>: es la etiqueta para poner un texto en negrita
o	<img>: es la etiqueta para poner una foto en la página web
o	<br>: es una etiqueta para que al acabar un párrafo haya un salto de linea
o	<!-- -->: es una etiqueta para poder añadir comentarios en la página web pero que no se muestra
o	<hr>: permite agregar una linea horizontal divisora que es útil para separar visualmente párrafos
o	<em>: hace que un texto sea resaltante con énfasis 
o	<ol>: es una etiqueta que sigue un listado de forma ordenada
o	<ul>: es una etiqueta que sigue un listado de forma desordenada
o	<li>: es la etiqueta que dependiendo si esta ordenada o desordenada, lo clasifica como una lista
o	<a href>: es la etiqueta para poder moverse internamente de una página a otra
o	<a href id>: es la etiqueta para poner un enlace a un sitio que coincida con ese id y sobre todo que tenga un # delante del id

Validar código HTML/Markdown
https://validator.w3.org
Este validador de HTML/Markdown lo que hace es que lee todo el código que tiene el HTML que ha sido asignado para validar y devuelve todo lo que este correcto y proporciona los errores que contiene el código para poder corregirlo 

Contenedores, formularios y tablas
Contenedores
Para crear el contenedor se ha de usar la etiqueta <div>.
Ejemplos de elementos semánticos: <header>, <footer>, <article>, <section>, <nav> y <figure>

Formularios
La etiqueta para crear un formulario es <form>.
Los atributos que son necesarios para que tenga el formulario son: 
1.	Action
2.	Method
3.	Get
4.	Post
5.	Target
6.	Type
7.	Id
8.	Input
9.	Name
10.	Value
11.	Placeholder
12.	Required
13.	Desable
14.	Readonly

Textarea
1.	Name
2.	Id
3.	Rows
4.	Cols
5.	Placeholder

Etiquetas de tablas
1.	Table
2.	Thead
3.	Tbody
4.	Tfoot
5.	Border
6.	Width
7.	Th
8.	Tr
9.	Td
10.	Align
11.	Bgcolor

CSS
Es un archivo donde se puede añadir diseño a la página web para que tenga una apariencia bonita. Es un lenguaje sencillo, donde a nivel de diseño es mucho mejor que las etiquetas mismas de HTML.
En cualquier etiqueta HTML, se le puede poner estilo dentro de la misma etiqueta de apertura, hará que todo lo que este en esa etiqueta haga lo que le pida ese estilo. Para que los estilos se apliquen a todas las partes que se encuentran en la cabecera, se indican en una etiqueta denominada <style> y dentro de esa etiqueta, todo lo que se le indica a la hora de recorrer todo el código, pues lo que a la hora de montar la página web cada cosa que tenga marcado en la etiqueta <style> lo va a poner tal y como se indica. También hay otro método para poder poner un archivo css de forma externa, pues dependiendo de donde se encuentra puede afectar directamente a toda la página web. Para poner los comentarios en CSS, se usa la nomenclatura /* Esto es un comentario en CSS*/
