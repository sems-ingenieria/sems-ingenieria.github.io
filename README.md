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
