# HTML y CSS

### Estructura mínima de una web

```html
<DOCTYPE!>
 <html>
 <head>
   <title></title>
 </head>
 <body>
 </body>
 </html>
```
### Explica las 3 formas de usar CSS en HTML 
```html

Una forma es con un CSS externo, en la cual le damos una relación al CSS en el bloque <head></head>

Otra forma es con un CSS interno,el cual podemos incluir estilos en la cabecera HTML del documento

Y por último el CSS embebido, con el podemos hacer lo mediente las etiquetas a través del <style></style>
```

### Crea una lista sin ordenar con 5 ingredientes de una receta de cocina
```html
<html>
 <head>
 <title></title>
 </head>
 <body>
 <ul>
 <li>Alcachofas</li>
 <li>Cebollas</li>
 <li>Coliflor</li>
 <li>Esparragos</li>
 <li>Espinacas</li>
 </ul>
 </body>
</html>
```

### Como se puede incluir JavaScript en HTML
```html
Lo podemos incluir mediante la etiqueta "<script>"
```

### ¿Que diferencia hay entre una clase y una id?
```html
Principalmente su simbolo id: "#" y class: ".", id es un elemento único mientras que class puede usarse las veces que quieras.
```

### Código para hacer un enlace a otra página y que esta se abra en una nueva ventana
```html
El código sería con <a href=....> 
 
 Ej:
 
 <html>
 <head>
 <title></title>
 </head>
 <body>
 <button><a href="https://es.wikipedia.org/wiki/Wikipedia:Portada">Página de wikipedia</a></button>
 </body>
 </html>
```

### ¿Qué son las pseudoclases?, pon ejemplos.
```html
Una pseudoclase es simplemente una palabra clave que especifica un estado especial del elemento que hemos seleccionado 
```

### Explica el modelo de caja de CSS (margin, border y padding)
```html
Margin es una etiqueta que nos permite crear un espacio entre un texto y una imágen (por ejemplo)
Border es una etiqueta que nos permite crear un borde sobre el elemento especificado, pudiendo personalizarlo dandole colores, ancho sobre el borde...
Padding es una etiqueta que nos permite crear un espacio alrededor del elemento, quiero decir, es como un relleno al rededor de la imagen,texto... 
```

### Explica que son los selectores de CSS y pon ejemplos
```html
Los selectores de CSS son la unión entre la hoja de estilos y los documentos para aplicarlos en la hoja de estilos
```

### Di a quien afectan:
```html
p a { color: red;} : Afecta a todo lo que tenga "p" y todo lo que tenga "a"
p > a { color: red; } : Afecta a la "a" que este dentro de "p" y tendrá colo rojo
h1 + h2 { color: red } : Afecta a ambas cabeceras y tendrá color rojo
a[class] { color: blue; } : Afectará a todo lo que tenga esa clase y tendrá color azul
a[class="externo"] { color: blue; } : Afectará a la clase "externo" y lo pondrá de color azul
a[href="http://www.ejemplo.com"] { color: blue; } : Afectará la dirección web y le pondrá color azul.
```
