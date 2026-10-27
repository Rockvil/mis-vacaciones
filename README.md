# Mis vacaciones

Aplicación personal para planificar vacaciones, días de libre disposición y horas de convenio en un calendario anual.

## Uso

Abre `index.html` en un navegador moderno o accede a la web publicada con GitHub Pages. No requiere instalación, servidor ni dependencias externas.

- Configura tus bolsas de tiempo y sus saldos por año.
- Registra días completos, medios días u horas.
- Añade festivos manualmente y excluye fines de semana y festivos al planificar.
- Guarda y recupera copias en formato JSON.

## Datos y copias de seguridad

Los datos se guardan en el almacenamiento local del navegador (`localStorage`). No se envían a GitHub ni se sincronizan entre dispositivos o navegadores. Borrar los datos del navegador puede borrar tu planificación.

Para trasladar tu planificación desde el archivo HTML original a GitHub Pages:

1. Abre el archivo original en el navegador donde lo utilizabas.
2. Pulsa **Guardar copia** y conserva el JSON descargado.
3. Abre la web de GitHub Pages.
4. Pulsa **Abrir copia** y selecciona el JSON.

No subas tus copias JSON al repositorio. La web publicada y, si eliges un repositorio público, su código serán accesibles en Internet; la planificación que guardas en tu navegador no se incluye en los archivos de este proyecto.

## Publicación en GitHub Pages

1. Crea un repositorio llamado `mis-vacaciones` en tu cuenta de GitHub. Con GitHub Free, utiliza un repositorio público para publicar con Pages.
2. Sube `index.html`, `.nojekyll`, `.gitignore` y este `README.md` a la raíz de la rama `main`.
3. En el repositorio, abre **Settings → Pages**.
4. En **Build and deployment → Source**, selecciona **Deploy from a branch**.
5. Selecciona **main** y **/ (root)** y pulsa **Save**.
6. Espera al despliegue y abre la dirección que aparece en esa sección.

La dirección habitual será `https://TU-USUARIO.github.io/mis-vacaciones/`. Los cambios que subas a `main` se publicarán automáticamente.

Documentación oficial: [Crear un sitio de GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site).

## Archivos

- `index.html`: aplicación original, sin cambios funcionales.
- `.nojekyll`: indica que se publique como sitio estático sin procesar con Jekyll.
- `.gitignore`: excluye copias personales y archivos locales habituales.
