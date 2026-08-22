# Tenet Healthcare (tenet-healthcare)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Tenet Healthcare is a diversified healthcare services company and Fortune 500 organization operating regionally focused, integrated healthcare delivery networks. The company operates acute care hospitals, ambulatory surgery centers (ASCs), and physician practices across the United States through United Surgical Partners International (USPI) and Tenet Health. Tenet also provides revenue cycle management services through Conifer Health Solutions.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/tenet-healthcare/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/tenet-healthcare/refs/heads/main/apis.yml)

## Tags

- Healthcare
- Hospitals
- Ambulatory Surgery Centers
- Revenue Cycle Management
- Fortune 500

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-05-19

## APIs

### Conifer Health Solutions Revenue Cycle API

Revenue cycle management API from Conifer Health Solutions, a Tenet Healthcare subsidiary providing end-to-end RCM services including patient access, health information management, patient financial services, and clinical revenue integrity for hospitals and health systems.

- **Human URL:** [https://www.coniferhealth.com/](https://www.coniferhealth.com/)
- **Base URL:** `https://api.coniferhealth.com`

#### Tags

- Revenue Cycle Management
- Healthcare Finance
- Patient Access
- Claims Management
- Healthcare

#### Properties

- [Website](https://www.coniferhealth.com/)
- [Documentation](https://www.coniferhealth.com/services/)
- [Postman Collection](collections/tenet-healthcare-fhir.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tenet-healthcare-fhir.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### USPI Ambulatory Surgery Center API

United Surgical Partners International (USPI) integration APIs for ambulatory surgery center scheduling, patient registration, procedure management, and clinical data exchange. USPI operates over 600 ambulatory surgery centers and surgical hospitals across the United States.

- **Human URL:** [https://www.uspi.com/](https://www.uspi.com/)
- **Base URL:** `https://api.uspi.com`

#### Tags

- Ambulatory Surgery Centers
- Surgical Scheduling
- Patient Registration
- Healthcare

#### Properties

- [Website](https://www.uspi.com/)
- [Documentation](https://www.uspi.com/for-physicians/)
- [Postman Collection](collections/tenet-healthcare-fhir.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tenet-healthcare-fhir.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tenet Health Patient Portal API

Patient-facing digital health API enabling access to medical records, appointment scheduling, test results, care team communications, and bill payment across Tenet Health hospital network. Integrates with MyChart and other patient portal platforms. HL7 FHIR R4 compatible.

- **Human URL:** [https://www.tenethealth.com/patients](https://www.tenethealth.com/patients)
- **Base URL:** `https://api.tenethealth.com/patient`

#### Tags

- Patient Portal
- Medical Records
- Appointment Scheduling
- FHIR
- Healthcare

#### Properties

- [Website](https://www.tenethealth.com/patients)
- [F H I R  Standard](https://hl7.org/fhir/R4/)
- [OpenAPI](openapi/tenet-healthcare-fhir-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tenet-healthcare-fhir.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tenet-healthcare-fhir.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/tenet-healthcare)
- [Website](https://www.tenethealth.com)
- [Corporate  Website](https://www.tenetcorporate.com)
- [Investor  Relations](https://ir.tenethealth.com)
- [Press  Room](https://www.tenethealth.com/news)
- [Careers](https://careers.tenethealth.com)
- [Conifer  Health  Solutions](https://www.coniferhealth.com)
- [U S P I](https://www.uspi.com)
- [JSON-LD](json-ld/tenet-healthcare-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/tenet-healthcare-patient-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/tenet-healthcare-appointment-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/tenet-healthcare-patient-structure.json)
- [Spectral Rules](rules/tenet-healthcare-rules.yml)
- [Vocabulary](vocabulary/tenet-healthcare-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
