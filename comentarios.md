### Comentarios Generales

## HTML

- section#hello > .presentation-container {

      * Linea 46 {
          * Los Headings ( h1, h2 ,h3 , etc) semánticamente representan títulos/encabezados dentro de la web, respetan un orden. No deberias poner un <h3> antes que un <h1>, ademas de que semanticamente, no representa nada el "¡Hola! Soy", es por eso que seria mas apropiado un <span> o un <p>.
      }

  }

- section#skills > .skills-container > .skills {

      * Linea 66 {
          * Con el fin de hacer mas semántico el código podrias envolver al <img> en un <picture> o <figure>, como hiciste en otras partes del código.
      }

  }

- Hay errores de validación HTML {

      * Linea 51 {
          * El nombre del archivo, al contener espacios genera un error. Es importante que los nombres de los archivos no contengan espacios ni carácteres especiales.
          * Siempre que los nombres sean compuestos, podes optar por serar con "-" o "_".
      }

      * Linea 103 {
          * No se permite añidar un elemento <p> dentro de un <cite>. Lo que si se puede, es añidar un elemento <cite> dentro del <p>.

          * En este caso igualmente, no es necesario el <cite>, porque se utiliza para hacer referencia al título de una obra, no al autor.

          * Elemento <cite> ( No esta traducido )
              https://html.spec.whatwg.org/multipage/text-level-semantics.html#the-cite-element
      }

  }

- Deje algunos comentarios a lo largo de tu código.

## CSS

- Buen uso de las transiciones muy sutiles en los elementos, para generar una mejor experiencia de usuario.

- Te deje una sugerencia sobre como trabajar el menu. Por lo general, el menu suele ocupar toda la pantalla, igualmente queda a criterio del diseñador ;)

- Cuando haces el #target al menu, estabas agregando un margen que desplazaba todo el contenido de la página, lo cual no era buena práctica y rompia un poco la página.

- Deje algunos comentarios a lo largo de tu código.

### Nota final: 8 (ocho)

Nota desagregada:
❌ Estructura correcta de documento HTML.
✅ Respeta la consigna.
✅ Respeta el diseño dado.
✅ Responsive funciona correctamente.
❌ Código bien indentado.
✅ Comentarios que permiten mejorar la legibilidad del código.
❌ Uso correcto de etiquetas semánticas.
✅ Buenos nombres de clases
✅ Reutilización de estilos.
✅ Código CSS ordenado.
❌Commits con mensajes adecuados.
