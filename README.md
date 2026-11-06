# Bodeguita Glorish – Catálogo de pedidos

Página estática (HTML, CSS y JavaScript) con catálogo, carrito y envío de pedidos por WhatsApp.

## Archivos

- `index.html`: página y configuración del catálogo.
- `logo.png`: logo mostrado en la cabecera.
- `tienda.jpg`: foto de la tienda usada en el banner principal.

Todos los recursos locales están en la raíz para que sea fácil subir el proyecto completo a GitHub. Las fotos opcionales de productos también pueden colocarse allí; en `index.html`, asigna su nombre a `img` en el producto. Si la foto no está disponible, se mostrará un icono de respaldo.

## Configuración

En `index.html`, busca `CONFIGURA AQUÍ`:

- `WHATSAPP`: número con código de país, sin `+` ni espacios (Perú: `51`).
- `PRODUCTOS`: agrega, quita o cambia productos. Usa `img:"foto.jpg"` para una foto local o `e:"🍫"` para un emoji.

## Publicar en GitHub Pages

1. Crea un repositorio y sube `index.html`, `logo.png` y `tienda.jpg`.
2. Ve a **Settings → Pages**.
3. En **Build and deployment**, elige **Deploy from a branch**, la rama `main` y la carpeta `/ (root)`.
4. Cuando GitHub Pages publique el sitio, copia la URL que aparece en esa sección.
5. Pega esa URL en los botones **Ver productos** de tu landing page para dirigirlos a este catálogo.
