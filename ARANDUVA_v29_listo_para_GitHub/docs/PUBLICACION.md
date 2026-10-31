# Guía de publicación en GitHub

## Opción A · Subir desde la web (sin terminal)

1. Entrá a [GitHub](https://github.com) con tu cuenta.
2. Seleccioná **New repository**. Nombre sugerido: `aranduva`.
3. Elegí la visibilidad (para usar GitHub Pages en un repositorio gratuito normalmente se utiliza un repositorio público; comprobá las condiciones vigentes del plan).
4. Creá el repositorio **sin archivos iniciales** si vas a subir esta carpeta completa.
5. Usá **Add file → Upload files** y arrastrá `index.html`, `README.md`, `.nojekyll`, `.gitignore` y el directorio `docs` (o agregalo desde la interfaz).
6. Confirmá con **Commit changes**.
7. Abrí **Settings → Pages → Build and deployment → Source: Deploy from a branch**.
8. Seleccioná `main` y `/(root)`, luego **Save**.
9. Revisá la URL pública que GitHub muestre en Pages.

**Aviso sobre archivos ocultos:** Si no ves `.nojekyll` y `.gitignore` en Finder, usá `Cmd + Shift + .` para mostrar archivos ocultos.

## Opción B · Terminal (repositorio nuevo)

```bash
cd ARANDUVA_v29_GitHub
git init
git add .
git commit -m "Publicar prototipo ARANDUVA V29"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/aranduva.git
git push -u origin main
```

Cambiá `TU-USUARIO` por tu cuenta y asegurate de crear el repositorio remoto antes de hacer `push`.

## Checklist previo a compartir la URL

- [ ] `index.html` está en la **raíz**, no dentro de una carpeta adicional.
- [ ] La homepage muestra portadas, créditos y Mainú.
- [ ] Navegan Inicio, Artículos, Cursos, Calendario, En vivos, Grabaciones y Foro.
- [ ] Se entiende claramente que los perfiles y las interacciones son simulados.
- [ ] Se revisaron créditos, marcas, imágenes y posibles derechos de uso.
- [ ] No se añadieron contraseñas, claves de API, tokens ni datos privados.
- [ ] La versión es V29 y se comprobó en el navegador tras el despliegue.

## Cambios posteriores

Editá o reemplazá `index.html`, creá un commit y publicá en la rama `main`.
