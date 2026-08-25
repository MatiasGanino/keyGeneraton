# keyGeneraton

Generador de contraseña cómico: ingresás datos (nombre, apellido, mail y una posible contraseña), se evalúa la seguridad real con una librería y se muestra un mensaje gracioso con mejoras sugeridas.

## Despliegue en GitHub Pages

Este repositorio ya queda listo para desplegar automáticamente en GitHub Pages mediante GitHub Actions.

### Requisitos en GitHub

1. Ir a **Settings > Pages** del repositorio.
2. En **Build and deployment**, seleccionar **Source: GitHub Actions**.

### Publicación

- Cada push a la rama `main` ejecuta el workflow `.github/workflows/deploy-pages.yml`.
- El sitio se publica usando `index.html` como página principal.
