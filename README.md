# Mis apuntes

<strong>Para crear un repositorio de GitHub en tu PC local:</strong>
1. Copia la URL del repositorio que has creado en GitHub.
2. En tu PC, selecciona una carpeta donde quieras clonar el repositorio.
3. Ejecuta el siguiente comando en la terminal:  
   <code>git clone <URL del repositorio de GitHub></code>
4. Esto descargará automáticamente el repositorio en la carpeta seleccionada.

<strong>Guardar y subir los cambios:</strong>
1. Para guardar los cambios en tu código, usa el siguiente comando:  
   <code>git commit -m "Mensaje descriptivo sobre los cambios"</code>
2. Luego, para subir los cambios a GitHub, usa el comando:  
   <code>git push origin main</code>  
   Este comando sube todos los cambios realizados a la rama principal de tu repositorio en GitHub.

<h2>Markdown:</h2>
<strong>Crear una tabla</strong>
Para crear una tabla en el archivo <code>README.md</code>, utiliza el siguiente formato:

<pre>
| Columna 1 | Columna 2 | Columna 3 |
|-----------|-----------|-----------|
| Valor 1   | Valor 2   | Valor 3   |
</pre>
Este código generará una tabla con tres columnas.

<strong>Texto en negrita</strong>
Para poner un texto en <strong>negrita</strong> en Markdown, usa los siguientes símbolos:
<code>**texto**</code> o <code>__texto__</code>  
Esto hará que el texto aparezca en negrita.

<strong>Texto en cursiva</strong>
Para poner un texto en <em>cursiva</em> (o itálica), usa los siguientes símbolos:
<code>*texto*</code> o <code>_texto_</code>  
Esto hará que el texto se muestre en cursiva.

<strong>Encabezados</strong>
Para crear encabezados, utiliza los siguientes códigos:

<pre>
# Título de nivel 1 (más grande)
## Título de nivel 2
### Título de nivel 3
#### Título de nivel 4
##### Título de nivel 5
###### Título de nivel 6 (más pequeño)
</pre>

<strong>Listas</strong>
- <strong>Lista ordenada:</strong> Usa el formato <code>ol</code> y <code>li</code> para crear una lista numerada. Ejemplo:

<pre>
1. Primer ítem
2. Segundo ítem
3. Tercer ítem
</pre>

- <strong>Lista desordenada:</strong> Usa el formato <code>ul</code> y <code>li</code> para crear una lista sin numerar. Ejemplo:

<pre>
- Primer ítem
- Segundo ítem
- Tercer ítem
</pre>

<strong>Párrafos</strong>
Para crear un párrafo, usa el código <code>p</code>. Un salto de línea se puede hacer con el símbolo <code>&lt;br&gt;</code>. Ejemplo:

<pre>
<p>Este es un párrafo de ejemplo.</p>
</pre>

<h3>HTML:</h3>
<strong>Empezando con HTML</strong>
Para crear un documento HTML básico, usa el siguiente formato:

<pre>
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Título de la página</title>
</head>
<body>
<ul>
<li>
Hola
</li>
<li>
Encantado de conocerte
</li>
<li>
Como llevas estos días?
</li>
</ul>
</body>
</html>
</pre>

<strong>Estructura básica de HTML</strong>
- **Header:** El <code>&lt;head&gt;</code> es la sección donde se definen metadatos como el título de la página, enlaces a hojas de estilo, etc.
- **Body:** El <code>&lt;body&gt;</code> es la sección donde se coloca el contenido visible de la página web.

<strong>Negrita en HTML</strong>
Para poner un texto en <strong>negrita</strong>, usa el elemento <code>&lt;strong&gt;</code>. Ejemplo:

<pre>
<strong>Texto en negrita</strong>
</pre>

<strong>Añadir imágenes</strong>
Para agregar una imagen en HTML, usa el siguiente código:

<pre>
<img src="./img/bola basket barça.jpg" alt="bola basket barça" width="300">
</pre>
- <code>src</code>: Especificamos la URL donde se encuentra la imagen.
- <code>alt</code>: Proporcionamos un texto alternativo que se mostrará si la imagen no se puede cargar.

<strong>Enlaces externos a otra página</strong>
Para crear enlaces externos, usamos el siguiente código:

<pre>
<a href="www.google.es">Enlace a Google</a>
</pre>
- <code>href</code>: Especifica la URL del documento al que el enlace llevará al usuario.

<strong>Favicon</strong>
Para agregar un favicon (el ícono que aparece en la pestaña del navegador), usa el siguiente código en el <code>&lt;head&gt;</code>:

<pre>
<link rel="icon" type="image/png" href="URL del favicon">
</pre>

<h2>Introducción a CSS</h2>
<strong>CSS</strong> (Cascading Style Sheets) es un lenguaje utilizado para describir la presentación de un documento HTML. Permite controlar el diseño, los colores, las fuentes, los márgenes y otros aspectos visuales de los elementos en una página web.

<h2>Sintaxis Básica de CSS</h2>
La sintaxis de CSS se compone de <strong>selectores</strong> y <strong>declaraciones</strong>: 

<pre>
selector {
  propiedad: valor;
}
</pre>

- **Selector**: Es el elemento HTML al que quieres aplicar estilos (por ejemplo, <code>p</code>, <code>div</code>, <code>.clase</code>, <code>#id</code>).
- **Propiedad**: Es el estilo que deseas aplicar (por ejemplo, <code>color</code>, <code>font-size</code>, <code>margin</code>).
- **Valor**: Es el valor que asignas a la propiedad (por ejemplo, <code>red</code>, <code>16px</code>, <code>10px</code>).

<h3>Ejemplo:</h3>

<pre>
p {
  color: red;
  font-size: 16px;
}
</pre>
Este código aplica el color rojo y un tamaño de fuente de 16 píxeles a todos los elementos <code>&lt;p&gt;</code>.

<h2>Diseño Responsive</h2>

<h3>1. Meta Etiqueta "Viewport"</h3>

Aseguranos de que el documento HTML tenga la meta etiqueta para que la página sea responsive desde el principio:

```html
<pre>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
@media (max-width: 700px){
    header{
        background-color: #27f3d1;
    }
    section{
        font-size: 12px;
    }
    main{
        flex-direction: column;
    }
    aside, section{
        width: 100%;
    }
    h1{
        font-size: 50px;
    }
    .container {
        grid-template-columns: 1fr;
    }

    header nav ul {
        display: flex;
        flex-direction: column;
        text-align: left;
    }

    header nav ul li {
        margin-bottom: 10px;
    }
}
</pre>
Lo que hace este códgio es que cuando cambiamos el tamaño de la pestaña de la página web, esta llegue a un punto en donde todo cambia de forma, color, color de fondo, etc. donde ya no se mueva más.
