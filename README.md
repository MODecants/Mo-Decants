# M&O Decants

Sitio web estático listo para publicar gratuitamente con GitHub Pages.

## Estructura

- `index.html` — página principal.
- `assets/styles.css` — estilos.
- `assets/app.js` — interacción, navegación, catálogo y pedidos por WhatsApp.
- `404.html` — redirección de respaldo para GitHub Pages.

## Publicar gratis con GitHub Pages

1. Crea una cuenta en GitHub.
2. Crea un repositorio nuevo, por ejemplo `mo-decants`.
3. Sube todos los archivos de este proyecto manteniendo la estructura.
4. En GitHub abre **Settings → Pages**.
5. En **Build and deployment**, selecciona **Deploy from a branch**.
6. Elige la rama `main` y la carpeta `/ (root)`.
7. Guarda los cambios y espera a que GitHub publique la web.

## Antes de publicar

Revisa el número de WhatsApp definido en `assets/app.js`:

```js
const WA_NUMBER = '573178143757';
```

Los precios, nombres y productos están definidos en el código existente. Puedes modificarlos directamente desde el proyecto.

No necesitas backend ni hosting de pago para esta versión.
