# Centro Deportivo SportMax - Sitio Web HTML5

## Descripción del Proyecto

Este proyecto consiste en un sitio web completo para un centro deportivo que utiliza todas las características de HTML5 (excepto las que requieren JavaScript). El sitio implementa una estructura jerárquica de navegación y contiene contenido rico con formularios avanzados, elementos multimedia y etiquetas semánticas.

## Estructura Jerárquica del Sitio

```
├── Inicio (index.html)
├── Login (login.html)
│   ├── Instalaciones (instalaciones.html)
│   │   ├── Pistas de pádel (padel.html)
│   │   ├── Pistas de fútbol (futbol.html)
│   │   └── Canchas de baloncesto (baloncesto.html)
│   ├── Personal (personal.html)
│   │   └── Equipo (equipo.html)
│   ├── Blog (blog.html)
│   ├── Noticias (noticias.html)
│   │   ├── Noticia 1 (noticia1.html)
│   │   ├── Noticia 2 (noticia2.html)
│   │   └── Noticia 3 (noticia3.html)
│   └── Contacto (contacto.html)
```

## Navegación Implementada

- **Navegación horizontal**: Páginas del mismo nivel pueden navegar entre sí
- **Navegación vertical**: Las páginas hijas pueden acceder a páginas padre y viceversa
- **Breadcrumb navigation**: Implementado en páginas hijas para mostrar la jerarquía
- **Navegación contextual**: Menús específicos para secciones relacionadas

## Elementos HTML5 Utilizados

### Etiquetas Semánticas
- `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`
- `<figure>`, `<figcaption>`, `<details>`, `<summary>`
- `<address>`, `<time>`, `<mark>`, `<small>`

### Formularios HTML5 Avanzados
- Tipos de input: `email`, `tel`, `date`, `time`, `datetime-local`, `number`, `range`, `color`, `url`, `file`
- Elementos: `<datalist>`, `<output>`, `<fieldset>`, `<legend>`
- Atributos: `required`, `pattern`, `min`, `max`, `step`, `placeholder`, `autocomplete`
- Validación nativa y controles avanzados

### Multimedia
- `<audio>` y `<video>` con múltiples fuentes
- Controles nativos del navegador
- Contenido alternativo para accesibilidad

### Elementos de Medición
- `<meter>` para mostrar mediciones (ocupación, satisfacción)
- `<progress>` para barras de progreso

### Listas y Tablas Complejas
- Listas anidadas (ul, ol) con diferentes tipos de numeración
- Tablas con `<thead>`, `<tbody>`, `<caption>`
- Celdas que abarcan múltiples filas y columnas (`rowspan`, `colspan`)
- Agrupación de columnas con `<colgroup>`

### Enlaces y Referencias
- `<blockquote>` con atributo `cite`
- Enlaces `mailto:` y `tel:`
- Enlaces con `target="_blank"` para recursos externos

## Características Implementadas

### 1. Imágenes con Miniaturas
- Imágenes thumbnail que se expanden al hacer clic
- Uso de `onclick` para abrir imágenes en resolución completa
- `<figcaption>` para descripciones de imágenes

### 2. Listas Anidadas Complejas
- Hasta 3 niveles de anidación
- Diferentes tipos de numeración (1, a, i, A, I)
- Combinación de listas ordenadas y no ordenadas

### 3. Tablas Avanzadas
- Celdas de cabecera con `scope`
- Expansión de celdas a múltiples filas y columnas
- Agrupación lógica de datos
- Tablas responsivas y accesibles

### 4. Formularios Comprehensivos
- Más de 15 tipos diferentes de input
- Validación nativa HTML5
- Agrupación con fieldsets
- Controles deslizantes, selectores de color
- Subida de archivos con restricciones de tipo

### 5. Contenido Multimedia
- Audio con fuentes externas
- Video embebido con controles nativos
- Fallbacks para navegadores no compatibles

## Archivos del Proyecto

### Páginas HTML
- `index.html` - Página de inicio
- `login.html` - Portal de acceso
- `instalaciones.html` - Página padre de instalaciones
- `padel.html`, `futbol.html`, `baloncesto.html` - Instalaciones específicas
- `personal.html` - Información del personal
- `equipo.html` - Perfiles del equipo
- `blog.html` - Blog deportivo
- `noticias.html` - Portal de noticias
- `noticia1.html`, `noticia2.html`, `noticia3.html` - Artículos de noticias
- `contacto.html` - Formularios de contacto

### Recursos
- `css/style.css` - Estilos del sitio web
- `images/` - Carpeta para imágenes
- `images/thumbs/` - Miniaturas de imágenes

## Tecnologías Utilizadas

- **HTML5**: Todas las etiquetas semánticas y elementos de formulario
- **CSS3**: Flexbox, Grid, animaciones, diseño responsive
- **Fuentes externas**: Google Fonts, recursos multimedia externos
- **Accesibilidad**: ARIA labels, navegación semántica, alt texts

## Características de Accesibilidad

- Navegación con ARIA labels
- Textos alternativos en imágenes
- Estructura semántica correcta
- Contraste de colores adecuado
- Navegación por teclado
- Breadcrumbs para orientación
- Formularios etiquetados correctamente

## Responsive Design

- Diseño adaptable para diferentes tamaños de pantalla
- Grid layout que se convierte a columna única en móviles
- Navegación adaptativa
- Tablas responsivas
- Imágenes que se ajustan al contenedor

## Validación HTML5

Todas las páginas están construidas con HTML5 válido y siguen las mejores prácticas de:
- Estructura semántica
- Accesibilidad web
- SEO básico con meta tags
- Navegación jerárquica
- Contenido estructurado

Este proyecto demuestra el uso comprehensivo de HTML5 moderno para crear un sitio web profesional y funcional sin depender de JavaScript.