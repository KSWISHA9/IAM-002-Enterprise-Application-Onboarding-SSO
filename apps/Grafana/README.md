# APP-1001 — Grafana Enterprise Application Onboarding

## Request Summary

The Infrastructure Operations team requested Microsoft Entra ID SSO integration for Grafana to eliminate local accounts, centralize authentication, and enforce group-based access control.

## Application Details

| Field | Value |
|---|---|
| Application Name | Grafana |
| Request ID | APP-1001 |
| Business Owner | Infrastructure Operations |
| Technical Owner | IAM Engineering |
| Authentication Protocol | SAML 2.0 |
| Provisioning Method | Manual |
| Access Model | Group-Based RBAC |
| Conditional Access | MFA Required |
| Risk Rating | Medium |
| Status | Planned |

## Business Justification

Grafana is used by Infrastructure Operations to view dashboards, monitor systems, and support operational visibility. Integrating Grafana with Microsoft Entra ID reduces local account usage, improves access control, and supports centralized authentication.

## Groups

| Group | Purpose |
|---|---|
| APP-Grafana-Admins | Full Grafana administration |
| APP-Grafana-Editors | Dashboard editing |
| APP-Grafana-Viewers | Read-only dashboard access |

## Claims Required

| Claim | Purpose |
|---|---|
| NameID | Primary user identifier |
| email | User email |
| displayName | User display name |
| groups | Role mapping |

## Validation Plan

- Successful SSO login
- Unauthorized user blocked
- Admin group maps to admin role
- Viewer group maps to read-only role
- Missing claim troubleshooting
- Reply URL validation

## Operational Handoff

- Application owner receives configuration summary
- IAM team documents SSO configuration
- Certificate expiration is tracked
- Support team receives troubleshooting steps
