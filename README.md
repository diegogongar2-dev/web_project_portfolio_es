# Mi Portafolio - Diego González

Este proyecto es mi portafolio web personal, desarrollado utilizando HTML5 semántico y CSS3. Su objetivo es presentar mi perfil como desarrollador Full Stack junior, mostrar mis habilidades, los proyectos que he construido y facilitar mis datos de contacto en un sitio limpio y completamente responsivo.

## Secciones del proyecto

El portafolio está compuesto por cuatro secciones principales:

- **Perfil**: presentación personal con foto, una breve descripción profesional y enlaces directos a mi CV, GitHub y al contacto.
- **Habilidades y herramientas**: lista visual de las tecnologías que manejo día a día.
- **Proyectos destacados**: tarjetas con los proyectos que he desarrollado, su descripción y enlaces al demo en vivo y al repositorio.
- **Contacto**: correo electrónico, formulario para enviarme un mensaje y enlaces a mis redes sociales.

## Tecnologías utilizadas

- **HTML5**: para construir la estructura semántica completa (`<main>`, `<section>`, `<footer>`, `<nav>`, `<form>`) y el contenido del portafolio.
- **CSS3 con BEM**: para aplicar estilos visuales personalizados con un esquema de colores oscuro minimalista, nombrando las clases con la metodología BEM para mantener el código organizado.
- **Fuentes locales** (`@font-face`): las familias _Open Sans_ y _Archivo Black_ se cargan localmente en formatos `.woff` y `.woff2` para mejor rendimiento.
- **Flexbox Layout**: utilizado en todas las secciones para distribuir el perfil en dos columnas, organizar las tarjetas de proyectos, alinear los íconos de habilidades y maquetar el formulario de contacto.
- **Diseño responsivo**: con _media queries_ en los puntos de ruptura de **1023px** (tabletas) y **767px** (móviles), siguiendo las especificaciones del diseño.
- **Gradientes en CSS**: gradientes lineales para los subrayados decorativos de los enlaces destacados, y gradientes radiales posicionados con `calc()` para las manchas de luz del fondo.
- **`aspect-ratio` y `object-fit`**: para mantener la proporción 16:9 de las imágenes de los proyectos en cualquier resolución sin que se deformen.
- **Posicionamiento absoluto**: utilizado dentro de un contenedor relativo para superponer la "capa invisible" (velo) y los íconos de tecnologías sobre las imágenes de las tarjetas de proyecto.
- **Interactividad CSS**: pseudo-clases (`:hover`, `:focus`) y transiciones suaves (`transition`) para mejorar la experiencia de usuario en todos los enlaces, botones y elementos interactivos.

## Instalación y uso

Para ver este proyecto de forma local en tu computadora, no necesitas instalar ningún software o servidor complejo. Solo sigue estos pasos:

1. Descarga o clona la carpeta completa del proyecto en tu equipo.
2. Asegúrate de mantener la estructura de carpetas intacta (`styles`, `fuentes`, `images`).
3. Busca el archivo principal llamado `index.html` en la raíz de la carpeta.
4. Haz doble clic sobre él para abrirlo directamente en cualquier navegador web (como Chrome, Firefox o Edge).

## Futuras mejoras

En las próximas versiones del proyecto, me enfocaré en las siguientes optimizaciones:

- **Evolución del contenido**: agregar nuevos proyectos a la sección correspondiente conforme vaya terminando los siguientes sprints del bootcamp.
- **Funcionalidad del formulario**: conectar el formulario de contacto a un servicio real (como Formspree o EmailJS) para que los mensajes lleguen directamente a mi correo.
- **Accesibilidad**: revisar los contrastes de color con herramientas como WAVE, añadir atributos `aria` donde sean necesarios y asegurar que la navegación por teclado funcione en toda la página.
- **Optimización de imágenes**: convertir las imágenes a formatos modernos como WebP y aplicar `loading="lazy"` para mejorar los tiempos de carga.

## Enlace al proyecto

GitHub Pages: https://diegogongar2-dev.github.io/web_project_portfolio_es/
