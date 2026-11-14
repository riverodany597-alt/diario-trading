# Diario de Trading

App personal para registrar operaciones de trading: antes, durante y después de cada operación. Incluye checklist de la estrategia con semáforo, calculadora de lotes por riesgo, práctica de escenarios, estadísticas, metas y revisión semanal.

- Funciona en el celular y en el PC (se instala desde Chrome o Edge).
- Funciona sin internet.
- Se sincroniza entre el celular y el PC al entrar con Google (Firebase). Sin internet, los cambios se guardan y se suben solos al reconectar.
- Igual conviene "Descargar respaldo" (Historial → Logros y respaldo) de vez en cuando.

## Archivos

- `index.html`: la app completa.
- `manifest.webmanifest`: nombre, colores e íconos para instalarla.
- `sw.js`: guarda la app en el dispositivo para usarla sin internet.
- `firebase-sync.js`: conexión con Firebase (inicio de sesión con Google y base de datos).
- `icons/`: íconos de la app.
