================================================================================
                    DOCUMENTACIÓN DE ELEMENTOS HTML5 UTILIZADOS
                         Centro Deportivo SportMax
================================================================================

PROYECTO: Centro Deportivo SportMax - Sitio Web Completo HTML5
AUTOR: Jonathan Quishpe
FECHA: Octubre 2025

================================================================================
                           RESUMEN DEL PROYECTO
================================================================================

Este proyecto implementa un sitio web completo para un centro deportivo utilizando
EXCLUSIVAMENTE elementos HTML5 semánticos y funcionales. El objetivo es demostrar
el dominio completo de HTML5 sin depender de JavaScript para funcionalidades
básicas.

CARACTERÍSTICAS PRINCIPALES:
- 16 páginas HTML interconectadas
- Uso exhaustivo de elementos semánticos HTML5
- Formularios complejos con validación nativa
- Contenido multimedia integrado
- Navegación jerárquica y accesible
- Contenido real extraído de AS.com (noticias deportivas)
- Estructura semánticamente correcta y validable

================================================================================
                        ELEMENTOS HTML5 UTILIZADOS POR ARCHIVO
================================================================================

┌─────────────────────────────────────────────────────────────────────────────┐
│                              INDEX.HTML                                    │
└─────────────────────────────────────────────────────────────────────────────┘

ELEMENTOS SEMÁNTICOS:
• <header>          - Cabecera principal del sitio
• <nav>             - Navegación principal con aria-label
• <main>            - Contenido principal de la página
• <section>         - Secciones temáticas (servicios, instalaciones)
• <article>         - Artículos independientes (noticias destacadas)
• <aside>           - Información complementaria (contacto rápido)
• <footer>          - Pie de página con información de contacto
• <figure>          - Contenedores de imágenes con descripción
• <figcaption>      - Descripciones de imágenes

ELEMENTOS DE NAVEGACIÓN:
• <nav aria-label>  - Navegación accesible con etiquetas descriptivas
• <ol>/<ul>/<li>    - Listas estructuradas para navegación

ELEMENTOS MULTIMEDIA:
• <img>             - Imágenes con atributos alt completos
• <video controls>  - Videos HTML5 nativos con controles

ELEMENTOS DE FORMULARIO:
• <form>            - Formulario de contacto rápido
• <fieldset>        - Agrupación lógica de campos
• <legend>          - Títulos de grupos de campos
• <label>           - Etiquetas asociadas a inputs
• <input type="email"> - Validación nativa de email
• <select>          - Listas desplegables
• <textarea>        - Áreas de texto multilínea

ELEMENTOS TEMPORALES:
• <time datetime>   - Fechas y horarios semánticamente marcados

┌─────────────────────────────────────────────────────────────────────────────┐
│                           INSTALACIONES.HTML                               │
└─────────────────────────────────────────────────────────────────────────────┘

ELEMENTOS ESTRUCTURALES:
• <section>         - División por tipos de instalaciones
• <article>         - Cada instalación como contenido independiente
• <details>         - Información expandible de instalaciones
• <summary>         - Resúmenes clicables para expandir contenido

ELEMENTOS DE DATOS:
• <dl>/<dt>/<dd>    - Listas de definición para especificaciones técnicas
• <table>           - Tablas complejas con horarios y precios
• <thead>/<tbody>   - Estructura semántica de tablas
• <th scope>        - Encabezados de tabla con scope definido
• <caption>         - Títulos descriptivos de tablas

ELEMENTOS MULTIMEDIA:
• <audio controls>  - Audio HTML5 con controles nativos
• <video controls>  - Videos integrados

┌─────────────────────────────────────────────────────────────────────────────┐
│                     PÁGINAS DEPORTIVAS (padel.html, futbol.html, etc.)     │
└─────────────────────────────────────────────────────────────────────────────┘

ELEMENTOS ESPECÍFICOS:
• <section>         - Secciones por modalidad deportiva
• <table colspan/rowspan> - Tablas complejas con celdas combinadas
• <meter>           - Medidores de ocupación y disponibilidad
• <progress>        - Barras de progreso para estadísticas
• <blockquote cite> - Citas con fuente especificada
• <cite>            - Referencias a fuentes externas

