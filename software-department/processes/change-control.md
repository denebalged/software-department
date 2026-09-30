# Proceso: Change Control

## Cuándo
Antes de modificar algo ya aprobado (REQ, ADR, ERD, API).

## Reglas
1. No se edita un artefacto aprobado. Se crea uno nuevo.
2. El nuevo marca `superseded` al anterior.
3. Se registra motivo del cambio.
4. Se actualizan dependencias (US, tests, código).

## Formato
- Artefacto origen → Artefacto nuevo → Motivo → Impacto

## Salida
- Cambio documentado y trazable