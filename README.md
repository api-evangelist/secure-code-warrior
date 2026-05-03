# Secure Code Warrior (secure-code-warrior)

Secure Code Warrior is a developer-first security platform that provides security training, coaching, and assessments to help developers write secure code from the start. The platform offers over 50 programming language and framework combinations, covering OWASP Top 10 and CWE vulnerability categories through interactive challenges, assessments, tournaments, and guided learning courses. Secure Code Warrior exposes a REST API supporting user management, training progress reporting, assessment assignment and tracking, tournament management, metrics, and audit logging, with GitHub and CI/CD pipeline integrations for contextual in-workflow security coaching.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/secure-code-warrior/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
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
- **Modified:** 2026-05-02

## APIs

### Secure Code Warrior Portal API

The Secure Code Warrior Portal API provides programmatic access to the security training platform. The API enables user management, team administration, training progress reporting, assessment management, tournament administration, course assignments, and audit logging. It supports multiple API key types including Report, Admin, and Team keys for granular access control, with separate server instances for US and EU regions.

#### Properties

- [OpenAPI](openapi/secure-code-warrior-portal-openapi.yml)
- [API Documentation](https://portal-api.securecodewarrior.com/api/docs/v2/)

### Secure Code Warrior Direct Linking API

The Secure Code Warrior Direct Linking API is a RESTful JSON service that allows partners to retrieve application security training material including links to explainer videos and training exercises in over 50 programming languages. The API maps CWE and OWASP vulnerability references to contextually relevant training content.

#### Properties

- [Documentation](https://help.securecodewarrior.com/hc/en-us/articles/900005309583-Direct-Linking-API-Documentation)

## Common Properties

- [Website](https://www.securecodewarrior.com)
- [Portal API Documentation](https://portal-api.securecodewarrior.com/api/docs/v2/)
- [GitHub Organization](https://github.com/SecureCodeWarrior)
- [GitHub App](https://github.com/marketplace/secure-code-warrior-for-github)

## Artifacts

### JSON Schema

- [User Schema](json-schema/secure-code-warrior-user-schema.json)

### JSON Structure

- [Training Structure](json-structure/secure-code-warrior-training-structure.json)

### JSON-LD

- [Context](json-ld/secure-code-warrior-context.jsonld)

### Examples

- [Get Developer Leaderboard](examples/secure-code-warrior-get-leaderboard-example.json)

### Rules

- [Spectral Ruleset](rules/secure-code-warrior-rules.yml)

### Capabilities

- [Developer Security Training](capabilities/developer-security-training.yaml)
  - Shared: [Portal](capabilities/shared/portal.yaml)

### Vocabulary

- [Secure Code Warrior Vocabulary](vocabulary/secure-code-warrior-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
