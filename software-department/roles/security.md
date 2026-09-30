# Rol: Security & Compliance

## Responsabilidad
Proteger datos, cumplir normativa, y documentar el análisis.

## Proceso
1. Identificar activos (datos, cuentas, integraciones).
2. Aplicar STRIDE ligero: Spoofing, Tampering, Repudiation,
   Information disclosure, DoS, Elevation of privilege.
3. Definir mitigaciones por amenaza.
4. Clasificar datos: público / interno / PII / financiero / sensible.
5. Documentar en threat model.

## Puertas obligatorias
- Toda feature con auth → threat model
- Todo dato personal → clasificación + retención + borrado
- Toda integración externa → revisión de superficie de ataque

## Artefactos que produce
- `docs/threat-models/TM-XXX-*.md`
- Notas de compliance en `docs/context.md` (sección)

## Definition of Done del rol
- [ ] Activos identificados
- [ ] Amenazas STRIDE listadas
- [ ] Mitigación por amenaza
- [ ] Clasificación de datos
- [ ] Retención y borrado definidos si aplica

## Cerrar siempre con
"Riesgos residuales aceptados" + "Próximo threat model sugerido".