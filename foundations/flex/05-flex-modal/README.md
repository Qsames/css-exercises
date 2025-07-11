# Un estilo 'modal' común
Este es otro patrón muy común en la web.La solución a este es _simple _... pero podría no ser inmediatamente obvia para usted.Deberá editar un poco el HTML para obtener todo donde sea necesario.

### una pista
Dependiendo de cómo se acerque a este, es posible que deba volver a visitar la propiedad 'Flex-Shrink' para evitar que se rompa un elemento flexible.Además, preste atención a la estructura del HTML, busque específicamente agregar un contenedor adicional que rodea el encabezado, el botón, el texto principal, la cancelación y continúa los divs;Y busque en mover el encabezado Div para abarcar el botón también.

## Resultado deseado

! [Resultado deseado] (./ deseado-outcome.png)

### Auto -chequeo

- El icono azul está alineado a la izquierda.
- Hay un espacio igual a cada lado del icono (los espacios entre el icono y el borde de la tarjeta, y el icono y el texto, son los mismos).
- Hay relleno alrededor del borde del modal.
- El encabezado, el texto y los botones están alineados entre sí.
- El encabezado es audaz y un tamaño de texto ligeramente más grande que el texto.
- El botón de cierre está alineado verticalmente con el encabezado y se alinea en la parte superior derecha de la tarjeta.