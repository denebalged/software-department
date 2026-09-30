# Modelo de datos (ERD)

## TL;DR
[Resumen del modelo en 3 líneas]

## Estado
draft | review | approved

## Fecha / Autor

## Diagrama
```mermaid
erDiagram
    TENANT ||--o{ USER : tiene
    TENANT ||--o{ PRODUCT : tiene
    PRODUCT ||--o{ STOCK_MOVEMENT : registraEntidades
[Entidad]

    Propósito:

    Campos clave:

    Índices:

    Reglas de integridad:

    Multi-tenant: [cómo se aísla]

Decisiones relacionadas

    ADR-XXXX

Preguntas abiertas

    [ ]