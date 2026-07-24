# Amwell (amwell)

Amwell (American Well) is a United States telehealth and hybrid-care technology company headquartered in Boston, Massachusetts, whose Converge platform delivers virtual and in-person care at scale for health systems, health plans, and government programs. Converge is built on an open architecture whose APIs leverage HL7 FHIR, single sign-on, and embedded telehealth mobile and web SDKs (iOS, Android, web), with verified embedded-telehealth integrations for the Epic and Oracle Cerner EHRs. The developer surface is a gated partner developer portal (developers.amwell.com) — the REST/FHIR API reference, SDKs, and sandbox sit behind a partner login rather than an anonymous public spec.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/amwell/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/amwell/refs/heads/main/apis.yml)

## Tags

- Healthcare
- United States
- Telehealth
- Virtual Care
- FHIR
- HL7
- Interoperability
- EHR
- SDK

## Timestamps

- **Created:** 2026-07-24
- **Modified:** 2026-07-24

## APIs

### Amwell Converge Platform API

Amwell's Converge platform REST APIs, which leverage HL7 FHIR and single sign-on, let partners embed and orchestrate virtual care — urgent, scheduled, behavioral, and specialty visits — into their own applications, patient portals, and clinical workflows. Access is provisioned through the gated Amwell partner developer portal.

- **Human URL:** [https://developers.amwell.com](https://developers.amwell.com)

#### Tags

- Telehealth
- FHIR
- Virtual Care

#### Properties

- [Developer Portal](https://developers.amwell.com)
- [Documentation](https://business.amwell.com/the-amwell-platform)

### Amwell Telehealth SDK

Amwell's embedded telehealth software development kits for iOS, Android, and web, enabling organizations to plug live virtual visits directly into their own consumer and clinical applications. SDK documentation and downloads are distributed through the gated Amwell developer portal.

- **Human URL:** [https://developers.amwell.com](https://developers.amwell.com)

#### Tags

- SDK
- Telehealth
- Mobile

#### Properties

- [Developer Portal](https://developers.amwell.com)
- [Documentation](https://business.amwell.com/the-amwell-platform)

### Amwell EHR Integration

Amwell's verified embedded-telehealth integrations for the Epic and Oracle Cerner electronic health records, using single sign-on and FHIR-based workflows to launch virtual visits from within existing EHR and patient-portal experiences.

- **Human URL:** [https://business.amwell.com/the-amwell-platform](https://business.amwell.com/the-amwell-platform)

#### Tags

- EHR
- Interoperability
- FHIR

#### Properties

- [Documentation](https://business.amwell.com/the-amwell-platform)

## Common Properties

- [Website](https://www.amwell.com)
- [Developer Portal](https://developers.amwell.com)
- [Documentation](https://business.amwell.com/the-amwell-platform)
- [Blog](https://business.amwell.com/blog)
- [Status Page](https://status.amwell.com)
- [Support](https://business.amwell.com/contact-us/)
- [Privacy Policy](https://business.amwell.com/privacy-policy/)
- [LinkedIn](https://www.linkedin.com/company/amwell)

## Review

Amwell runs a real, live developer portal at [developers.amwell.com](https://developers.amwell.com) (HTTP 200), but its REST/FHIR API reference, SDKs, and sandbox are gated behind a partner login. No anonymous FHIR CapabilityStatement, SMART-on-FHIR configuration, or downloadable OpenAPI/Swagger document could be retrieved — the developer, docs, and FHIR subdomains all redirect to a browser-check gate. See [`review.yml`](review.yml) for the full finding.

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
