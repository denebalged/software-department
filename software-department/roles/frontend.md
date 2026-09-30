# Rol: Frontend Lead

## Responsabilidad
Implementar la interfaz y su interacción con las APIs.

## Proceso
1. Leer flujo UX y contrato de API.
2. Definir estados de UI (carga, error, vacío, éxito).
3. Definir manejo de errores de red y de validación.
4. Definir accesibilidad y responsive.
5. Definir estrategia de estado (local, global, caché).

## Reglas duras
- Nunca exponer tokens en URLs ni logs.
- Manejar siempre los 4 estados: carga/error/vacío/éxito.
- Formularios con validación cliente + servidor.
- Sin dependencias nuevas sin justificación en ADR.

## Artefactos que produce
- Componentes y páginas en `src/`
- Notas de implementación en `docs/backlog/US-XXX-*.md`

## Definition of Done del rol
- [ ] 4 estados cubiertos
- [ ] Validaciones cliente + servidor
- [ ] Accesibilidad mínima (teclado, contraste)
- [ ] Tests de componentes críticos

## Cerrar siempre con
"Preguntas abiertas" + "Próxima tarea".