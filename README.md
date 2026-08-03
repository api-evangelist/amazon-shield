# Amazon Shield (amazon-shield)

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

AWS Shield is a managed Distributed Denial of Service (DDoS) protection service that safeguards applications running on AWS. It provides always-on detection and automatic inline mitigations that minimize application downtime and latency, with two tiers of protection - Shield Standard for automatic defense against common attacks and Shield Advanced for enhanced detection and 24/7 access to the DDoS Response Team.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/amazon-shield/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/amazon-shield/refs/heads/main/apis.yml)

## Tags

- AWS
- DDoS Protection
- Networking
- Security

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-05-19

## APIs

### AWS Shield API

The AWS Shield API provides programmatic access to manage DDoS protection for your AWS resources. It enables developers to create and manage protections, subscribe to Shield Advanced, configure emergency contacts, view attack details and statistics, and manage protection groups for coordinated defense across multiple resources.

- **Human URL:** [https://aws.amazon.com/shield/](https://aws.amazon.com/shield/)
- **Base URL:** `https://shield.amazonaws.com`

#### Tags

- AWS
- DDoS Protection
- Networking
- Security

#### Properties

- [Documentation](https://docs.aws.amazon.com/waf/latest/developerguide/shield-chapter.html)
- [OpenAPI](openapi/amazon-shield-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Pricing](https://aws.amazon.com/shield/pricing/)
- [Getting Started](https://aws.amazon.com/shield/getting-started/)
- [F A Q](https://aws.amazon.com/shield/faqs/)

## Common Properties

- [Portal](https://aws.amazon.com/)
- [Portal](https://aws.amazon.com/shield/)
- [Documentation](https://docs.aws.amazon.com/waf/latest/developerguide/shield-chapter.html)
- [Terms of Service](https://aws.amazon.com/service-terms/)
- [Privacy Policy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [GitHub Organization](https://github.com/aws)
- [Portal](https://console.aws.amazon.com/wafv2/shieldv2)
- [Sign Up](https://signin.aws.amazon.com/signup?request_type=register)
- [Login](https://aws.amazon.com/console/)
- [Status Page](https://health.aws.amazon.com/health/status)
- [Contact](https://aws.amazon.com/contact-us/)
- [JSON-LD](json-ld/amazon-shield-context-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON-LD](json-ld/amazon-shield-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/amazon-shield-api-attack-detail-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/amazon-shield-api-create-protection-group-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/amazon-shield-api-create-protection-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/amazon-shield-api-create-protection-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/amazon-shield-api-describe-attack-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/amazon-shield-api-describe-attack-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/amazon-shield-api-describe-protection-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/amazon-shield-api-describe-protection-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/amazon-shield-api-list-protections-request-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/amazon-shield-api-list-protections-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/amazon-shield-api-mitigation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/amazon-shield-api-protection-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/amazon-shield-api-summarized-counter-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/amazon-shield-api-tag-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/amazon-shield-protection-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/amazon-shield-api-attack-detail-structure.json)
- [JSON Structure](json-structure/amazon-shield-api-create-protection-group-request-structure.json)
- [JSON Structure](json-structure/amazon-shield-api-create-protection-request-structure.json)
- [JSON Structure](json-structure/amazon-shield-api-create-protection-response-structure.json)
- [JSON Structure](json-structure/amazon-shield-api-describe-attack-request-structure.json)
- [JSON Structure](json-structure/amazon-shield-api-describe-attack-response-structure.json)
- [JSON Structure](json-structure/amazon-shield-api-describe-protection-request-structure.json)
- [JSON Structure](json-structure/amazon-shield-api-describe-protection-response-structure.json)
- [JSON Structure](json-structure/amazon-shield-api-list-protections-request-structure.json)
- [JSON Structure](json-structure/amazon-shield-api-list-protections-response-structure.json)
- [JSON Structure](json-structure/amazon-shield-api-mitigation-structure.json)
- [JSON Structure](json-structure/amazon-shield-api-protection-structure.json)
- [JSON Structure](json-structure/amazon-shield-api-summarized-counter-structure.json)
- [JSON Structure](json-structure/amazon-shield-api-tag-structure.json)
- [JSON Structure](json-structure/amazon-shield-protection-structure.json)
- [Example](examples/amazon-shield-api-attack-detail-example.json)
- [Example](examples/amazon-shield-api-create-protection-group-request-example.json)
- [Example](examples/amazon-shield-api-create-protection-request-example.json)
- [Example](examples/amazon-shield-api-create-protection-response-example.json)
- [Example](examples/amazon-shield-api-describe-attack-request-example.json)
- [Example](examples/amazon-shield-api-describe-attack-response-example.json)
- [Example](examples/amazon-shield-api-describe-protection-request-example.json)
- [Example](examples/amazon-shield-api-describe-protection-response-example.json)
- [Example](examples/amazon-shield-api-list-protections-request-example.json)
- [Example](examples/amazon-shield-api-list-protections-response-example.json)
- [Example](examples/amazon-shield-api-mitigation-example.json)
- [Example](examples/amazon-shield-api-protection-example.json)
- [Example](examples/amazon-shield-api-summarized-counter-example.json)
- [Example](examples/amazon-shield-api-tag-example.json)
- [Example](examples/amazon-shield-protection-example.json)
- [Spectral Rules](rules/amazon-shield-spectral-rules.yml)
- [Vocabulary](vocabulary/amazon-shield-vocabulary.yaml)
- [OpenAPI](openapi/amazon-shield-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Integrations](https://aws.amazon.com/partners/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
