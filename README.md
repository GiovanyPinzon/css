(1) La diferencia práctica entre Margin y Padding:
La diferencia es que Margin es el espacio externo de un elemento, es decir, la distancia que existe entre una caja y los demás elementos. En cambio, Padding es el espacio interno que hay entre el contenido y el borde de la caja

(2) Por qué es obligatorio usar box-sizing: border-box:
Porque permite que el tamaño de una caja se mantenga dentro de las medidas que establecemos, incluyendo el contenido, el padding y el borde. Esto facilita organizar los elementos y evita que las cajas crezcan más de lo esperado

(3) Cómo se ven afectados los elementos hermanos cuando le aplicas un margen grande a uno de ellos:
Cuando aplicamos un margen grande a un elemento, este puede generar una mayor separación con los elementos que están a su alrededor. Por ejemplo, si un producto tiene un margen inferior de 100px, el siguiente producto aparecerá más abajo, dejando un espacio grande entre ambos

                Hallazgos: Centralización de Identidad Visual yEspaciado

(1) La lista completa de variables declaradas (colores y espaciados):Son valores guardados en :root para reutilizar en la página, como colores principales, secundarios, fondo, texto y medidas de espaciado pequeño, mediano y grande

(2) La ventaja de reutilizar medidas de margen y relleno en lugar de inventar valores en cada selector:Permite mantener espacios organizados, evitar repetir valores y modificar las medidas fácilmente desde un solo lugar

(3) De qué manera la centralización en :root previene colisiones visuales a medida que la hoja de estilos crece:Ayuda a mantener los mismos colores y espaciados en toda la página, evitando diferencias accidentales entre elementos
