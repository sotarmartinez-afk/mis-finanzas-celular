# Mis Finanzas en el celular

Página para anotar gastos, ingresos, pagos de tarjeta, transferencias y ahorros desde el celular, y pasarlos a la app de escritorio **Mis Finanzas** con la sección **Importar**.

- Los movimientos se guardan **solo en el celular**, en el navegador. Este repositorio tiene únicamente el código de la página, no tus datos.
- **Enviar archivo** o **Descargar archivo** genera `movimientos_celular_AAAA-MM-DD.csv`, con las mismas columnas de la plantilla de Importar.
- Funciona sin internet una vez abierta, y se puede agregar a la pantalla de inicio como una app.

## Archivos

| Archivo | Para qué |
|---|---|
| `index.html` | La página completa |
| `manifest.webmanifest` | Nombre e íconos para la pantalla de inicio |
| `sw.js` | Modo sin internet |
| `icon-192.png`, `icon-512.png`, `icon-maskable-512.png`, `apple-touch-icon.png` | Íconos |

## Publicar con GitHub Pages

Settings → Pages → Source: *Deploy from a branch* → Branch: `main` y carpeta `/ (root)` → Save.
La dirección queda como `https://TU-USUARIO.github.io/mis-finanzas-celular/`.

## Actualizar

Sube el archivo nuevo con el mismo nombre (Add file → Upload files). El celular toma la versión nueva la próxima vez que abra la página con internet. Tus movimientos no se borran.
