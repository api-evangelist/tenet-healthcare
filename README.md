# Tenet Healthcare

Tenet Healthcare is a diversified healthcare services company and Fortune 500 organization operating regionally focused, integrated healthcare delivery networks. The company operates acute care hospitals, ambulatory surgery centers (ASCs), and physician practices across the United States through United Surgical Partners International (USPI) and Tenet Health. Tenet also provides revenue cycle management services through Conifer Health Solutions.

**Website:** [https://www.tenethealth.com](https://www.tenethealth.com)
**Corporate:** [https://www.tenetcorporate.com](https://www.tenetcorporate.com)
**Investor Relations:** [https://ir.tenethealth.com](https://ir.tenethealth.com)

**Tags:** Healthcare, Hospitals, Ambulatory Surgery Centers, Revenue Cycle Management, Fortune 500

**Modified:** 2026-05-03

---

## Subsidiaries

| Subsidiary | Description | Website |
|---|---|---|
| Tenet Health | Hospital operations network | https://www.tenethealth.com |
| USPI | United Surgical Partners International - ambulatory surgery centers | https://www.uspi.com |
| Conifer Health Solutions | Revenue cycle management services | https://www.coniferhealth.com |

---

## APIs

### Conifer Health Solutions Revenue Cycle API

Revenue cycle management API from Conifer Health Solutions providing end-to-end RCM services including patient access, health information management, patient financial services, and clinical revenue integrity.

**Human URL:** [https://www.coniferhealth.com/](https://www.coniferhealth.com/)

**Tags:** Revenue Cycle Management, Healthcare Finance, Patient Access, Claims Management

| Property | URL |
|---|---|
| Website | https://www.coniferhealth.com/ |
| Services | https://www.coniferhealth.com/services/ |

---

### USPI Ambulatory Surgery Center API

United Surgical Partners International integration APIs for ambulatory surgery center scheduling, patient registration, procedure management, and clinical data exchange.

**Human URL:** [https://www.uspi.com/](https://www.uspi.com/)

**Tags:** Ambulatory Surgery Centers, Surgical Scheduling, Patient Registration

| Property | URL |
|---|---|
| Website | https://www.uspi.com/ |
| For Physicians | https://www.uspi.com/for-physicians/ |

---

### Tenet Health Patient Portal API

Patient-facing digital health API enabling access to medical records, appointment scheduling, test results, care team communications, and bill payment. HL7 FHIR R4 compatible with SMART on FHIR authorization.

**Human URL:** [https://www.tenethealth.com/patients](https://www.tenethealth.com/patients)

**Tags:** Patient Portal, Medical Records, Appointment Scheduling, FHIR

| Property | URL |
|---|---|
| Website | https://www.tenethealth.com/patients |
| FHIR Standard | https://hl7.org/fhir/R4/ |
| OpenAPI (local) | openapi/tenet-healthcare-fhir-openapi.yml |

---

## Common Properties

| Property | URL |
|---|---|
| Corporate Website | https://www.tenetcorporate.com |
| Patient Website | https://www.tenethealth.com |
| Investor Relations | https://ir.tenethealth.com |
| Press Room | https://www.tenethealth.com/news |
| Careers | https://careers.tenethealth.com |
| Conifer Health Solutions | https://www.coniferhealth.com |
| USPI | https://www.uspi.com |

---

## Artifacts

### OpenAPI Specifications

| API | File |
|---|---|
| FHIR R4 Patient API | [openapi/tenet-healthcare-fhir-openapi.yml](openapi/tenet-healthcare-fhir-openapi.yml) |

### JSON Schema

| Schema | File |
|---|---|
| Patient (FHIR R4) | [json-schema/tenet-healthcare-patient-schema.json](json-schema/tenet-healthcare-patient-schema.json) |
| Appointment (FHIR R4) | [json-schema/tenet-healthcare-appointment-schema.json](json-schema/tenet-healthcare-appointment-schema.json) |

### JSON Structure

| Structure | File |
|---|---|
| Patient | [json-structure/tenet-healthcare-patient-structure.json](json-structure/tenet-healthcare-patient-structure.json) |

### JSON-LD

| Context | File |
|---|---|
| Tenet Healthcare Context | [json-ld/tenet-healthcare-context.jsonld](json-ld/tenet-healthcare-context.jsonld) |

### Examples

| Example | File |
|---|---|
| Get Patient | [examples/tenet-healthcare-get-patient-example.json](examples/tenet-healthcare-get-patient-example.json) |
| List Appointments | [examples/tenet-healthcare-list-appointments-example.json](examples/tenet-healthcare-list-appointments-example.json) |

### Spectral Rules

| Ruleset | File |
|---|---|
| Tenet Healthcare API Rules | [rules/tenet-healthcare-rules.yml](rules/tenet-healthcare-rules.yml) |

### Naftiko Capabilities

**Shared Definitions:**

| API | File |
|---|---|
| Tenet FHIR R4 | [capabilities/shared/tenet-fhir.yaml](capabilities/shared/tenet-fhir.yaml) |

**Workflow Capabilities:**

| Workflow | Description | File |
|---|---|---|
| Patient Care | Patient records, appointments, clinical data, and care coordination | [capabilities/patient-care.yaml](capabilities/patient-care.yaml) |

### Vocabulary

| Vocabulary | File |
|---|---|
| Tenet Healthcare Domain Vocabulary | [vocabulary/tenet-healthcare-vocabulary.yml](vocabulary/tenet-healthcare-vocabulary.yml) |

---

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
