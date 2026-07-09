# Security, Privacy, and Compliance Brief

## Risk Level
Low / Medium / High. Reason:

## Data Classification
| Data | Classification | Stored? | Shared? | Retention |
|---|---|---|---|---|
|  | Public/Internal/Confidential/Sensitive |  |  |  |

## Security Requirements
| ID | Requirement | Verification |
|---|---|---|
| SEC-001 | Validate all user-controlled input | Tests |
| SEC-002 | Enforce server-side authorization | Tests |
| SEC-003 | Do not log secrets or sensitive personal data | Log review |
| SEC-004 | Store secrets outside source control | Secret scan |

## Abuse Cases
| ID | Abuse Case | Mitigation |
|---|---|---|
| ABUSE-001 | Unauthorized access to another user's data | Ownership checks |
