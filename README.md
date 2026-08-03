# Amwell (amwell)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
