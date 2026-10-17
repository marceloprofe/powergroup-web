# Power Group

Web del equipo Power Group, Liceo 6 de Rivera, Uruguay.

Sitio estático para GitHub Pages. El contenido está en `index.html`, el estilo en `style.css` y las interacciones en `app.js`.

Incluye galería de imágenes y videos con filtros y navegación, proyectos, espacio para el Ceilab y explorador de habilidades. Los portafolios individuales y las fichas de proyectos pendientes deben completarse con información del equipo; no se inventaron nombres o resultados.

Los recursos compartidos por el equipo se guardan en `assets/`. `equipo-animado.mp4` y su miniatura corresponden a una animación generada con IA.

Calculadora: https://powergroup-robotica.github.io/powergroup-scorer/

## Flujo de trabajo

- `main`: versión pública. GitHub Pages publica únicamente esta rama, desde la raíz del repositorio.
- `codex/desarrollo`: cambios en preparación. Se pueden guardar y subir a GitHub sin actualizar el sitio público.
- Para trabajos independientes se pueden crear ramas `codex/nombre-del-cambio` desde `main`.

Los cambios se revisan en una vista previa local antes de publicar. Subir una rama de trabajo no crea por sí solo una URL de vista previa en GitHub Pages.

Para revisar localmente, ejecutar desde la carpeta del proyecto:

```sh
python -m http.server 8768
```

Abrir http://127.0.0.1:8768/ .

Cuando el usuario solicite publicar, abrir una pull request hacia `main`, revisar y combinar los cambios. Solo la actualización de `main` despliega la web pública. No combinar ni enviar cambios a `main` mientras se estén preparando o revisando.
