<!-- Mis apuntes -->
<h1>GitHub: Gestión de Repositorios</h1>
<p><strong>Para crear un repositorio de GitHub en tu PC local:</strong></p>
<ol>
  <li>Copia la URL del repositorio creado en GitHub.</li>
  <li>En tu PC, selecciona una carpeta donde quieras clonar el repositorio.</li>
  <li>Ejecuta el siguiente comando en la terminal:  
    <code>git clone, seguido del URL_del_repositorio</code></li>
  <li>Esto descargará automáticamente el repositorio en la carpeta seleccionada.</li>
</ol>

<p><strong>Guardar y subir los cambios:</strong></p>
<ol>
  <li>Para guardar los cambios en tu código, usa el siguiente comando:  
    <code>git commit -m "<em>Mensaje descriptivo sobre los cambios</em>"</code></li>
  <li>Luego, para subir los cambios a GitHub, usa el comando:  
    <code>git push origin main</code></li>
  <li>Este comando sube todos los cambios realizados a la rama principal de tu repositorio en GitHub.</li>
</ol>

<h2>Markdown:</h2>

<p><strong>Crear una tabla:</strong></p>
<p>Para crear una tabla en el archivo <code>README.md</code>, utiliza el siguiente formato:</p>

<pre>
| Columna 1 | Columna 2 | Columna 3 |
|-----------|-----------|-----------|
| Valor 1   | Valor 2   | Valor 3   |
</pre>

<p><strong>Texto en negrita:</strong></p>
<p>Para poner un texto en <strong>negrita</strong> en Markdown, usa los siguientes símbolos:</p>
<code>**texto**</code> o <code>__texto__</code>

<p><strong>Texto en cursiva:</strong></p>
<p>Para poner un texto en <em>cursiva</em> en Markdown, usa los siguientes símbolos:</p>
<code>*texto*</code> o <code>_texto_</code>

<p><strong>Encabezados:</strong></p>
<p>Para crear encabezados, utiliza los siguientes códigos:</p>

<pre>
# Título de nivel 1 (más grande)
## Título de nivel 2
### Título de nivel 3
#### Título de nivel 4
##### Título de nivel 5
###### Título de nivel 6 (más pequeño)
</pre>

<p><strong>Listas:</strong></p>
<ul>
  <li><strong>Lista ordenada:</strong> Usa el formato <code>ol</code> y <code>li</code> para crear una lista numerada. Ejemplo:</li>
</ul>
<pre>
1. Primer ítem
2. Segundo ítem
3. Tercer ítem
</pre>
<ul>
  <li><strong>Lista desordenada:</strong> Usa el formato <code>ul</code> y <code>li</code> para crear una lista sin numerar. Ejemplo:</li>
</ul>
<pre>
- Primer ítem
- Segundo ítem
- Tercer ítem
</pre>

<h3>HTML:</h3>

<p><strong>Empezando con HTML:</strong></p>
<p>Para crear un documento HTML básico, usa el siguiente formato:</p>

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
  <li>Hola</li>
  <li>Encantado de conocerte</li>
  <li>¿Cómo llevas estos días?</li>
</ul>
</body>
</html>
</pre>

<p><strong>Negrita en HTML:</strong></p>
<p>Para poner un texto en <strong>negrita</strong>, usa el siguiente elemento:</p>
<pre>
<strong>Texto en negrita</strong>
</pre>

<p><strong>Añadir imágenes:</strong></p>
<p>Para agregar una imagen en HTML, usa el siguiente código:</p>

<pre>
<img src="./img/bola basket barça.jpg" alt="bola basket barça" width="300">
</pre>

<p><strong>Enlaces externos:</strong></p>
<p>Para crear enlaces externos, usa el siguiente código:</p>

<pre>
<a href="https://www.google.es">Enlace a Google</a>
</pre>

<p><strong>Favicon:</strong></p>
<p>Para agregar un favicon, utiliza el siguiente código en el <code>&lt;head&gt;</code>:</p>

<pre>
<link rel="icon" type="image/png" href="URL_del_favicon.png">
</pre>

<h2>Introducción a CSS</h2>
<p><strong>CSS</strong> (Cascading Style Sheets) es un lenguaje utilizado para describir la presentación de un documento HTML. Permite controlar el diseño, los colores, las fuentes, los márgenes y otros aspectos visuales de los elementos en una página web.</p>

<h2>Sintaxis Básica de CSS</h2>
<p>La sintaxis de CSS se compone de <strong>selectores</strong> y <strong>declaraciones</strong>: </p>
<pre>
selector {
  propiedad: valor;
}
</pre>

<h3>Ejemplo:</h3>
<pre>
p {
  color: red;
  font-size: 16px;
}
</pre>

<p>Este código aplica el color rojo y un tamaño de fuente de 16 píxeles a todos los elementos <code>&lt;p&gt;</code>.</p>

<h2>Diseño Responsive</h2>
<p><strong>Meta etiqueta "Viewport":</strong></p>
<p>Para asegurar que el documento HTML sea responsivo, incluimos el siguiente código CSS:</p>

<pre>
@media (max-width: 700px) {
    header {
        background-color: #27f3d1;
    }
    section {
        font-size: 12px;
    }
    main {
        flex-direction: column;
    }
    aside, section {
        width: 100%;
    }
    h1 {
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

<p>Este código hace que cuando cambias el tamaño de la ventana de la página web, el diseño se ajusta a los cambios. Al llegar a un punto específico, los elementos se reorganizan y cambian de color, tamaño y disposición, garantizando una experiencia de usuario óptima en dispositivos móviles.</p>

