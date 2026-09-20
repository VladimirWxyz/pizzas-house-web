# Pizzas House · Web comercial

Sitio estático independiente de Pizzas House. Incluye el catálogo, tamaños, historia, equipo, sedes y pedidos por WhatsApp.

## Vista local

Desde esta carpeta:

```bash
python3 -m http.server 4174
```

Luego abre `http://127.0.0.1:4174`.

## GitHub Pages

1. Crea un repositorio vacío.
2. Sube el contenido de esta carpeta a la rama `main`.
3. En **Settings > Pages**, selecciona **Deploy from a branch**, `main` y `/ (root)`.

El archivo `.nojekyll` evita que GitHub Pages procese el sitio con Jekyll.
