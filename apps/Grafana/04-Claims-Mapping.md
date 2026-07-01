# 04 - Claims Mapping

## Objective

Configure SAML claims required for Grafana authentication and future role mapping.

## Claims Used

| Claim | Purpose |
|---|---|
| NameID | Primary login identifier |
| mail | User email address |
| name | Display name |
| groups | Group-based RBAC mapping |

## Group Claim

The group claim was added so Grafana can receive Microsoft Entra group membership data for role-based access decisions.

## Result

Default claims were reviewed and a group claim was added for application authorization.
