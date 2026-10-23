# Monitoreo de visitas a sede

Página web de una sola pantalla para el monitoreo de visitas a sede.

## Archivos

```
index.html   Toda la página: HTML, CSS y JavaScript en un solo archivo
```

No necesita servidor, build ni instalación: se puede abrir `index.html` con doble clic. La única dependencia externa son las fuentes de Google Fonts (Caveat y Patrick Hand), que se cargan desde internet.

## Publicar en Cloudflare Pages

1. En el panel de Cloudflare: **Workers & Pages → Create → Pages → Connect to Git**.
2. Elige este repositorio (`EduardoAEGES/monitoreo_aqp`) y la rama `main`.
3. Configuración de build:
   - Framework preset: **None**
   - Build command: *vacío*
   - Build output directory: `/`
4. **Save and Deploy**.

Queda publicada en `https://<proyecto>.pages.dev/`. Cada push a `main` vuelve a desplegar automáticamente.

## Publicar en GitHub Pages (alternativa)

Settings → Pages → Source: rama `main`, carpeta `/ (root)`. Queda en `https://eduardoaeges.github.io/monitoreo_aqp/`.

## Nota

La página enlaza a un formulario de Google (`forms.gle`). Publicada en Cloudflare Pages o GitHub Pages, cualquiera con el enlace puede verla.
