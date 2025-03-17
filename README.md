https://fancy-rabanadas-decb3c.netlify.app/

README - Menú Hamburguesa

Descripción

Este proyecto implementa un menú hamburguesa responsivo utilizando HTML, CSS y FontAwesome para los íconos. El menú hamburguesa permite que la navegación se adapte a diferentes tamaños de pantalla, ofreciendo una experiencia de usuario fluida en dispositivos móviles y de escritorio.

Estructura del Código

HTML

El menú hamburguesa está compuesto por los siguientes elementos:

- Un header que contiene el logo, el menú de navegación y las opciones de usuario.

- Un input oculto de tipo checkbox (menu_hamburguesa), que actúa como activador del menú.

- Un label asociado al input que contiene el ícono de la hamburguesa.

- Una lista de navegación dentro de un nav que se oculta y se muestra según el estado del input

CSS

El menú hamburguesa está oculto en tamaños grandes y se activa en dispositivos móviles con las siguientes reglas:

- Se oculta el input y el label en pantallas grandes (display: none;).

- Se muestra el label como ícono de hamburguesa en pantallas menores a 960px.

- Se oculta la navegación estableciendo height: 0 y opacity: 0 en nav ul.

- Al marcar el input (menu_hamburguesa:checked), el menú se expande con height: 100vh y opacity: 1.