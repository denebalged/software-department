# Instrucciones para agentes IA

Este proyecto usa la skill "Software Department".

## Carga en capas (no leer todo)
1. Lee `.software-department/SKILL.md` (núcleo).
2. Lee `.software-department/LOADING.md` (reglas de carga).
3. Lee `docs/.session.md` si existe.
4. Carga SOLO el rol necesario: `.software-department/roles/INDEX.md`.
5. Carga SOLO la plantilla necesaria: `.software-department/templates/INDEX.md`.

## Nunca
- Leer roles/ ni templates/ completos.
- Releer lo ya leído.
- Generar artefactos sin leer contexto.

## Antes de responder
- Revisar `docs/decisions/INDEX.md` para no contradecir ADRs.
- Si contradice un ADR, proponer uno nuevo que lo supersede.

## Al cerrar
- Actualizar `docs/.session.md`.
- Proponer próximo artefacto.