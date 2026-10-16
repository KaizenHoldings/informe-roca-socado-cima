# Informe de La Roca · Socado + Cima

Informe elaborado por KH sobre el avance de la roca, la entrega de Ávila Tek, las pruebas realizadas y los pendientes del proyecto Socado–Cima.

## Página principal

`index.html` es la entrada del sitio. Incluye la portada, el informe completo, los tres videos de demostración y el diagrama de arquitectura. Las fuentes, imágenes y videos están incorporados en el HTML, por lo que el archivo se puede abrir o compartir de forma independiente.

La versión del informe corresponde al 16 de octubre de 2026. El proveedor de Cowork figura como **SYNC Consultores**.

## Uso y despliegue

- Abrir `index.html` en un navegador para consultar el informe localmente.
- Para desplegarlo, servir la raíz del repositorio como un sitio estático, con `index.html` como documento inicial.
- No requiere instalación de dependencias, compilación, variables de entorno ni servidor de aplicación.
- `.nojekyll` permite servir los archivos directamente si se utiliza GitHub Pages.

El HTML ocupa aproximadamente 20 MB porque incluye los videos. El repositorio se crea privado; cargar el código no activa por sí mismo un sitio publicado.

## Contenido y mantenimiento

La portada se encuentra directamente en `index.html`. El informe completo se conserva como HTML codificado en Base64 dentro de `script#app-payload` y se muestra en un iframe. Al modificarlo, debe decodificarse y volver a codificarse en UTF-8.

Los documentos originales, versiones anteriores y archivos temporales de revisión permanecen en el espacio de trabajo local y se excluyen mediante `.gitignore`.

## Verificación realizada

Se comprobó la navegación, los filtros de módulos, las pestañas con teclado, la reproducción de los tres videos, la ampliación del diagrama y la descarga del HTML con los archivos incorporados. La portada se verificó sin desplazamiento ni texto recortado en ventanas de escritorio entre 1024 × 600 y 1440 × 900.
