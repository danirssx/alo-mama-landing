# Aló Mamá · landing

Landing de portafolio de **Aló Mamá**, 1er lugar en el track de Emergencias y 2do lugar general (de 22 equipos) en Platanus Hack 26 Caracas.

Sitio estático: un solo `index.html` con CSS y JS en línea, más `media/` (fotos, capturas, videos) y `fonts/` (Lexend). No hay build ni dependencias.

## Ver en local

```sh
python3 -m http.server 8080
# abrir http://localhost:8080
```

## Deploy

Funciona en cualquier hosting estático. En Vercel: importar el repo, framework **Other**, sin build command, output directory `.` (raíz). `vercel.json` solo añade cabeceras de caché para `media/` y `fonts/`.

Si cambias el dominio, actualiza la URL absoluta de `og:image` en `index.html`.
