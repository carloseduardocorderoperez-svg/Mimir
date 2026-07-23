# Protocolo Mimir

## Objetivo

Permitir que una persona o IA retome y actualice un proyecto sin depender de conversaciones anteriores.

## Orden de lectura

Al iniciar trabajo en un proyecto, leer en este orden:

1. `README.md` para entender propósito, alcance y estado general.
2. `CONTEXT.md` para conocer el objetivo, estado y siguiente acción.
3. Los documentos enlazados en `CONTEXT.md` bajo "Lecturas necesarias".
4. `TASKS.md` o `DECISIONS.md` solo cuando sean relevantes para el trabajo actual.

No es necesario leer todas las sesiones antiguas para comenzar.

## Orden de autoridad

Cuando haya contradicciones, prevalece este orden:

1. `CONTEXT.md` y `DECISIONS.md` vigentes.
2. `README.md`, `SPECS.md` y `ROADMAP.md`.
3. `TASKS.md`.
4. Registros de `03 Sessions/`.
5. `IDEAS.md` e `00 Inbox/`.

## Inicio de una sesión

1. Leer el Context Snapshot.
2. Confirmar la siguiente acción y el criterio de terminado.
3. Registrar una pregunta abierta antes de asumir información no documentada.

## Cierre de una sesión

1. Actualizar `TASKS.md` cuando cambie el estado de una tarea.
2. Registrar en `DECISIONS.md` toda decisión que afecte alcance, arquitectura o prioridades.
3. Actualizar `CONTEXT.md` con el estado, riesgos y siguiente acción reales.
4. Crear un registro breve en `03 Sessions/` usando la plantilla correspondiente.

## Reglas de escritura

- Separar hechos, decisiones, hipótesis e ideas.
- No presentar una inferencia de la IA como un hecho confirmado.
- Enlazar documentos relacionados en vez de duplicar contenido.
- Mantener `CONTEXT.md` breve, actual y accionable.
- Mover el material finalizado a `99 Archive/` sin eliminar su historia.