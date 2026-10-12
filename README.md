# Su Hogar era el Fuego — sitio web

Sitio estático (HTML + CSS + JS, sin dependencias) listo para **GitHub Pages**.

## Estructura
```
index.html                      Inicio
cenas-clandestinas/index.html   Cenas Clandestinas
talleres-de-cocina/index.html   Talleres de Cocina
eventos-empresariales/index.html Eventos Empresariales
contacto/index.html             Contacto + FAQs
css/ js/ assets/                Estilos, scripts, fuentes e imágenes (WebP)
sitemap.xml robots.txt          SEO
```

## Publicar en GitHub Pages
1. Crea un repositorio y sube todo el contenido de esta carpeta a la raíz (`main`).
2. *Settings → Pages → Build and deployment → Deploy from a branch → `main` / `(root)`*.
3. Reemplaza el dominio de ejemplo (canonical, Open Graph, sitemap y datos estructurados):
   ```bash
   ./reemplazar-dominio.sh https://TU-USUARIO.github.io/NOMBRE-REPO   # o tu dominio propio
   ```
4. Dominio propio: crea un archivo `CNAME` con el dominio y configura el DNS.
5. Registra el sitio en **Google Search Console** y envía `https://TU-DOMINIO/sitemap.xml`.
6. Crea/verifica la ficha de **Google Business Profile** (Bogotá) y enlázala.

## Pendientes de contenido
- Textos de reseñas de Google Maps (hoy hay botón al perfil; ver comentario en `index.html`, sección Reseñas).
- Logos de los clientes (hoy aparecen como texto en el banner rotativo).
- Código de Google Analytics / Tag Manager (comentario en el `<head>`).
