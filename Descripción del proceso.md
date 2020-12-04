Traducción del archivo psd al francés. 
Después de leer las indicaciones y pedir algunas aclaraciones a Sergi, comencé con la traducción del archivo psd. No tuve problemas con esta parte. Luego seguí con la creación de la carpeta assets-fr con las imágenes de la prueba.

Exportar imágenes desde el archivo psd. 
En photoshop, agrupé las capas que necesitaba para crear los distintos componentes y los exporté como png, a excepción del logo (en svg) y de la imagen principal (en jpg). Le puse a cada componente un nombre que fuera descriptivo, para que la maquetación fuera más eficiente y menos ambigua.

Maquetación En VS Code, creé un nuevo archivo html, un archivo css y la carpeta assets-fr con las imágenes. Primero me gusta mirar el diseño y hacerme una idea de cómo podrían ir los elementos en el html, siguiendo el box model. De esta forma, me es más fácil comenzar a maquetar. También pensé que sería buena idea mantener el diseño centrado, por lo que le dí al body un color similar al blanco, pero que tuviera un contraste suficiente para que el diseño resaltara. Desde aquí, maqueté por secciones y en orden de aparición en el diseño. El método que me pareció más cómodo de usar en este diseño fue el flexbox, que me dió bastante libertad para poder ubicar los componentes. Al igual que en los assets, a las clases también les dí un nombre que fuera muy descriptivo y así sea más fácil ubicarse en el diseño. Además, reutilicé el código lo más que pude en los componentes que eran similares.

Otros aspectos / dudas: 
En un momento, pensé en incluir un atributo para que los links se abrieran en otra pestaña, pero como no estaba tan especificado, preferí dejarlo como estaba.
Hice la maquetación haciendo la prueba general en firefox. Pero luego, al hacer las pruebas con otros navegadores (chrome y safari), el svg no se mostraba en chrome. Busqué el por qué y al parecer chrome tiene problemas al renderizar svg en <img/>. Intenté colocar el svg como una etiqueta en lugar de una img, pero tampoco me daba buenos resultados. Al final tuve que exportar el logo como png. Con esto, el logo se renderizaba en todos los navegadores.

En general, me gustó la prueba. Me lo paso bien maquetando. En total, me tomó un poco más de dos horas: una media hora traduciendo y exportando imágenes, una hora maquetando, un par de minutos testeando y resolviendo el problema del logo y otra media hora preparando todo para entregar.

¡Muchas gracias!
