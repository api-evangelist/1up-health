# 1upHealth (1up-health)

1upHealth is a FHIR-based health data interoperability platform providing REST APIs for connecting patient records across payers and providers. The platform supports HL7 FHIR R4, SMART on FHIR, OAuth 2.0, and FHIR Bulk Export, enabling health plans to acquire, manage, exchange, and analyze clinical and claims data in a HIPAA-compliant cloud environment. Products include Patient Access, Provider Access, Payer-to-Payer Data Exchange, Provider Directory, Electronic Prior Authorization, and Formulary APIs — supporting compliance with CMS Interoperability and Patient Access Final Rule, CMS Interoperability and Prior Authorization Final Rule, and related healthcare data mandates.

APIs.json: https://raw.githubusercontent.com/api-evangelist/1up-health/refs/heads/main/apis.yml

Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=1up-health-api-evangelist&utm_content=repo

## Tags

- FHIR
- Health Data
- Interoperability
- Patient Access
- HL7
- SMART on FHIR
- Healthcare
- Payer
- Claims
- Electronic Prior Authorization

## APIs

| API | Description |
|-----|-------------|
| 1upHealth FHIR R4 API | Core FHIR R4 REST API with full CRUD operations, dynamic search, Provenance, and AuditEvent tracking |
| 1upHealth Patient Access API | SMART on FHIR / OAuth 2.0 API enabling patients to share records with third-party applications |
| 1upHealth Provider Access API | FHIR Bulk Export for in-network providers to access member clinical, claims, and prior authorization data |
| 1upHealth Payer-to-Payer Data Exchange API | FHIR Bulk Export for payer data transfers during member plan transitions |
| 1upHealth Provider Directory API | FHIR-conformant provider directory aligned with DaVinci PDEX Plan Net IG |
| 1upHealth Electronic Prior Authorization API | AI-assisted ePA workflows using FHIR for CMS compliance |
| 1upHealth System Search API | Discovery API for searching and connecting to health systems and payer networks |

## Plans, Rate Limits, and FinOps

| Resource | File |
|----------|------|
| Plans & Pricing | [plans/1up-health-plans-pricing.yml](plans/1up-health-plans-pricing.yml) |
| Rate Limits | [rate-limits/1up-health-rate-limits.yml](rate-limits/1up-health-rate-limits.yml) |
| FinOps | [finops/1up-health-finops.yml](finops/1up-health-finops.yml) |

Pricing is enterprise/custom — contact 1upHealth directly. Historical per-connection pricing ranged from $200–$450/month. All API products require a 1up Dev Portal account to obtain OAuth 2.0 credentials.

## Timestamps

- **Created**: 2026-06-12
- **Modified**: 2026-06-12

## Common

| Type | URL |
|------|-----|
| Website | https://1up.health/ |
| Documentation | https://docs.1up.health/docs |
| GitHub | https://github.com/1uphealth |
| LinkedIn | https://www.linkedin.com/company/1uphealth/ |
| X | https://x.com/1up_health |
| Blog | https://1up.health/blog |
| Status Page | https://status.1up.health/ |
| Plans | [plans/1up-health-plans-pricing.yml](plans/1up-health-plans-pricing.yml) |
| Rate Limits | [rate-limits/1up-health-rate-limits.yml](rate-limits/1up-health-rate-limits.yml) |
| FinOps | [finops/1up-health-finops.yml](finops/1up-health-finops.yml) |

## Maintainers

| Name | Email |
|------|-------|
| Kin Lane | kin@apievangelist.com |
