# nicovenegas.com

Sitio web personal de Nico Venegas.

## Cómo levantar el proyecto

Para ejecutar el proyecto localmente, ejecuta el siguiente comando desde la raíz del proyecto:

```bash
cd public && python -m SimpleHTTPServer
```

Luego abre tu navegador y ve a `http://localhost:8000`. El sitio web estará disponible y funcionando localmente.

## Deploy

El sitio web se despliega automáticamente en Firebase Hosting con cada push a la rama `main`. No es necesario realizar ninguna acción manual para el deploy - simplemente haz push de tus cambios y el sitio se actualizará automáticamente.

## Estructura del proyecto

El proyecto está organizado en la carpeta `public/` que contiene todos los archivos estáticos del sitio web.
