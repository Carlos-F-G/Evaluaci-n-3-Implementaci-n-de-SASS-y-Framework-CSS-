# Hospital Nueva Vida - Sitio Web

Este proyecto es una página web de presentación para el **Hospital Nueva Vida**, que brinda atención médica de alta calidad. El sitio tiene un diseño responsivo y utiliza **SASS** con metodología **BEM** para organizar los estilos, lo que facilita el mantenimiento y la escalabilidad del código.

## Puntos a desarrollar

- **HTML5** para la estructura del contenido.
- **SASS** Para editar los estilos, 
- **BEM** (Block-Element-Modifier) para la organizacion de modulos
- **Bootstrap** Para hacer responsivo el sitio en diferentes dimensiones de pantallas


## Estructura del proyecto

### Archivos y Carpetas Principales

- `index.html`: Página principal del sitio web.
- `equipo.html`: Página del equipo médico.
- `contacto.html`: Página de contacto.
- `sass/`: Contiene todos los archivos SASS organizados en subcarpetas siguiendo BEM.
  - `abstracts/`: Variables y mixins globales.
  - `base/`: Estilos básicos y tipografía.
  - `layout/`: Estilos de estructura general como el header, footer y grid.
  - `components/`: Componentes específicos como bienvenida, servicios y testimonios.
  - `pages/`: Estilos específicos para cada página.

### Descripción de paginas

1. **Header**: Contiene el logo y el menú de navegación principal con enlaces a las páginas principales.
2. **Bienvenida**: Introducción a la misión del hospital con una imagen de fondo.
3. **Servicios**: Sección que muestra los principales servicios médicos que ofrece el hospital.
4. **Testimonios**: Opiniones de pacientes sobre la atención recibida en el hospital.
5. **Footer**: Información de contacto, y redes sociales.

## Responsividad

El sitio se ha diseñado para ser completamente responsivo, adaptándose a diferentes dispositivos y tamaños de pantalla. Se utilizaron **media queries** para ajustar el diseño y la estructura en pantallas de menos de 768px de ancho, logrando que cada sección se vea bien en dispositivos móviles.

## Implementación de SASS y BEM

- **BEM**: La implementacion de BEM se utilizó para estructurar el código de CSS en modulos, lo que facilita su modificacion.
- **SASS**: Los archivos SASS están organizados en diferentes subcarpetas para mejorar la lectura. Se emplean **variables** para los colores y la tipografía, así como **mixins** para reutilizar estilos comunes.

## Cómo ver el proyecto

1. Clonar el repositorio o descarga los archivos.
2. Abrir el archivo Index.html
