## Comparaciones técnicas entre los códigos:

 Código 1: A mano
 Código 2: Cursor

- 1ra diferencia: el atributo (lang ="en") en la etiqueta <html>

 En el código 1 declara el idioma en inglés, lo cual es incorrecto para un texto escrito en español. Esto afecta negativamente la accesibilidad (los lectores de pantalla pronunciarán el texto en español usando fonética inglesa) y el procesamiento SEO. En cambio, el código 2 utiliza el valor "es", definiendo el idioma de manera adecuada. 

- 2da diferencia: valor atributo "href" en los enlaces del <nav>

 En el código 1 deja el atributo href="" vacío, provocando que el navegador recargue la página por completo al hacer clic. Sin embargo, en el código 2 utiliza href= "#" como marcador de posición o (enlace temporal), lo que permite que los hipervínculos mantengan sus estilos de interacción sin provocar recargas innecesarias.

- 3ra diferencia: Estructura semántica en el pie de página <footer>

 En el código 1, el texto del copyright se coloca directamente en la etiqueta de bloque <footer> sin ninguna etiqueta contenedora de texto. Por su parte, en el código 2 el texto está correctamente encapsulado dentro de una etiqueta de párrafo <p>, siguiendo las buenas prácticas de maquetación semántica. 


## Anlisis final:

- Los cosas que Cursor hizo mejor:
 La descripción de la imagen en el atributo alt. En el código hecho a mano el atributo está vacío (alt=""), mientras que en el código creado por Cursor el atributo describe con palabras el contenido de la imagen. Esto mejora la accesibilidad de la página y es importante para personas con problemas de visión, sobre todo cuando la imagen aporta información importante.

- Algo que haríamos distinto a Cursor:
 La etiqueta de heading usada en el aside. Cursor usó la etiqueta <h2> tanto para el título del aside como para el título del articulo principal, darle el mismo nivel de jerarquía a ambos no es lo adecuado. Nosotros justamente usamos la etiqueta <h3>, lo que refleja correctamente que el contenido del aside es secundario.
