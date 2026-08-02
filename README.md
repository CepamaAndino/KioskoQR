# Semillas — Registro de deudas

App para registrar pagos pendientes de la cafetería Montessori Semillas: mantenedor de productos, deudas por persona, registro de pagos (abonos) y exportación compatible con la planilla de Google Sheets.

## Ver la app online (GitHub Pages)

1. Ve a **Settings → Pages** en este repositorio.
2. En "Source" elige la rama `main` y carpeta `/ (root)` → Save.
3. En un par de minutos tu app queda publicada en algo como:
   `https://cepamaandino.github.io/KioskoQR/`

## Importante sobre los datos

Esta versión (`index.html`) guarda los datos en el **navegador de cada persona** (no están sincronizados entre distintos computadores/celulares). Si varias personas van a registrar deudas al mismo tiempo desde distintos dispositivos y necesitan ver lo mismo en tiempo real, se necesita conectar una base de datos (o el puente a Google Sheets que se explica dentro de la pestaña "Sincronizar").

## Estructura

- `index.html` — la app completa (React vía CDN, no requiere instalación ni build).
- `assets/logo-semillas.png` — logo de la cafetería.
- `assets/semi-mascota.png` — mascota "Semi".
