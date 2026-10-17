# Página de negocio — versión corregida

Incluye catálogo, enlaces de TikTok y Facebook, búsqueda, categorías, detalle de producto y consultas por WhatsApp. Está hecha con HTML, CSS y JavaScript y puede publicarse en GitHub Pages.

## Archivos
- `index.html`: página pública; no incluye botón ni panel de administración.
- `style.css`: diseño adaptable a móvil y computadora.
- `script.js`: comportamiento de la página pública.
- `data.js`: nombre, eslogan, redes, WhatsApp, foto y productos que ven todos los visitantes.
- `admin.html`: herramienta de administración separada. **No la subas al repositorio público**; guárdala localmente.

## Usar la herramienta de administración
1. Abre `admin.html` en tu computadora (también puedes usar Apache/XAMPP).
2. Completa el nombre, contacto y redes; agrega/edita productos y selecciona imágenes.
3. Pulsa **Descargar data.js actualizado**. Las imágenes se comprimen en el navegador y se incluyen dentro del archivo generado.
4. Reemplaza el `data.js` dentro de la carpeta del sitio público con el descargado.
5. Sube `index.html`, `style.css`, `script.js` y `data.js` a GitHub Pages. No subas `admin.html`.

La herramienta no sube cambios automáticamente a GitHub, y GitHub Pages no proporciona una base de datos ni un servidor para guardar cambios. El proceso es exportar y volver a subir el archivo.

## Probar con Apache
Extrae la carpeta `linkme-negocio` dentro de `C:\xampp\htdocs\` y visita `http://localhost/linkme-negocio/`. Para abrir la herramienta, visita `http://localhost/linkme-negocio/admin.html` en tu propia computadora; no publiques ese archivo en GitHub.

## Personalización pendiente
Los datos iniciales son marcadores de posición porque todavía no tenemos confirmado el nombre, enlaces sociales, WhatsApp ni productos reales. La foto de perfil también está pendiente: el enlace de Facebook no permitió obtener la imagen, así que puedes seleccionarla desde `admin.html` cuando la tengas guardada en tu computadora.
