# Architecture

This document describes the proposed technical architecture for SALUD 360 ECUADOR. These are initial design decisions for an early-stage, open-source prototype, not integrations that are already implemented.

## Overview

SALUD 360 ECUADOR is designed as a modular web platform that helps organize information about healthcare facilities, services, declared operational capacity, and administrative referral processes. The architecture is intentionally modular so individual components can evolve independently and be adopted incrementally.

## Proposed stack

| Layer | Technology |
| --- | --- |
| Frontend | React + TypeScript + Vite |
| Backend / API | Python + FastAPI |
| Database | PostgreSQL |
| API style | REST |
| Future interoperability | HL7 FHIR (to be evaluated) |
| Containers | Docker |
| Testing | Pytest (backend), frontend testing tools |
| Version control | Git + GitHub |

## Suggested repository layout

```
SALUD-360-ECUADOR/
  backend/
    app/
      main.py
      api/
      core/
      models/
      schemas/
      services/
      repositories/
    tests/
  frontend/
    src/
      components/
      pages/
      layouts/
      services/
      hooks/
  database/
    schema.sql
    migrations/
  infrastructure/
    docker/
    deployment/
  docs/
```

## Modules

1. Appointment management
2. Healthcare capacity monitoring
3. Referral and counter-referral tracking
4. Analytics and reporting
5. Facility geolocation
6. Administration, roles and auditing

## Design principles

- Modularity: each module should be independently testable and deployable.
- Complementary, not a replacement: the platform is designed to complement existing institutional systems, not replace them.
- Privacy by design: see docs/data-protection.md.
- Interoperability-ready: data models should be designed with future HL7 FHIR alignment in mind, without requiring it from day one.

## Current status

No institutional integration (for example with MSP or IESS) is implemented or authorized today. This document reflects target architecture for the project's early design and prototype phase.
