# Secure Code Warrior (secure-code-warrior)

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

Secure Code Warrior is a developer-first security platform that provides security training, coaching, and assessments to help developers write secure code from the start. The platform offers over 50 programming language and framework combinations, covering OWASP Top 10 and CWE vulnerability categories through interactive challenges, assessments, tournaments, and guided learning courses. Secure Code Warrior exposes a REST API supporting user management, training progress reporting, assessment assignment and tracking, tournament management, metrics, and audit logging, with GitHub and CI/CD pipeline integrations for contextual in-workflow security coaching.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/secure-code-warrior/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/secure-code-warrior/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Application Security
- Developer Training
- Security Education
- AppSec
- Secure Coding
- DevSecOps

## Timestamps

- **Created:** 2026-05-02
- **Modified:** 2026-05-19

## APIs

### Secure Code Warrior Portal API

The Secure Code Warrior Portal API provides programmatic access to the Secure Code Warrior developer security training platform. The API enables user management, team administration, training progress reporting, assessment management, tournament administration, course assignments, and audit logging. It supports multiple API key types including Report, Admin, and Team keys for granular access control, with separate server instances for US and EU regions.

- **Human URL:** [https://portal-api.securecodewarrior.com/api/docs/v2/](https://portal-api.securecodewarrior.com/api/docs/v2/)
- **Base URL:** `https://portal-api.securecodewarrior.com/api/v2`

#### Tags

- Security Training
- Application Security
- Developer Training
- Reporting
- User Management

#### Properties

- [OpenAPI](openapi/secure-code-warrior-portal-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/secure-code-warrior-portal.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/secure-code-warrior-portal.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Documentation](https://portal-api.securecodewarrior.com/api/docs/v2/)
- [Documentation](https://help.securecodewarrior.com/hc/en-us/sections/360006026452-API)

### Secure Code Warrior Direct Linking API

The Secure Code Warrior Direct Linking API is a RESTful JSON service that allows partners to retrieve application security training material including links to explainer videos and training exercises in over 50 programming languages and frameworks. The API maps Common Weakness Enumeration (CWE) and OWASP vulnerability references to contextually relevant training content, enabling integration with GitHub, SARIF code scanning alerts, and other developer workflow tools.

- **Human URL:** [https://help.securecodewarrior.com/hc/en-us/articles/900005309583-Direct-Linking-API-Documentation](https://help.securecodewarrior.com/hc/en-us/articles/900005309583-Direct-Linking-API-Documentation)

#### Tags

- Security Training
- Application Security
- CWE
- OWASP
- GitHub Integration

#### Properties

- [Documentation](https://help.securecodewarrior.com/hc/en-us/articles/900005309583-Direct-Linking-API-Documentation)
- [Postman Collection](collections/secure-code-warrior-portal.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/secure-code-warrior-portal.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.securecodewarrior.com)
- [Documentation](https://portal-api.securecodewarrior.com/api/docs/v2/)
- [Documentation](https://help.securecodewarrior.com/hc/en-us/sections/360006026452-API)
- [Documentation](https://help.securecodewarrior.com/hc/en-us/articles/900005309583-Direct-Linking-API-Documentation)
- [GitHub Organization](https://github.com/SecureCodeWarrior)
- [Git Hub App](https://github.com/marketplace/secure-code-warrior-for-github)
- [Getting Started](https://help.securecodewarrior.com/hc/en-us/articles/360036036512-How-to-enable-API-access)
- [JSON Schema](json-schema/secure-code-warrior-user-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/secure-code-warrior-training-structure.json)
- [J S O N L D Context](json-ld/secure-code-warrior-context.jsonld)
- [Example](examples/secure-code-warrior-get-leaderboard-example.json)
- [Spectral Ruleset](rules/secure-code-warrior-rules.yml)
- [Vocabulary](vocabulary/secure-code-warrior-vocabulary.yml)
- [Integrations](https://www.securecodewarrior.com/product/integrations)
- [L L Ms Txt](https://www.securecodewarrior.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
