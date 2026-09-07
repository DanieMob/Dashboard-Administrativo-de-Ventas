# Dashboard-Administrativo-de-Ventas
Dashboard Administrativo de Ventas

GEDA es un dashboard administrativo diseñado para visualizar de forma clara y organizada la información de un sistema de gestión.

El dashboard presenta información relacionada con ventas, usuarios, productos e ingresos mediante tarjetas de resumen y una tabla con las ventas más recientes.

El diseño busca ofrecer una interfaz sencilla, organizada, responsiva y accesible.

## Tecnologías utilizadas

- HTML5
- CSS3
- CSS Grid
- Flexbox
- Media Queries
- Variables CSS
- Pseudo-clases CSS (`:hover` y `:focus`)

## Componentes principales

El dashboard está compuesto por:

- Barra lateral de navegación.
- Encabezado superior.
- Tarjetas de resumen.
- Tabla de últimas ventas.
- Footer informativo.

## Diseño

Para la estructura general del dashboard se utilizó **CSS Grid**, utilizando áreas nombradas mediante `grid-template-areas`.

CSS Grid permite organizar las principales secciones:

- Sidebar
- Header
- Main
- Footer

Dentro de los componentes se utilizó **Flexbox** para organizar elementos como:

- Menú de navegación.
- Encabezado.
- Tarjetas.
- Información de usuario.
- Elementos internos de los componentes.

## Responsividad

El dashboard utiliza **media queries** para adaptar su diseño a diferentes tamaños de pantalla:

### Escritorio

La barra lateral permanece visible y las tarjetas se distribuyen en cuatro columnas.

### Tablet

Las tarjetas se reorganizan en dos columnas y el tamaño de la barra lateral se reduce.

### Móvil

La barra lateral se oculta y el contenido principal ocupa todo el ancho disponible.

Las tarjetas pasan a una sola columna y la tabla puede desplazarse horizontalmente para facilitar su visualización.

## Interactividad visual

Se utilizaron transiciones y pseudo-clases CSS para proporcionar retroalimentación visual al usuario.

Se implementaron:

- Efectos `:hover` en enlaces.
- Efectos `:hover` en tarjetas.
- Efectos `:hover` en botones.
- Estados `:focus` para navegación mediante teclado.
- Transiciones suaves entre estados.

## Accesibilidad

Se utilizaron elementos HTML5 semánticos como:

- `<aside>`
- `<nav>`
- `<header>`
- `<main>`
- `<section>`
- `<article>`
- `<table>`
- `<footer>`

También se utilizaron atributos ARIA cuando fueron necesarios para mejorar la comprensión de los componentes por tecnologías de asistencia.

Los elementos interactivos pueden recibir el foco mediante el teclado y cuentan con indicadores visuales mediante `:focus`.

Los colores fueron seleccionados buscando mantener un contraste adecuado entre texto y fondo.


