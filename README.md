# GTA Intelligence — PWA prototipo v0.1

Prototipo en español, responsive y sin dependencias externas.

## Ejecutar en local

Abre `index.html` en el navegador para probar la interfaz y las interacciones básicas. El registro del service worker y la instalación PWA requieren servir el proyecto por HTTP(S); la instalación suele requerir HTTPS salvo localhost.

## Publicar gratis con GitHub Pages

1. Crea un repositorio público en GitHub.
2. Sube todos los archivos de esta carpeta a la raíz del repositorio.
3. En Settings → Pages, elige desplegar desde la rama principal y la carpeta raíz.
4. Espera a que GitHub Pages publique el sitio por HTTPS.
5. Abre la URL publicada en el móvil y usa la opción del navegador para añadir a pantalla de inicio.

## Qué hace este prototipo

- Navegación de una sola página, búsqueda, filtros y ordenación.
- Formulario para crear aportaciones locales.
- Las aportaciones se guardan en localStorage del navegador; no se sincronizan entre dispositivos ni con otros usuarios.
- Manifest y service worker básicos para una futura PWA alojada en HTTPS.
- Contenido ficticio marcado explícitamente como demostración.

## Lo que aún no hace

- No hay cuentas reales, base de datos compartida, moderación multiusuario, mapa real ni sincronización.
- Las entradas de ejemplo no son descubrimientos verificados de GTA 6.
- El icono SVG del manifest funciona en muchos entornos modernos; conviene añadir PNG de 192×192 y 512×512 para máxima compatibilidad antes del lanzamiento público.

## Siguiente fase sugerida

Conectar Supabase para autenticación, tablas de descubrimientos, aportaciones y estados de revisión. Mantener claves secretas fuera del cliente y aplicar políticas de seguridad en la base de datos.
