# ARANDUVA — Demo interactiva

Prototipo navegable para presentar la visión de una red académica interuniversitaria paraguaya con asistente **Mainu**.

## Uso

Abrí `index.html` en Chrome, Safari o Firefox. No requiere instalación, API keys, base de datos ni conexión a servicios pagos. Para un servidor local opcional: `python3 -m http.server 8000` desde esta carpeta y abrir http://localhost:8000.

## Qué se puede probar

- Homepage con novedades, cursos populares y prioridades de transmisión.
- Biblioteca pública ficticia, búsqueda, filtros, artículos y referencias APA de demostración.
- Acceso institucional de prueba: estudiante, administrador, coordinador escolar, oyente.
- Cursos, calendario, foro de en vivos y grabaciones.
- Chat en vivo simulado, solicitud de participación y comentarios anclados.
- Resumen académico de ejemplo sujeto a aprobación del administrador.
- Mainu vectorial (SVG) animado, chat contextual con respuestas prefijadas.

## Avisos

Este es un **prototipo**, no una implementación real. La IA, los roles, los eventos, los cursos, los permisos y las transmisiones son simulados. No se solicitan ni guardan datos personales auténticos. Los cambios de la demo no persisten al cerrar la página.

## Publicación gratuita

Publicá la carpeta en un sitio de alojamiento estático como Cloudflare Pages o GitHub Pages. Configurá como directorio público el que contiene `index.html`. Para enlaces con hash (`#/articles`), no se requieren reglas especiales de redirección.

## Próxima fase

Migrar a componentes React/Next.js si conviene; integrar autenticación, PostgreSQL con políticas de aislamiento institucional, almacenamiento de objetos y servicios audiovisuales; conectar Mainu a IA real mediante backend seguro con controles de costo y acceso.

## Novedades de la demo 1.1 — Sector docente y administración

Ingresá desde **Acceso institucional** con el rol ficticio **Docente universitario** para abrir **Sector docente**. También podés acceder como **Administrador universitario**. El recorrido interactivo contiene:

1. Crear un curso y guardarlo como borrador.
2. Revisar el borrador y publicarlo; desde ese momento aparece en el directorio de cursos.
3. Programar una transmisión con título, fecha, hora y disertante.
4. Publicar su programación; desde entonces aparece en el foro de en vivos.
5. Iniciar una sala simulada, abrir su chat y finalizar la transmisión.
6. Inscribir estudiantes ficticios en cursos publicados, exclusivamente con el rol administrador.

Los cambios son **temporales en memoria del navegador** y desaparecen al actualizar la página. No hay envío de correos, emisión audiovisual real ni almacenamiento de datos personales. Las acciones usan datos de demostración.
