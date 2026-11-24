# Data Protection

Protecting information is a core principle of SALUD 360 ECUADOR, given the sensitivity of healthcare-related data.

## Principles

- Privacy by design: privacy considerations are part of the architecture from the start, not added afterward.
- Data minimization: collect and store only what is operationally necessary.
- Role-based access control.
- Encryption of sensitive information, in transit and at rest.
- Audit logging of relevant operations.
- Secure credential management (no secrets committed to the repository).
- Data retention and deletion policies.
- Regular security assessments as the codebase matures.
- Compliance with applicable Ecuadorian law, including the Ley Orgánica de Protección de Datos Personales (LOPDP).

## Development data

During development, this project uses synthetic or properly anonymized data only.

Real personal data, health data, or clinical information must never be committed to this repository, included in test fixtures, or used in demos. If such data is found, report it immediately following the process in SECURITY.md so it can be removed.

## Scope and limitations

SALUD 360 ECUADOR is an early-stage, open-source prototype. It is not a certified medical device and does not store or process real patient records today. Any future pilot that would involve real institutional or patient data would require, at minimum:

- Institutional authorization.
- A data protection / privacy impact assessment.
- A security assessment.
- Legal review against applicable regulations.
- Appropriate governance and oversight.

None of these steps have been completed, and none are implied by the existence of this repository.
