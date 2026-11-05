# Lista de regalos de Obed 🎁

Página estática, compatible con GitHub Pages y teléfonos. No requiere instalar nada.

## Para ver la página
Abre `index.html` con doble clic desde una computadora.

## Publicarla GRATIS con GitHub Pages
1. Inicia sesión en https://github.com/ .
2. Crea un repositorio público llamado `lista-regalos-obed`.
3. Sube TODOS los archivos de esta carpeta a la raíz del repositorio (especialmente `index.html` y `portada-regalo.jpg`).
4. Ve a Settings → Pages → Build and deployment → Source: Deploy from a branch.
5. Selecciona `main` y carpeta `/(root)` y guarda.
6. En Pages aparecerá tu enlace, normalmente `https://TU-USUARIO.github.io/lista-regalos-obed/`. Comprueba el enlace antes de generar el QR.

## Crear el código QR
Una vez publicada y verificada, abre `crear-qr.html` en tu navegador, pega la dirección EXACTA de GitHub Pages y pulsa "Preparar QR". Abre la imagen para guardarla o imprime la tarjeta. El QR usa un servicio externo gratuito al abrir la herramienta; necesita conexión a internet.

## Editar regalos
Los regalos se encuentran en el arreglo `const products = [...]` dentro de `index.html`. Cambia nombre, precio, URL, categoría y tienda ahí. `productos.json` es una copia de referencia, NO se usa en tiempo de ejecución. Después sube el archivo actualizado a GitHub; la dirección de la página y el código QR seguirán siendo los mismos.

**Avisos:** precios aproximados (no se sincronizan); ilustraciones decorativas; links facilitados por Obed. Verifica talla, color, existencias y precio en la tienda antes de comprar.
