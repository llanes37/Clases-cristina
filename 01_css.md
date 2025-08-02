
# Ejercicio Completo de CSS para Profesores

Este archivo está diseñado para explicar a los profesores cómo usar CSS para estilizar páginas web, describiendo tanto el código HTML como el CSS utilizado.

## Estructura del Documento

### 1. Enlace a Archivo CSS Externo

En el `<head>` del documento, hemos enlazado un archivo CSS externo con la siguiente línea:

```html
<link rel="stylesheet" href="styles.css">
```

Esto permite escribir las reglas de estilo en un archivo separado, manteniendo el código más organizado.

### 2. Estilos Globales del Cuerpo del Documento

Se definen estilos globales para todo el documento con las siguientes propiedades CSS:

```css
body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    color: #333;
    margin: 0;
    padding: 0;
}
```

- **`font-family`**: Define el tipo de fuente que usará todo el texto en la página.
- **`background-color`**: Cambia el color de fondo de la página a un gris claro.
- **`color`**: Cambia el color del texto a un gris oscuro.

### 3. Encabezado y Navegación

El encabezado principal incluye un menú de navegación con enlaces a diferentes secciones de la página. Aquí usamos las siguientes reglas CSS para estilizar el encabezado:

```css
header {
    background-color: #333;
    color: white;
    padding: 20px;
    text-align: center;
}
```

- **`background-color`**: Aplica un fondo oscuro al encabezado.
- **`text-align: center`**: Centra el contenido del encabezado.

Para el menú de navegación:

```css
nav ul {
    list-style-type: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}
```

- **`list-style-type: none`**: Elimina los puntos de la lista.
- **`display: inline`**: Muestra los elementos de la lista en una sola línea.

### 4. Sección de Colores

En esta sección, se muestran ejemplos de cómo cambiar los colores de fondo de los elementos utilizando la propiedad `background-color`. Cada caja tiene un color de fondo diferente: rojo, azul y verde.

```css
.caja-roja {
    background-color: red;
    padding: 10px;
    color: white;
    margin-bottom: 10px;
}

.caja-azul {
    background-color: blue;
    padding: 10px;
    color: white;
    margin-bottom: 10px;
}

.caja-verde {
    background-color: green;
    padding: 10px;
    color: white;
    margin-bottom: 10px;
}
```

- **`background-color`**: Cambia el color de fondo de cada caja.
- **`padding`**: Añade espacio dentro de la caja.
- **`margin-bottom`**: Añade espacio entre las cajas.

### 5. Tipografía

En la sección de tipografía, se muestran diferentes tipos de fuentes y tamaños usando las propiedades `font-family` y `font-size`. También se incluye un ejemplo de texto resaltado:

```css
.tipografia-courier {
    font-family: 'Courier New', Courier, monospace;
    font-size: 20px;
}

.tipografia-verdana {
    font-family: Verdana, sans-serif;
    font-size: 18px;
}

.resaltado {
    background-color: yellow;
    font-weight: bold;
}
```

- **`font-family`**: Define la fuente utilizada en el texto.
- **`font-size`**: Cambia el tamaño del texto.
- **`font-weight`**: Aplica negrita al texto resaltado.

### 6. Modelo de Caja

La sección final del documento explica el **modelo de caja** en CSS, el cual describe cómo se organizan los elementos en la página utilizando márgenes, bordes y relleno:

```css
.modelo-caja {
    border: 2px solid black;
    padding: 20px;
    margin: 10px;
    background-color: #f9f9f9;
}
```

- **`margin`**: Define el espacio externo alrededor de la caja.
- **`padding`**: Define el espacio interno entre el borde y el contenido de la caja.
- **`border`**: Define el grosor y color del borde alrededor de la caja.

Este modelo de caja es fundamental para entender cómo se distribuyen los elementos en una página web.
