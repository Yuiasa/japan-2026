# 🇯🇵 Japón 2026 — App del juego

App de retos y bingo para el viaje familiar a Japón.

## Despliegue

1. Sube esta carpeta a un repositorio en GitHub
2. En Vercel, importa el repositorio
3. Deploy automático — la app queda en tu URL de Vercel

## Cómo funciona

- Los retos se cargan en tiempo real desde tu base de datos de Notion
- Cada jugador elige su nombre al entrar
- Los retos del día cambian automáticamente según la fecha
- Las entregas y monedas se guardan en el móvil de cada jugador

## Editar contenido

Todo el contenido se gestiona desde Notion:
- **Banco de Retos e Hitos** → edita nombres, pistas, puntos, fechas
- Los cambios se reflejan automáticamente en la app

## Estructura

- `index.html` — toda la app en un solo archivo
- `vercel.json` — configuración de Vercel