FORMULARIOS AVANZADOS:
• <input type="range"> - Controles deslizantes para puntuaciones
• <input type="number"> - Campos numéricos con min/max
• <input type="tel">    - Campos de teléfono con validación
• <input type="date">   - Selectores de fecha nativos
• <input type="time">   - Selectores de hora nativos
• <output>          - Elementos de salida dinámica

┌─────────────────────────────────────────────────────────────────────────────┐
│                              BLOG.HTML                                     │
└─────────────────────────────────────────────────────────────────────────────┘

ELEMENTOS DE CONTENIDO:
• <article>         - Entradas de blog independientes
• <header>          - Cabeceras de artículos con metadatos
• <address>         - Información del autor
• <time pubdate>    - Fechas de publicación semánticamente marcadas

NAVEGACIÓN AVANZADA:
• <nav aria-label="Breadcrumb"> - Migas de pan accesibles
• <ol>              - Navegación jerárquica estructurada

┌─────────────────────────────────────────────────────────────────────────────┐
│                            PERSONAL.HTML                                   │
└─────────────────────────────────────────────────────────────────────────────┘

ELEMENTOS ORGANIZACIONALES:
• <section>         - División por departamentos
• <article>         - Perfil de cada empleado
• <address>         - Información de contacto del personal
• <dl>              - Listas de cualificaciones y experiencia

┌─────────────────────────────────────────────────────────────────────────────┐
│                            LOGIN.HTML                                      │
└─────────────────────────────────────────────────────────────────────────────┘

FORMULARIOS COMPLEJOS:
• <form method="post"> - Formulario con método especificado
• <fieldset>        - Agrupación lógica de campos de login
• <input required>  - Validación nativa obligatoria
• <input pattern>   - Validación con expresiones regulares
• <input minlength> - Validación de longitud mínima

┌─────────────────────────────────────────────────────────────────────────────┐
│                            CONTACTO.HTML                                   │
└─────────────────────────────────────────────────────────────────────────────┘

FORMULARIOS AVANZADOS:
• <form>            - Formulario principal de contacto
• <input type="url"> - Campos URL con validación nativa
• <input type="search"> - Campos de búsqueda especializados
• <datalist>        - Listas de sugerencias para inputs
• <option>          - Opciones para datalists y selects

ELEMENTOS DE UBICACIÓN:
• <address>         - Direcciones físicas y de contacto
• <map>/<area>      - Mapas de imagen interactivos (si aplicable)

┌─────────────────────────────────────────────────────────────────────────────┐
│                  NOTICIAS (noticias.html, noticia1-3.html)                 │
└─────────────────────────────────────────────────────────────────────────────┘

CONTENIDO REAL DE AS.COM:
• <article>         - Artículos periodísticos completos
• <header>          - Cabeceras con metadatos de noticias
• <section>         - Secciones temáticas dentro de artículos
• <blockquote cite> - Citas textuales con fuente
• <cite>            - Referencias a fuentes externas
• <mark>            - Texto destacado semánticamente
• <em>/<strong>     - Énfasis e importancia textual

ELEMENTOS INTERACTIVOS:
• <details>/<summary> - Contenido expandible para análisis técnicos
• <dl>/<dt>/<dd>    - Listas de definición para términos técnicos

TABLAS COMPLEJAS:
• <table>           - Tablas de estadísticas deportivas
• <caption>         - Títulos descriptivos de tablas
• <colgroup>/<col>  - Agrupación de columnas
• <th scope="col/row/colgroup"> - Encabezados con scope específico
• <rowspan>/<colspan> - Celdas combinadas

MULTIMEDIA TEMÁTICA:
• <audio>           - Audios relacionados con noticias
• <video>           - Videos de análisis deportivo
• <source>          - Múltiples fuentes para compatibilidad

================================================================================
                           FORMULARIOS ESPECIALIZADOS
================================================================================

TIPOS DE INPUT UTILIZADOS:
• type="text"       - Texto básico
• type="email"      - Validación de email
• type="tel"        - Números de teléfono
• type="url"        - URLs con validación
• type="number"     - Números con min/max
• type="range"      - Controles deslizantes
• type="date"       - Selectores de fecha
• type="time"       - Selectores de hora
• type="search"     - Campos de búsqueda
• type="password"   - Campos de contraseña
• type="radio"      - Botones de opción
• type="checkbox"   - Casillas de verificación
• type="submit"     - Botones de envío
• type="reset"      - Botones de reset

