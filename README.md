# Mapa de Acceso a la Salud Sexual y Reproductiva

Sitio estático inicial (HTML/CSS/JS), adaptable a celulares.

## Archivos
- `index.html`: estructura y contenido.
- `script.js`: directorio inicial, buscador y configuración del mapa.

## Antes de publicar
1. Revisá cada establecimiento, dirección, teléfono, horario y prestación.
2. Los registros de `script.js` son preliminares y están marcados como pendientes o históricos. No los presentes como servicios confirmados.
3. Para insertar Google My Maps:
   - Abrí tu mapa en Google My Maps.
   - Menú del mapa > Insertar en mi sitio (si está disponible) o Compartir.
   - Copiá la URL de inserción que contiene `maps/d/embed?mid=...`.
   - Pegala en `MAP_EMBED_URL` en `script.js`.
4. Si no tenés aún el mapa, dejá esa variable vacía: aparecerá un recuadro explicativo.

## Publicar gratis con GitHub Pages
1. Creá una cuenta en https://github.com/ si no tenés.
2. Creá un repositorio nuevo, por ejemplo `mapa-salud-sexual`.
3. Subí `index.html` y `script.js` a la raíz del repositorio.
4. Entrá en Settings > Pages.
5. En Build and deployment elegí `Deploy from a branch`.
6. Elegí `main` y `/ (root)`, y guardá.
7. Esperá a que GitHub publique el sitio. La URL tendrá la forma:
   `https://TU-USUARIO.github.io/mapa-salud-sexual/`
8. Probá el enlace desde un celular y generá el QR apuntando a esa URL.

## Importante
Es un prototipo académico de orientación, no un servicio oficial ni de emergencias. La página no recopila datos personales. Los datos sanitarios cambian: confirmá todo con los establecimientos y consigná fecha y fuente de actualización. No publiques información no verificada como vigente.
