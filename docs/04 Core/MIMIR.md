# Mimir

## Sistema de conocimiento para proyectos asistidos por IA

Versión: `0.2.0`

Estado: Experimental

## Propósito

Mimir es un estándar abierto para gestionar conocimiento de proyectos con ayuda de IA. La información vive en archivos Markdown: los chats son temporales y los documentos son permanentes.

## Principios

- El conocimiento pertenece al proyecto, no a una IA concreta.
- Los documentos son la fuente de verdad.
- El formato debe ser legible por personas y compatible con cualquier IA.
- El sistema debe poder mantenerse desde un teléfono.
- Cada proyecto debe poder recuperar su estado sin leer el historial completo de conversaciones.

## Estructura del vault

```text
docs/
├── 00 Inbox/       # Capturas pendientes de clasificar
├── 01 Projects/    # Proyectos activos
├── 02 Knowledge/   # Conocimiento reutilizable
├── 03 Sessions/    # Registro cronológico de trabajo
├── 04 Core/        # Estándar, protocolo y plantillas de Mimir
└── 99 Archive/     # Material finalizado
```

## Documentos del estándar

- `PROTOCOL.md`: cómo una persona o IA debe leer y actualizar el vault.
- `TEMPLATES.md`: plantillas para documentos de proyecto y sesiones.
- `CHANGELOG.md`: cambios relevantes del estándar Mimir.

## Documentos mínimos de un proyecto

- `README.md`: propósito, alcance y estado general.
- `CONTEXT.md`: snapshot operativo para retomar el trabajo.
- `TASKS.md`: trabajo accionable y priorizado.
- `DECISIONS.md`: decisiones vigentes y su justificación.

Los documentos opcionales incluyen `IDEAS.md`, `SPECS.md` y `ROADMAP.md`.

## Estado actual

Mimir v0.2 define el protocolo mínimo y las plantillas para validar la transferencia de contexto entre sesiones.

Última actualización: 2026-07-22