ATRIBUTOS DE VALIDACIÓN:
• required          - Campos obligatorios
• pattern           - Validación con regex
• min/max           - Valores mínimos y máximos
• minlength/maxlength - Longitud de texto
• step              - Incrementos para números
• placeholder       - Texto de ayuda

================================================================================
                            ELEMENTOS MULTIMEDIA
================================================================================

IMÁGENES:
• <img>             - Imágenes con alt descriptivo
• <figure>          - Contenedores semánticos
• <figcaption>      - Descripciones de imágenes

AUDIO Y VIDEO:
• <audio controls>  - Reproductores de audio nativos
• <video controls>  - Reproductores de video nativos
• <source>          - Múltiples formatos para compatibilidad

================================================================================
                           NAVEGACIÓN Y ACCESIBILIDAD
================================================================================

NAVEGACIÓN:
• <nav aria-label>  - Navegación principal etiquetada
• <nav aria-label="Breadcrumb"> - Migas de pan
• <ol>/<ul>         - Listas de navegación estructuradas
• <a aria-current="page"> - Página actual marcada

ACCESIBILIDAD:
• aria-label        - Etiquetas descriptivas
• aria-current      - Estado actual de navegación
• scope="col/row"   - Relaciones en tablas
• <label for>       - Asociación de etiquetas
• <legend>          - Títulos de grupos de campos

================================================================================
                              VALIDACIÓN HTML5
================================================================================

El proyecto está diseñado para validar completamente en:
• Validador HTML5 del W3C (https://validator.w3.org/)
• Validador WHATWG (https://whatwg.org/validator/)

ESTÁNDARES CUMPLIDOS:
• HTML5 Living Standard
• WCAG 2.1 (Accesibilidad)
• Semántica correcta
• Estructura jerárquica apropiada

================================================================================
                                INNOVACIONES
================================================================================

CONTENIDO REAL:
• Noticias extraídas de AS.com
• Análisis deportivo auténtico
• Estadísticas reales de partidos

INTERACTIVIDAD SIN JAVASCRIPT:
• <details>/<summary> para contenido expandible
• Formularios con validación nativa
• Elementos multimedia integrados
• Controles deslizantes funcionales

ESTRUCTURA SEMÁNTICA:
• Uso apropiado de todos los elementos HTML5
• Jerarquía de encabezados correcta
• Navegación accesible
• Contenido semánticamente estructurado

================================================================================
                              ARCHIVOS DEL PROYECTO
================================================================================

PÁGINAS PRINCIPALES:
• index.html        - Página de inicio
• instalaciones.html - Instalaciones del centro
• personal.html     - Equipo y personal
• blog.html         - Blog corporativo
• contacto.html     - Formulario de contacto
• login.html        - Sistema de acceso

PÁGINAS DEPORTIVAS:
• padel.html        - Información de pádel
• futbol.html       - Información de fútbol
• baloncesto.html   - Información de baloncesto
• equipo.html       - Equipos del centro

SECCIÓN DE NOTICIAS:
• noticias.html     - Índice de noticias
• noticia1.html     - Análisis derbi Madrid (AS.com)
• noticia2.html     - Hugo González NBA (AS.com)
• noticia3.html     - Marc Márquez MotoGP (AS.com)

RECURSOS:
• css/style.css     - Hoja de estilos (comentada)
• README.txt        - Esta documentación

================================================================================
                                CONCLUSIÓN
================================================================================

Este proyecto demuestra un dominio completo de HTML5 mediante:

1. USO EXHAUSTIVO de elementos semánticos
2. FORMULARIOS COMPLEJOS con validación nativa
3. CONTENIDO MULTIMEDIA integrado
4. NAVEGACIÓN ACCESIBLE y estructurada
5. INTERACTIVIDAD sin dependencia de JavaScript
6. CONTENIDO REAL de fuentes deportivas profesionales
7. VALIDACIÓN COMPLETA según estándares HTML5

El resultado es un sitio web funcional, accesible y semánticamente correcto
que aprovecha al máximo las capacidades nativas de HTML5 moderno.

================================================================================
                              FIN DEL DOCUMENTO
================================================================================