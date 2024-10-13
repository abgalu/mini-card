# Mini card

## Descripción

Este proyecto crea una tarjeta responsiva utilizando la metodología BEM para el nombrado, SCSS para el estilo y jQuery para la funcionalidad de alternar el color del botón. La tarjeta muestra información del producto y ajusta su diseño en función del tamaño de pantalla. Al hacer clic en el botón, su color cambia entre dos estados.

### Características

- Diseño **responsivo** (adaptable para escritorio y móvil).
- El **botón** cambia de color al hacer clic, alternando entre `#7AB800` (verde) y `#CC292B` (rojo).
- Implementación de la **metodología BEM** para nombres claros y organizados.
- Uso de la fuente **Nunito** para el diseño de tipografía.

### Stack Tecnológico

- **SCSS**: Para el diseño y las consultas de medios (media queries).
- **jQuery**: Para la lógica de alternar colores en los botones.
- **HTML**: Estructura del documento.
- **BEM**: Metodología de Bloque, Elemento, Modificador para un código más legible y mantenible.

### Estructura del Proyecto

- `index.html`: Contiene la estructura HTML de la tarjeta.
- `styles.scss`: Archivo SCSS para los estilos.
- `script.js`: Maneja la funcionalidad del botón con jQuery.

### Estructura del SCSS

El código SCSS está dividido en elementos BEM:

- `.card`: El contenedor principal de la tarjeta.
- `.card__image`: Espacio reservado para la imagen.
- `.card__title`: El título de la tarjeta.
- `.card__description`: Descripción breve del producto.
- `.card__button`: Botón con funcionalidad de alternancia de color.

### Funcionalidad con jQuery

El script jQuery asegura que el botón clicado cambie de color. Utiliza la función `.toggleClass()` para alternar entre el color verde predeterminado (`#7AB800`) y el color rojo (`#CC292B`).

### Instrucciones de Uso

1. Clona el repositorio:

   ```bash
   git clone https://github.com/abgalu/mini-card.git
   ```

2. Accede al directorio del proyecto:

   ```bash
   cd mini-card
   ```

3. Instala las dependencias:

   ```bash
   npm install
   ```

4. Inicia el servidor de desarrollo:

   ```bash
   npm run dev
   ```

   La aplicación estará disponible en `http://localhost:3000`.

5. Haz clic en el botón para alternar su color.

## Licencia

Este proyecto está bajo la licencia MIT.
