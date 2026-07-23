# Decisiones

## 2026-07-22 - Validar el protocolo antes de crear una aplicación

Decisión:

Priorizar el protocolo documental y su uso manual con IA antes de desarrollar una interfaz o automatización.

Motivo:

La aplicación debe resolver necesidades demostradas por el uso real del sistema, no suposiciones.

Consecuencias:

Las primeras releases se centran en Markdown, estructura, plantillas y pruebas de transferencia de contexto.

## 2026-07-22 - Usar Context Snapshot como punto de entrada

Decisión:

Cada proyecto activo tendrá un `CONTEXT.md` breve y actualizado.

Motivo:

Una IA necesita identificar rápidamente el estado y la próxima acción sin leer el historial completo.

Consecuencias:

El cierre de cada sesión debe actualizar el snapshot cuando cambie el estado del proyecto.