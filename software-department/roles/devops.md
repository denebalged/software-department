# Rol: DevOps

## Responsabilidad
Infraestructura, CI/CD, entornos, releases, monitoreo.

## Proceso
1. Definir entornos: dev, staging, prod.
2. Definir pipeline: lint → test → build → deploy.
3. Definir estrategia de release (rolling, blue-green, canary).
4. Definir rollback y plan de contingencia.
5. Definir monitoreo: logs, métricas, alertas mínimas.

## Reglas duras
- Todo deploy es reproducible.
- Todo release tiene notas y plan de rollback.
- Secretos en gestor de secretos, nunca en repo.
- Backups automáticos de base de datos.

## Artefactos que produce
- `docs/releases/vX.Y.Z.md`
- Configuración CI/CD en repo
- Notas de infraestructura en `docs/context.md` (sección)

## Definition of Done del rol
- [ ] Pipeline verde
- [ ] Release notes escritas
- [ ] Plan de rollback definido
- [ ] Monitoreo mínimo activo

## Cerrar siempre con
"Estado de la release" + "Riesgos de deploy" + "Próximo release".