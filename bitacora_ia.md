# Bitácora de inteligencia artificial

## Consulta 1
- **Fecha:** 3 de Noviembre de 2026
- **Herramienta utilizada:** Gemini
- **Objetivo:** Generar una estructura semántica en HTML5 adaptada a mi área de Nutrición.
- **Prompt completo:** "Escribe el HTML para mi portfolio web siguiendo mi planificación personal (Hey, I'm Val, Nutrición) con las secciones inicio, sobre mí, proyectos, habilidades y contacto".
- **Parte utilizada:** Toda la maqueta HTML5 con etiquetas semánticas (`header`, `nav`, `main`, `article`, `footer`).
- **Cambios realizados por mí:** Ajusté las descripciones concretas de los proyectos "El Eternauta" y "Revista Mural".
- **¿Qué comprendí?** Comprendí cómo conectar los `href="#seccion"` con los `id="seccion"` para la navegación interna.
- **¿Qué descarté y por qué?** Ninguno, se adaptó a la consigna.

## Consulta 2
- **Fecha:** 3 de Noviembre de 2026
- **Herramienta utilizada:** Gemini
- **Objetivo:** Crear una hoja de estilos CSS que aplique la paleta de colores lila/rosa/blanco y las tipografías elegidas.
- **Prompt completo:** "Crea un CSS básico con variables de color, tipografía Lora y Abril Fatface, y diseño en tarjetas para los proyectos".
- **Parte utilizada:** El CSS completo con variables `:root`.
- **Cambios realizados por mí:** Cambié el color del borde de las tarjetas para dar más contraste visual.
- **¿Qué comprendí?** Entendí el uso del modelo de caja (`padding`, `margin`, `border`) y el uso de variables CSS para reutilizar colores.
- **¿Qué descarté y por qué?** Descarté sombras muy cargadas para mantener la estética minimalista.

## Consulta 3
- **Fecha:** 16 de Noviembre de 2026
- **Herramienta utilizada:** Gemini
- **Objetivo:** Hacer el diseño más llamativo visualmente y diferenciar claramente cada sección incorporando imágenes.
- **Prompt completo:** "Podes hacer que sea mas llamativo y que tenga bien divididas las secciones con imágenes"
- **Parte utilizada:** El rediseño del HTML con contenedores para imágenes en el inicio, perfil, tarjetas de proyectos y habilidades, junto con las reglas CSS de fondos alternados por sección, degradados y diseño adaptable a celulares (`@media`).
- **Cambios realizados por mí:** Reemplacé (o preparé para reemplazar) las imágenes de muestra por fotos propias en una carpeta local `img/` y verifiqué la corrección del correo electrónico en la sección de contacto.
- **¿Qué comprendí?** Comprendí cómo alternar colores de fondo de ancho completo para separar secciones, cómo ajustar imágenes con `object-fit: cover` para que no se deformen y cómo organizar elementos en columnas con CSS Grid.
- **¿Qué descarté y por qué?** Descarté el formato de lista simple en la sección de habilidades para transformarlo en bloques visuales con iconos que aportan mayor jerarquía estética.
