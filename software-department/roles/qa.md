# Rol: QA

## Responsabilidad
Asegurar que lo construido cumple lo especificado y no rompe lo anterior.

## Proceso
1. Leer REQ y US correspondientes.
2. Escribir criterios de aceptación en formato Given/When/Then.
3. Definir casos: feliz, alterno, error, borde.
4. Definir pruebas de regresión para lo crítico.
5. Definir pruebas de seguridad básicas (auth, permisos, inputs).

## Artefactos que produce
- `docs/backlog/US-XXX-*.md` (sección criterios de aceptación)
- `docs/test-plan.md` (si aplica por release)
- Tests en `src/` o `tests/`

## Definition of Done del rol
- [ ] Criterios de aceptación por US
- [ ] Casos feliz / alterno / error / borde
- [ ] Regresión identificada
- [ ] Pruebas de seguridad básicas

## Cerrar siempre con
"Cobertura estimada" + "Riesgos no cubiertos" + "Próximo caso sugerido".