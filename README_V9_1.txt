MECÁNICA VISUAL V9.1 — OEM EN ESPAÑOL

CONTENIDO
- index.html: aplicación y apartado OEM ampliado en castellano.
- sw.js: caché PWA con versión nueva para forzar actualización.
- manifest.webmanifest e icon.svg: instalación PWA.

MEJORAS OEM
- Interfaz e instrucciones en español.
- Buscador de marcas ampliado.
- Ficha de datos del vehículo para preparar consultas (no valida automáticamente referencias).
- Diccionario inglés-español de términos frecuentes de despieces.
- Pasos para usar la traducción de Safari cuando el catálogo externo lo permita.

IMPORTANTE
Los catálogos se abren en sitios externos. Su idioma, cobertura, exactitud, acceso por VIN y carácter oficial dependen de cada proveedor. No se han añadido referencias ficticias ni se garantiza que cada enlace tenga datos OEM oficiales para todos los modelos. La referencia debe confirmarse en el catálogo correspondiente al VIN/motor/fecha/equipamiento.

ACTUALIZAR GITHUB PAGES
1. Guarda una copia de la versión publicada actual.
2. En el repositorio, abre la carpeta que publica GitHub Pages.
3. Sustituye index.html, sw.js, manifest.webmanifest e icon.svg por los de este ZIP, manteniendo los nombres exactos.
4. Confirma el cambio (Commit changes).
5. Espera a que GitHub Pages termine y abre la web en Safari. Si aparece una versión anterior, cierra la pestaña, vuelve a abrir la URL y recarga.
6. Prueba el apartado “Despieces OEM”, el filtro de marcas, el diccionario y la ficha de consulta.

PRUEBAS REALIZADAS EN ESTA ENTREGA
- Sintaxis JavaScript comprobada con Node.js.
- Estructura ZIP comprobada tras crear el paquete.
- No se ha probado en un iPad físico ni se ha publicado en GitHub desde aquí.
