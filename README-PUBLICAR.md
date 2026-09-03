# Publicar gratis el perfil de Renata Machuca

Este paquete está preparado como sitio estático para **GitHub Pages**, que puede alojarse gratuitamente desde un repositorio público.

## 1. Crear la cuenta y el repositorio
1. Entra a GitHub y crea una cuenta gratuita si aún no tienes una.
2. Crea un repositorio público llamado **renata-machuca**.
3. Sube **todo el contenido de esta carpeta** a la raíz del repositorio.

## 2. Activar GitHub Pages
1. Abre el repositorio.
2. Ve a **Settings → Pages**.
3. En **Build and deployment**, selecciona **Deploy from a branch**.
4. Elige la rama `main` y la carpeta `/ (root)`.
5. Guarda. GitHub te mostrará una URL parecida a:
   `https://TU-USUARIO.github.io/renata-machuca/`

## 3. Antes de pedir indexación a Google
Cuando ya tengas la URL pública, reemplaza `TU_URL_PUBLICA` en:
- `robots.txt.template`
- `sitemap.xml.template`

Después renómbralos a:
- `robots.txt`
- `sitemap.xml`

En `index.html`, agrega dentro de `<head>`:
```html
<link rel="canonical" href="TU_URL_PUBLICA">
<meta property="og:url" content="TU_URL_PUBLICA">
```
También es recomendable cambiar las rutas relativas de las imágenes del JSON-LD por URLs absolutas cuando tengas la dirección pública.

## 4. Google Search Console
1. Entra a Google Search Console.
2. Añade la URL del sitio como propiedad de tipo **Prefijo de URL**.
3. Verifica la propiedad con el método que Google te ofrezca.
4. En **Inspección de URLs**, pega la URL principal y solicita indexación.
5. En **Sitemaps**, envía: `sitemap.xml`.

## 5. Coherencia de identidad
Usa de forma idéntica en LinkedIn y futuras publicaciones:
**Renata Machuca | CEO y Fundadora de MIIEXPORT | Desarrollo de Negocios | Infraestructura y Sector Ferroviario | Comercio Internacional**

No cambies frecuentemente el nombre profesional, el cargo principal ni la fotografía. La consistencia ayuda a construir una identidad digital reconocible.

## Datos ya incluidos
- Correo: miiexportsos@gmail.com
- Teléfono: +52 984 135 3945
- Ubicación profesional: Cancún, Quintana Roo, México
- LinkedIn: https://www.linkedin.com/in/renata-machuca-8b8191423

## Importante
El sitio crea una base SEO sólida, pero Google decide cuándo rastrea, indexa y posiciona las páginas. La publicación constante de contenido firmado por Renata Machuca y los enlaces desde perfiles profesionales e instituciones fortalecen el posicionamiento con el tiempo.
