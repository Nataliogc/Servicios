# Reglas del Proyecto (Cumbria Hotel & Spa)

## Control de Versiones Obligatorio y Automático (Versión Única Global)

Existe **una única versión global para todo el sistema**. 

### Regla de Automatización:
Cada vez que se realice cualquier modificación, mejora, corrección o ampliación en cualquier archivo del sistema (`index.html`, `admin.html`, `db.js`, `firebase-config.js`, archivos de excursiones, estilos, etc.), el asistente **DEBE ACTUALIZAR AUTOMÁTICAMENTE Y DE MANERA INMEDIATA** (sin necesidad de que el usuario lo recuerde):

1. **Número de Versión Global**: Incrementar la versión en [`REGISTRO_VERSIONES.md`](file:///c:/Users/comun/Documents/GitHub/Servicios/REGISTRO_VERSIONES.md) siguiendo SemVer:
   - **Parche (`+0.0.1`)**: Correcciones de bugs, mejoras visuales, ajustes de textos o pequeñas optimizaciones.
   - **Menor (`+0.1.0`)**: Nuevas funcionalidades, nuevas vistas o secciones añadidas.
   - **Mayor (`+1.0.0`)**: Cambios de arquitectura mayores o rediseños completos.
2. **Fecha de Actualización**: Registrar la fecha actual en formato `DD/MM/AAAA`.
3. **Historial de Cambios (Changelog)**: Añadir una nueva entrada detallando:
   - Versión y fecha.
   - Módulos/archivos afectados.
   - Resumen claro de la mejora implementada.
