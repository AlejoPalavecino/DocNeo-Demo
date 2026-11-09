# DocNeo · Demo interactiva

Prototipo navegable de DocNeo, una propuesta de sistema para organizar información neonatal mediante carga documental asistida por IA y validación humana.

## Abrir la demo

Cuando finalice el primer despliegue de GitHub Pages, estará disponible en:

https://alejopalavecino.github.io/DocNeo-Demo/

## Qué incluye

- Dashboard de actividad neonatal.
- Perfiles demostrativos y permisos simulados.
- Carga de documentos de ejemplo.
- Extracción documental simulada con Neo.
- Bandeja de revisión con corrección y aprobación humana.
- Registros, estadísticas y consultas.
- Flujo de carga por voz simulado.

## Ejecutar localmente

Abrir `index.html` en un navegador moderno. No requiere instalación ni compilación.

## Importante

Esta es exclusivamente una demostración de interfaz y flujos. Utiliza datos ficticios y persistencia local en el navegador. La extracción documental, el dictado y las respuestas de Neo son simulados; no existe conexión con una historia clínica ni con una base de datos institucional.

**No cargar información real, identificable ni datos sensibles de pacientes.** Este prototipo no está destinado a uso asistencial ni a tomar decisiones clínicas.

## Publicación

El workflow de GitHub Actions ubicado en `.github/workflows/deploy-pages.yml` publica automáticamente el contenido del repositorio en GitHub Pages cada vez que se actualiza la rama `main`.
