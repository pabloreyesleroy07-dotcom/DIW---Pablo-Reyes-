# Órbita 2 — Sistema visual de CaminandoLogros

## Enlaces de entrega

- Archivo de Figma Design (versión `Entrega Órbita 2`): [Abrir archivo en Figma](https://www.figma.com/design/aLJ3mo94Ou8ULd9bTwfr4K/PABLO-REYES---DIW?node-id=0-1&t=dPbGHYCynFpLV3sY-1)
- Prototipo interactivo (flujo principal y modo oscuro): [Abrir prototipo en Figma](https://www.figma.com/proto/aLJ3mo94Ou8ULd9bTwfr4K/PABLO-REYES---DIW?node-id=656-472&p=f&t=KNdrS52t4GOSMG82-1&scaling=min-zoom&content-scaling=fixed&page-id=635%3A302&starting-point-node-id=656%3A472&show-proto-sidebar=1)
- Registro de uso de IA: [CHANGELOG.md](./CHANGELOG.md)
- Brief del proyecto (Órbita 1): [BRIEF.md](./BRIEF.md)

## Ubicación en el archivo de Figma

- `PORTADA`: identificación del proyecto (`CaminandoLogros`).
- `GUIA DE ESTILOS`: documentación de tokens, tabla de contraste, escala tipográfica, relación con etiquetas HTML y muestra de componentes (`1. COLOR`, `2. TIPOGRAFÍA Y ETIQUETAS HTML`, `3. COMPONENTES`).
- `COMPONENTES`: librería de iconos (`0 Icons`), átomos (`Button`, `Badge`, `Input`) y moléculas (`GameCard`) con Auto layout y variantes.
- `WIREFRAMES`: agrupación de `WIREFRAMES ORBITA 1` y `WIREFRAMES REDISEÑADOS`.
- `MOCKUPS`: pantallas del happy path en escritorio (`Desktop - Home`, `Desktop - Pantalla de Juegos`, `Desktop - Crear runs`), copias en modo oscuro y enlaces en `Prototipo`.

## Lista de comprobación de la Órbita 2

- [x] Colección de variables `Primitivos` (paletas de color, `space`, `radius` y tokens tipográficos `font`).
- [x] Colección de variables `Semanticos` conectada a `Primitivos` con modos `Claro` y `Oscuro`.
- [x] Estilos guardados de texto (`Display` a `caption`), efectos (`elevation-1` a `elevation-3`) y retícula (`Escritorio`, `Movil`).
- [x] Librería única de iconos convertidos a componentes (`Lucide`).
- [x] Componentes reutilizables (`Button`, `Badge`, `Input`, `GameCard`) con Auto layout y variantes.
- [x] `GUIA DE ESTILOS` con valores, justificación por personas usuarias y comprobación de contraste WCAG.
- [x] Mockups del happy path con Auto layout, variables aplicadas y modo oscuro por selector de variable.
- [x] Prototipo navegable del flujo principal y cambio de tema desde la barra superior.
- [ ] Segundo ancho responsive en `MOCKUPS` (`Movil - Home`).

## Resumen de decisiones de diseño

### Color y contraste

- Paleta base centrada en azul (`#2F6690` y escala `blue`) para acciones principales y navegación, combinada con escala `orange` para elementos secundarios o perdibles y neutros `gray` para superficies y bordes.
- Tokens semánticos (`color/surface`, `color/surface-raised`, `color/on-surface`, `color/primary`, `color/border`) con modos `Claro` y `Oscuro` para que Abraham (sesiones largas en PC) y Alejandro (consulta rápida con poco tiempo) distingan de inmediato la acción principal manteniendo contraste WCAG AA (4,5:1 o superior).

### Tipografía

- Familia única `Inter` (`font/family/base`) por su legibilidad en tamaños pequeños (`14 px` en etiquetas de logros) y menor peso de carga frente a la restricción WSG 2.4 (inferior a 500 KB por página).
- Escala de 7 estilos (`Display` 40/48, `heading-1` 32/40, `heading-2` 24/32, `heading-3` 20/28, `body` 16/24, `label` 14/20 y `caption` 14/20) desacoplada de la etiqueta HTML semántica para mantener la jerarquía visual sin romper la accesibilidad.

### Espaciado, retícula, radios y elevación

- Escala de espaciado `space` basada en cuadrícula de 4 y 8 px (`0, 4, 8, 12, 16, 24, 32, 48, 64` px) aplicada mediante Auto layout.
- Retícula de 12 columnas en escritorio (`Grid/Escritorio`) junto con tokens `radius` y estilos `elevation-1` a `elevation-3` para separar tarjetas y barra superior sin saturar la lectura.

### Iconos, componentes y prototipo

- Iconos de la librería `Lucide` convertidos en componentes reutilizables.
- Componentes construidos con Auto layout y variables (`Button`, `Badge`, `Input`, `GameCard`) para asegurar consistencia y agilizar el flujo de Abraham y Alejandro desde el buscador hasta la creación de una run.

### Elementos pendientes o simplificados por tiempo

- La vista `Movil` en `MOCKUPS` queda pendiente respecto a los `WIREFRAMES REDISEÑADOS`; el sistema responsive base y la retícula `Grid/Movil` ya están definidos en variables y estilos para retomarse antes de la maquetación en Órbita 3.
