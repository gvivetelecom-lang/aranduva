# ARANDUVA · Prototipo interuniversitario (V29)

**ARANDUVA** es un prototipo conceptual de una plataforma académica interuniversitaria paraguaya. Este repositorio contiene la **versión 29** de su interfaz demostrativa, lista para abrir en el navegador o publicar en **GitHub Pages**.

> **Importante:** Esta es una **demostración**, no un servicio universitario operativo. Las universidades, cursos, usuarios, publicaciones, transmisiones y chats exhibidos son ejemplos ilustrativos. No hay autenticación real, integraciones institucionales, backend, almacenamiento en servidor, streaming ni un modelo de IA conectado.

## Cómo abrir la demostración

1. Descargá o cloná el repositorio.
2. Abrí [`index.html`](index.html) en un navegador moderno.
3. Navegá por las secciones y, cuando corresponda, elegí un **perfil de demostración**.

No hace falta instalar dependencias ni ejecutar `npm install`. La versión actual incorpora estilos, lógica y recursos visuales directamente en un único archivo HTML.

Si un navegador restringe determinadas funciones al abrir archivos locales, podés servirlo con Python desde la carpeta del repositorio:

```bash
python3 -m http.server 8000
```

Y abrir `http://localhost:8000`.

## Funcionalidades ilustradas

- **Inicio:** presentación de la propuesta, fotografía temática y bloque «Conocé a Mainu».
- **Artículos:** biblioteca académica con búsqueda y herramientas de lectura/citación de muestra.
- **Cursos:** directorio de cursos y fichas didácticas.
- **Calendario:** vistas académicas y seguimiento de actividades de demostración.
- **En vivos:** catálogo de eventos y sala interactiva simulada.
- **Grabaciones:** archivo de videoconferencias de ejemplo.
- **Foro académico:** publicaciones y participación simulada.
- **Panel docente, administración y coordinación escolar:** experiencias de permisos y flujos institucionales simulados.
- **Mainu / Mainú:** personaje asistente tipo colibrí con respuestas de ejemplo, sin conexión a una API de inteligencia artificial.

> El prototipo puede utilizar almacenamiento **local del navegador** para determinadas interacciones. Estos datos no se comparten entre equipos y pueden desaparecer al limpiar los datos del navegador.

## Publicación gratuita con GitHub Pages

1. Creá un repositorio en GitHub (por ejemplo `aranduva`).
2. Subí **todo el contenido de esta carpeta** a la raíz del repositorio, en particular `index.html`.
3. En GitHub entrá a **Settings → Pages**.
4. Elegí **Deploy from a branch**, seleccioná `main` y la carpeta **`/(root)`**, y guardá.
5. GitHub mostrará la URL pública de Pages cuando el despliegue termine. Habitualmente tiene la estructura `https://TU-USUARIO.github.io/aranduva/` (sustituí el usuario y nombre de repositorio reales).

Si tu repositorio es público, el código, los contenidos y las imágenes incluidos en el HTML también serán públicos. Revisá su pertinencia antes de hacer pública la URL.

### Actualizar el sitio

Reemplazá `index.html` por la nueva versión, confirmá el cambio y subilo a `main`. Pages volverá a desplegar el contenido.

## Personas y créditos

**Concepción de ARANDUVA:** Ana Corvalán y Marcelo Encina, mediante conversaciones y decisiones compartidas.

- **Marcelo Encina:** propuestas de funcionalidades, referencias e integración conceptual de interfaces (incluidas plataformas de streaming, foros, videoconferencias y calendarios); aportes en los casos de medicina y tecnología.
- **Ana Corvalán:** mediación y gestión del desarrollo con IA, traducción de las ideas a instrucciones y ciclos de prototipado; distribución UX/UI y enfoque de experiencia humana; aportes en humanidades y artes.
- **ChatGPT (OpenAI):** herramienta de asistencia empleada para documentar, generar y revisar prototipos a partir de decisiones humanas. No figura como autor del concepto.

## Nombre e identidad

En la narrativa elegida por sus creadores, **ARANDUVA** se asocia con «quien lleva el conocimiento» y **Mainú**, nombre inspirado en el guaraní *mainumbú* (colibrí), representa a quien acerca ese conocimiento a los estudiantes. El colibrí simboliza el puente entre experiencias universitarias **presenciales** y un entorno **digital** compartido. Son interpretaciones de marca; no se presentan como un dictamen lingüístico definitivo.

## Estado y límites técnicos

- Prototipo estático, **sin API o base de datos real**.
- Inicio de sesión y perfiles **simulados**; no ofrecen seguridad de producción.
- Ningún canal de video transmite contenido en tiempo real.
- Mainu produce respuestas de demostración, no inferencia de IA externa.
- Los datos académicos y los nombres de organizaciones visibles se utilizan con fines ilustrativos; **no implican convenios, afiliaciones ni respaldos**.
- Antes de una implementación pública real se necesitan auditorías de privacidad, seguridad, accesibilidad, protección de derechos de imágenes y datos, infraestructura y permisos institucionales.

## Estructura

```text
ARANDUVA_v29_GitHub/
├── index.html             # Demo completa (HTML/CSS/JS + medios embebidos)
├── README.md              # Presentación y publicación
├── .nojekyll              # Publicación estática sin procesamiento Jekyll
├── .gitignore             # Archivos locales que no conviene publicar
└── docs/
    ├── PUBLICACION.md    # Pasos y verificaciones de despliegue
    └── ESTADO_DEMO.md    # Alcance técnico y pendientes
```

## Licencia y derechos

**No se incluye una licencia de software todavía.** La publicación de código en GitHub no implica automáticamente una autorización para reutilizarlo o distribuirlo. Los responsables del proyecto deberán definir expresamente la licencia y verificar los derechos de fotografías, recursos gráficos, marcas y materiales antes de habilitar su reutilización. La aspiración a código abierto es parte de la propuesta, no una autorización ya otorgada.

**Versión:** V29 · **Año:** 2026 · **Estado:** prototipo conceptual.
