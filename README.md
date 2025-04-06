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
<img src="URL de la imagen" alt="Texto alternativo">
</pre>
- <code>src</code>: Especifica la URL donde se encuentra la imagen.
- <code>alt</code>: Proporciona un texto alternativo que se mostrará si la imagen no se puede cargar.

<strong>Enlaces entre documentos</strong>
Para crear enlaces entre páginas HTML, usa el siguiente código:

<pre>
<a href="URL del documento">Texto del enlace</a>
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

<h2>Selectores CSS</h2>

<h3>1. Selector de Elemento (Tipo)</h3>
Selecciona todos los elementos de un tipo específico. Ejemplo:

<pre>
h1 {
  color: blue;
}
</pre>
Este código aplicará el color azul a todos los elementos <code>&lt;h1&gt;</code>.

<h3>2. Selector de Clase</h3>
Selecciona todos los elementos que tienen una clase específica. Se indica con un punto (<code>.</code>) antes del nombre de la clase:

<pre>
.clase-ejemplo {
  background-color: yellow;
}
</pre>
Este código aplica un fondo amarillo a todos los elementos con la clase <code>clase-ejemplo</code>.

<h3>3. Selector de ID</h3>
Selecciona un elemento con un ID específico. Se indica con un signo de almohadilla (<code>#</code>) antes del ID:

<pre>
#id-ejemplo {
  font-weight: bold;
}
</pre>
Este código pone en negrita el texto de un elemento con el ID <code>id-ejemplo</code>.

<h3>4. Selector de Atributo</h3>
Selecciona elementos que contienen un atributo específico. Ejemplo:

<pre>
input[type="text"] {
  border: 2px solid blue;
}
</pre>
Este código selecciona todos los elementos <code>&lt;input&gt;</code> con el atributo <code>type="text"</code> y les aplica un borde azul.

<h2>Propiedades Comunes de CSS</h2>

<h3>1. Colores</h3>
Para cambiar el color de los elementos, puedes usar:

- **Color de texto**:  
  <code>color: red;</code>  
  O puedes usar códigos hexadecimales o valores RGB:  
  <code>color: #ff0000;</code> o <code>color: rgb(255, 0, 0);</code>

- **Color de fondo**:  
  <code>background-color: yellow;</code>  
  O usando valores hexadecimales:  
  <code>background-color: #ffff00;</code>

<h3>2. Fuentes</h3>
Puedes definir las propiedades de la fuente de los textos:

- **Tamaño de la fuente**:  
  <code>font-size: 16px;</code>
- **Familia de fuente**:  
  <code>font-family: Arial, sans-serif;</code>
- **Estilo de fuente (negrita, cursiva, etc.)**:  
  <code>font-weight: bold;</code>  
  <code>font-style: italic;</code>

<h3>3. Márgenes y Rellenos</h3>
- **Margen (space around)**:  
  <code>margin: 20px;</code>  
  Esto aplica un margen de 20 píxeles alrededor del elemento.

- **Relleno (padding, space inside)**:  
  <code>padding: 15px;</code>  
  Esto aplica un relleno de 15 píxeles dentro del elemento.

- **Margen y Relleno individual**:  
  <code>margin-top: 10px;</code>  
  <code>padding-left: 20px;</code>

<h3>4. Ancho y Alto</h3>
Puedes establecer el tamaño de los elementos con:

- **Ancho**:  
  <code>width: 100px;</code>
- **Alto**:  
  <code>height: 50px;</code>

<h3>5. Bordes</h3>
Puedes agregar bordes alrededor de un elemento:

- **Borde básico**:  
  <code>border: 2px solid black;</code>
- **Bordes individuales**:  
  <code>border-top: 2px solid red;</code>

<h3>6. Sombra de texto y caja</h3>
- **Sombra de texto**:  
  <code>text-shadow: 2px 2px 5px gray;</code>

- **Sombra de caja**:  
  <code>box-shadow: 5px 5px 10px rgba(0, 0, 0, 0.5);</code>

<h2>Diseño y Posicionamiento</h2>

<h3>1. Posicionamiento</h3>
Existen diferentes tipos de posicionamiento en CSS:

- **Static (estático)**: Este es el valor predeterminado. Los elementos se posicionan según el flujo normal del documento.
- **Relative (relativo)**: Posiciona un elemento en relación con su posición original.
  <pre>
  position: relative;
  top: 10px;
  left: 20px;
  </pre>
- **Absolute (absoluto)**: Posiciona el elemento en relación con su contenedor más cercano que tiene posición relativa.
  <pre>
  position: absolute;
  top: 0;
  right: 0;
  </pre>
- **Fixed (fijo)**: El elemento se posiciona con respecto a la ventana del navegador, sin importar el desplazamiento.
  <pre>
  position: fixed;
  top: 0;
  right: 0;
  </pre>

<h3>2. Flexbox</h3>
Flexbox es un modelo de diseño para crear estructuras flexibles. Usa las siguientes propiedades:

- **Contenedor Flex**:  
  <code>display: flex;</code>
- **Dirección del eje principal**:  
  <code>flex-direction: row;</code> (puede ser <code>row</code>, <code>column</code>, <code>row-reverse</code>, <code>column-reverse</code>).
- **Alineación de los elementos**:  
  <code>justify-content: center;</code> (para alinear horizontalmente).  
  <code>align-items: center;</code> (para alinear verticalmente).

<h3>3. Grid</h3>
CSS Grid Layout permite crear diseños en una cuadrícula:

- **Contenedor Grid**:  
  <code>display: grid;</code>
- **Definir las columnas y filas**:  
  <code>grid-template-columns: 100px 200px;</code>  
  <code>grid-template-rows: 50px 100px;</code>

<h2>Pseudo-clases y Pseudo-elementos</h2>

<h3>1. Pseudo-clases</h3>
Las pseudo-clases permiten aplicar estilos a un elemento en ciertos estados:

- <code>:hover</code> - cuando el mouse está sobre el elemento.
- <code>:focus</code> - cuando un elemento recibe el foco (por ejemplo, un campo de formulario).
- <code>:nth-child(n)</code> - selecciona un hijo específico basado en su posición.

<h3>2. Pseudo-elementos</h3>
Los pseudo-elementos permiten aplicar estilos a una parte específica de un elemento:

- <code>::before</code> - agrega contenido antes del contenido de un elemento.
- <code>::after</code> - agrega contenido después del contenido de un elemento.

<h2>Comentarios en CSS</h2>
Puedes agregar comentarios en CSS con <code>/*</code> y <code>*/»:

<pre>
/* Este es un comentario */
</pre>
