# SEMS · Landing page

Sitio estático de SEMS (Structural Engineering Management Systems), listo para GitHub Pages.

- `index.html`: la página completa (HTML, CSS y JS en un solo archivo).
- `assets/`: logotipo e imagen de fondo.

## Publicar en GitHub Pages
Settings → Pages → Source: "Deploy from a branch" → rama `main`, carpeta `/ (root)` → Save.

## Datos de contacto
Correo, WhatsApp y ubicación aparecen en la sección de contacto y en el pie de página de `index.html`, y en la constante `CONTACT` al final del archivo (WhatsApp con código de país, sin signos ni espacios).

## Formulario
El formulario envía cada solicitud a sems.structures@gmail.com con [Web3Forms](https://web3forms.com/) (plan gratis, 250 mensajes al mes). La clave está en la constante `WEB3FORMS` al final de `index.html`; es pública y solo permite enviar a ese correo. Si el envío falla, la página ofrece mandarla por correo o WhatsApp.

## Idiomas (español / inglés)
El botón **ES / EN** del encabezado cambia la página a inglés. El texto en español está en el HTML y la versión en inglés está en el objeto `EN` al final de `index.html` (cada elemento traducible lleva `data-i18n`, `data-i18n-html` o `data-i18n-attr` con su clave). Si cambias un texto en español, cambia también su traducción en `EN`.

- La página recuerda el idioma elegido en ese navegador. Si la persona nunca lo ha elegido, se muestra en inglés cuando su navegador no está en español.
- Enlace directo a la versión en inglés: `https://sems-ingenieria.github.io/?lang=en`.
- Las solicitudes enviadas desde la versión en inglés llegan al correo con `[EN]` en el asunto.
