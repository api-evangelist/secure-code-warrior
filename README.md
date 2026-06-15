# Secure Code Warrior (secure-code-warrior)

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
